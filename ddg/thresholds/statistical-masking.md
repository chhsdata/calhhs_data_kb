# Statistical Masking

Statistical masking provides an extensive set of tools that can be used to mitigate potential risk in a given data presentation. As discussed in Section 4.4, the data releaser will assess the need for statistical masking when the assessment in Step 3 identified potential risk. Each department will document statistical masking processes that are routinely used in data preparation for public release.

As discussed in section 4.4, initial methods to address sensitive or small cells, as well as complimentary cells include the following:

* Reduce Table Dimensions
* Reduce Granularity of Variable(s), aka Recoding or Aggregation
* Cell Suppression and Complementary Cell Suppression

Small cell sizes are typically encountered when one of the following conditions is met.

1. Multiple variables. This most often occurs in a pivot table presentation or a query interface where a user may have occurrences of disease X, stratified by county, stratified by sex, stratified by race and ethnicity.&#x20;
2. Granular variables. The more granular the variable the smaller the potential numerator and denominator. This most commonly occurs with shortening the time period of reporting (weekly) or making the geography more specific (zip code or census tract). However, it can also occur when there are many categories for a variable. An example of this is aid codes in Medi-Cal where there are almost 200 aid codes.
3. Rare events. Examples include diseases such as hemophilia. Examples of incidents may result from mass trauma events such as a plane crash or multi-car accident.&#x20;

In each of these cases, statistical masking may be addressed in a number of ways. For this reason, it is important to keep in mind the purpose for the reporting so that the method chosen for masking can still maximize the usefulness of the data provided. Choices for each condition are highlighted below.&#x20;

1. Multiple variables. Options include separating the table into multiple tables that limit the number of variables included in each table; decreasing the granularity of the variables included in the table; or suppressing the small cell with an indicator that it is less than 11.
2. Granular variables. A common approach to this situation would be to decrease the granularity of the variables although suppressing the small cell with an indicator that it is less than 11 is also an option.
3. Rare events. In these cases it becomes very challenging to suppress the value in a way that it will not be able to be used with other public information to identify individuals. Additionally, with rare events, there is more significance in the variance of small numbers.

In addition to small cells, complementary cells must also be suppressed. Complementary cells are those that must be suppressed to prevent someone from calculating the suppressed cell based on row or column totals in combination with other data in that row or column.&#x20;

Suppressing small cell values and complimentary cells can be done in two ways:

{% tabs %}
{% tab title="Small Cell Suppression: Method 1" %}
* Use a symbol to indicate the cell has been suppressed. Identify any other cells (complimentary cells) that can be used to calculate the small cell and use a symbol to indicate the cell has been suppressed. When submitting data to the Open Data Portal or any departmental websites, use the CalHHS suppression symbols and guidelines indicated in the CalHHS guidelines\[1]
* Use the symbols "S," "\*," or similar symbols in the data for the PRA or other outstanding requests. When suppressing values, it is recommended to use the following footnote to indicate the suppression.
* “Values or cells marked as “S”, “\*”, or a similar symbol in the data represents that the member counts were not shown for counts less than 11 in accordance with the CalHHS DDG v2.0. Additional suppression has been applied to complementary cells to prevent the inference of the values of suppressed cells.
{% endtab %}

{% tab title="Small Cell Suppression: Method 2" %}
* Use a symbol to indicate the cell has been suppressed or leave the cell blank and remove the value from all pertinent row and column totals so that the cell cannot be calculated. This negates the need for the evaluation of complementary cells.

{% hint style="warning" %}
This method must be used with great caution because the totals may actually be published in other non-related tables. For this reason, the method is not recommended.
{% endhint %}
{% endtab %}
{% endtabs %}

### Suppression Rules

1. Suppress cells (e.g., count of members and services provided to members) <11 (excluding 0) when total score ≥13.
2. After the cell suppression (<11 excluding 0) is completed, complementary cell suppression is also required so that the suppressed cells cannot be re-identified.
3. Values of 0 should not be suppressed since a non-event cannot be identified.
4. Suppression is also required for financial data which can be associated with members or services provided to members <11 (excluding 0).
5. Suppression is required for all the associated statistical entries (e.g., Prevalence rates, percentages, Mean etc.) of the suppressed cells.
6. An additional complementary cell needs to be suppressed if (a) OR (b) is true:
   1. all of the values suppressed in a specific group (row or column) are each ≤ 3 (1, 2, 3 excluding 0)
   2. the sum of the values suppressed is less than 11

The above-mentioned suppression rules minimize the risk of re-identification most of the times. However, an expert should treat each data on case-by-case basis and add additional rules if there is a risk of re-identification in any data. Please see below a couple of examples in which all the above rules are covered but if it is revealed that the cells are suppressed due to regular suppression (<11) and not for complementary suppression then all the suppressed cells can be re-identified.

### Suppression Examples

{% tabs %}
{% tab title="Example 1: 10-10-10" %}
#### Count of Medi-Cal Members by Age

In this example, if we suppress the three highlighted cells (in yellow) and if we reveal that it is due to regular suppression of cells <11 then anyone can guess that each cell is 10. In this case, either we should not specify that the three cells are <11 or suppress a complementary cell (in orange) so that the three cells highlighted in yellow could not be identified.

<table data-full-width="true"><thead><tr><th>Age</th><th>Count</th></tr></thead><tbody><tr><td>A1</td><td><mark style="background-color:yellow;">10</mark></td></tr><tr><td>A2</td><td><mark style="background-color:red;">14</mark></td></tr><tr><td>A3</td><td><mark style="background-color:yellow;">10</mark></td></tr><tr><td>A4</td><td><mark style="background-color:yellow;">10</mark></td></tr><tr><td>A5</td><td>0</td></tr><tr><td>A6</td><td>0</td></tr><tr><td>A7</td><td>0</td></tr><tr><td>A8</td><td>30</td></tr><tr><td>Total</td><td>74</td></tr></tbody></table>


{% endtab %}

{% tab title="Example 2: 10-9" %}
#### Count of Medi-Cal Members by Age

In this example, if we suppress the two highlighted cells (in yellow) and if we reveal that it is due to regular suppression of cells <11 then there are only 2 possible combinations (A1=10, A3=9) or (A1=9, A3=10). In this case, either we should not specify that the two cells are <11 or suppress a complementary cell (in orange) so that the cells highlighted in yellow could not be identified.

| Age   | Count                                            |
| ----- | ------------------------------------------------ |
| A1    | <mark style="background-color:yellow;">10</mark> |
| A2    | <mark style="background-color:red;">14</mark>    |
| A3    | <mark style="background-color:yellow;">9</mark>  |
| A4    | 17                                               |
| A5    | 0                                                |
| A6    | 0                                                |
| A7    | 0                                                |
| A8    | 30                                               |
| Total | 80                                               |
{% endtab %}

{% tab title="Example 3. When to suppress 0?" %}
#### Counts and Percentages of Medi-Cal Members by County

In this example, the percentage of 0.0 should not be suppressed for County ZZZ because it is based on a non-event. However, the percentage of 0.0 for County XXX needs to be suppressed because it is due to rounding of numbers. For example, if the denominator for the County XXX percentage is 7,500, a count of 4 would have a rounded percentage of 0.1. Therefore, it could be inferred that the count for County XXX is 1, 2, or 3 because a count of 3 is the highest value that would have a rounded percentage of 0.0 and counts of 0 are not suppressed. Consequently, summary statistics based on suppressed counts should not be reported even if the rounded value is 0 due to the potential for the information to be used for inference of suppressed values.

| County | Count                                           | Percent                                           |
| ------ | ----------------------------------------------- | ------------------------------------------------- |
| XXX    | <mark style="background-color:yellow;">3</mark> | <mark style="background-color:yellow;">0.0</mark> |
| YYY    | 15                                              | 1.0                                               |
| ZZZ    | 0                                               | 0.0                                               |
{% endtab %}
{% endtabs %}



In addition to the above, there are a number of other methods that may be used for Statistical Masking. Methods discussed in the “Statistical Policy Working Paper 22 (Second version, 2005), Report on Statistical Disclosure Limitation Methodology” include the following for tables of counts or frequencies and for magnitude data.

Tables of Counts or Frequencies

* Sampling as a Statistical Disclosure Limitation Method
* Defining Sensitive Cells
  * Special Rules
  * The Threshold Rule
* Protecting Sensitive Cells After Tabulation
  * Suppression
  * Random Rounding
  * Controlled Rounding
  * Controlled Tabular Adjustment
* Protecting Sensitive Cells Before Tabulation

Tables of Magnitude Data

* Defining Sensitive Cells – Linear Sensitivity Rules
* Protecting Sensitive Cells After Tabulation
* Protecting Sensitive Cells Before Tabulation

***

\[1] Ohio Department of Public Health.  “Data Methodology for Public Health Practice.” [http://www.odh.ohio.gov/\~/media/ODH/ASSETS/Files/data%20statistics/standards/methodological%20standards/disclimit.ashx](http://www.odh.ohio.gov/~/media/ODH/ASSETS/Files/data%20statistics/standards/methodological%20standards/disclimit.ashx).

\[2] Washington State Department of Health. "Guidelines for Working with Small Numbers." N.p., 15 October 2012.  Retrieved from [http://www.doh.wa.gov/Portals/1/Documents/5500/SmallNumbers.pdf](http://www.doh.wa.gov/Portals/1/Documents/5500/SmallNumbers.pdf).  &#x20;

\[3] Colorado Department of Public Health and Environment. “Guidelines for Working with Small Numbers.”  Retrieved from [http://www.cohid.dphe.state.co.us/smnumguidelines.html](http://www.cohid.dphe.state.co.us/smnumguidelines.html)&#x20;
