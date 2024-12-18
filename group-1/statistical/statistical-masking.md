# Statistical Masking

If Step 3 determined that the data set has a risk that small numerators or small denominators may result in conditions that put individuals at risk of being re-identified, then the data set must be assessed to determine the need for statistical masking of those small values and complimentary values. In performing the statistical masking, the data producer must consider what level of analysis may be sacrificed in order to produce a table with lower risk. Initial considerations for statistical masking are described below. For additional methods related to statistical masking, please see Section 6.5.

### Reduce Table Dimensions

If there are more dimensions present in the table than necessary for the vast majority of analysis, the data producer should consider reducing the number of dimensions in a single table and producing multiple tables, each with a subset of the dimensions in the table that resulted in small cells. For example, if there are six dimensions of interest for study, but a table that crosses all six dimensions produces a large number of small cells, the data producer could consider producing several tables each of which crosses four dimensions. This is especially effective if there are very few analytic questions requiring a cross-section of all six variables.

### Reduce Granularity of Variable(s), aka Recoding or Aggregation

An alternative approach to addressing small cells in a table is to reduce the number of levels of a particular dimension. This is especially useful for dimensions with a large number of levels that can be easily aggregated to fewer levels and maintain much of their utility. Geographic variables such as state or county can often be recoded into regional variables that still serve the analytic needs of the data user. It is also the only table restructuring option for tables with only two or three dimensions which have limited opportunities for table dimension reduction.

It should be noted that these actions can be used alone or in tandem to reduce or completely eliminate small cells within a table.

### Cell Suppression and Complementary Cell Suppression

There will be cases where not all small cells can be eliminated by reducing the granularity of dimensions or the number of dimensions present in a table. In these cases, it will be necessary to suppress small cells and perform complementary suppression to ensure that precise values of small cells cannot be calculated using the values of unsuppressed cells and marginal values. In the simplest case, this means ensuring that each column and row of a two-dimensional table has at least two suppressions. This ensures that the precise values of the suppressed cells cannot be calculated. Complementary suppressions are often selected using one of the methods listed below.

1. The ‘analytically least interesting’ level of a particular dimension. This is often, ‘other’, or ‘I don’t know’.
2. The smallest cell available for complementary suppression. This is based on minimizing the ‘information loss’.
3. The cell most similar to the cell needing complementary suppression, such as adjacent age groups. This can produce complementary suppression that may be easier to interpret.

### Masking a Three Category Variable (e.g. Intersex Status)

A special situation may occur when complementary cell suppression must be applied to a variable with three categories. This occurs when “Intersex” is an option for the Sex variable (Male, Female, Intersex), but can occur in any situation where a variable has two large categories and one small category (for example, if the options for Gender Identity included Man, Woman, and Nonbinary).

As an example:

<table><thead><tr><th data-type="number">Male</th><th data-type="number">Female</th><th data-type="number">Intersex</th><th data-type="number">Total</th></tr></thead><tbody><tr><td>545</td><td>545</td><td>10</td><td>1100</td></tr></tbody></table>

&#x20;

If the DDG risk assessment concludes that counts less than 11 must be suppressed, then complementary suppression must be applied to either the Male or Female categories so that the Intersex count of 10 cannot be backcalculated. The problem is that suppression of either category would deprive the public of vital information and hence be publicly unacceptable. Other masking methods (such as combining Intersex with either the Male or Female categories; or reassigning the Intersex individuals to both categories equally) will likely also be unacceptable as they would be viewed as erasure of the Intersex identity.

In these instances, the recommendation is to not show counts at all, butonly percentages, rounded to the nearest whole percent. Such “rounding error” will effectively mask the smallest category without requiring complementary suppression.

Here are the raw percentages for the above example:

| Male    | Female  |        |      |
| ------- | ------- | ------ | ---- |
| 49.545% | 49.545% | 0.009% | 100% |

Here are the rounded percentages:

| Male | Female | Intersex | Total |
| ---- | ------ | -------- | ----- |
| 50%  | 50%    | <1%      | 100%  |

&#x20;Once the percentages are rounded, one cannot back-calculate to obtain the Intersex count, even if one knows the total is 1100. One would only know that the count is less than 11, which is the same knowledge as with standard suppression practices. It is recommended that a footnote is provided to explain why this was done, for example:

> “To protect individual privacy, counts are not provided for this table and percentages have been rounded to the nearest whole number. Due to rounding, totals for all categories may not add up to 100%.”

A few other points regarding this method:

* Ensure that counts for the variable are not provided anywhere else in the document and are not available in the public domain. In the above example, one needs to make sure one cannot obtain a total count of 545 males and females elsewhere (for example, in a table that cross-tabulates sex by race).
* This method is only effective if the total number of individuals is 1100 or above. Below this threshold, one can back-calculate counts of less than 11 even when percentages are rounded.
* This method is only needed for a three-category variable. In the above example, if Intersex were presented as a separate “yes/no” variable and no cross-tabulation with Sex was provided, then complementary suppression would not be required, and this issue would not arise.
