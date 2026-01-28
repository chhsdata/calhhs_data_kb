---
icon: chart-scatter
---

# 4. Statistical De-Identification

The DDG describes the Data Assessment for Public Release Procedure shown in Figure 5, to be used by departments in the CalHHS to assess data for public release. This Section 4 describes specific actions that may be taken for each step in the procedure with additional supporting information provided in Sections 5, 6 and 16. These steps are intended to assist departments in assuring that data is de-identified for purposes of public release that meet the requirements of the California IPA to prevent the disclosure of personal information.

The Data Assessment for Public Release Procedure includes the following steps:

1. Review the data to determine if it includes personal characteristics, directly or indirectly, that can be tied back to an individual;
2. If there is concern for personal characteristics, then assess the data for small numerators or denominators;
3. If there is concern for small numerators or denominators, assess potential risk of data release;
4. If there is potential risk identified, assess the need to apply statistical masking methods to de-identify the data;
5. Following statistical de-identification, the data release is reviewed by legal if indicated in departmental procedures; and,
6. After statistical de-identification, the data is reviewed and approved for release based on program and policy criteria pursuant to departmental procedures.

The steps above are represented in a step-wise process shown in Figure 5. Each step is described in further detail in Section 4.1 through 4.6.

Data summaries that originate from data which includes personal identifiers must be de-identified before release to the public. Additionally, data summaries about conditions experienced by individuals must be adequately de-identified to prevent re-identification of individuals represented by the summarized data. Various statistical methods are available to de-identify data statistically.&#x20;

Summarized data may be reviewed in the context of the numerator and the denominator for the given presentation. The numerator represents the number of events being reported while the denominator represents the population from which the numerator is taken. For example, if it is reported that there are 50 cases of diabetes in California then the numerator would be the number of cases (50) and the denominator would be the number of people in California that could have diabetes (more than 38 million people since diabetes can occur at any age or sex). While the numerator is relatively straight-forward to identify, the denominator can be difficult. Data summaries are frequently presented in tables in which numerators and denominators may be identified.&#x20;

The numerator is typically the value in each table cell. However, the denominator can be difficult to identify given the various ways in which tables are prepared. Two examples of tables, Figure 3 and Figure 4, show the numerators and denominators in sample tables.

#### Figure 3: Illustration of Numerators and Denominators in a Table

<figure><img src="../../.gitbook/assets/f3-numerators-and-denominators-in-a-table.png" alt=""><figcaption><p>Figure 3. Illustration of Numerators and Denominators in a Table</p></figcaption></figure>

Figure 3 shows an example table with the numerator highlighted. The Cells in the table are the boxes with values in them, as opposed to the row and column headings. The row headings are 2021 and 2022. The column headings are Year, Number of Female Medi-Cal Members, and Number of Male Medi-Cal Members. In Figure 3, “8,625,954” is the value in a table cell and represents a numerator. The sum of the row for year 2022 (8,625,954 + 7,654,306 = 16,280,260) represents a denominator. In this context, the denominator may represent row totals, column totals or the total occurrences in the dataset released. Data in Figure 3 comes from the [“Medi-Cal Long-Term Services and Supports Data” dashboard on the CalHHS Open Data Portal](#user-content-fn-1)[^1].

Figure 4 shows another type of table that contains rates. In this case, the numerator is the number of Salmonellosis cases for a sample of California Local Health Jurisdictions in 2021. The table also includes the rate of Salmonellosis for these jurisdictions. In order to calculate the rate, the population size of each jurisdiction is required, but is not shown directly in this table. The population denominator is an important element for data de-identification.

#### Figure 4: Illustration of Numerators and Denominators in a Table of Rates

<figure><img src="../../.gitbook/assets/f4-numerators-denominators-table-of-rates.png" alt=""><figcaption><p>Figure 4: Illustration of Numerators and Denominators in a Table of Rates</p></figcaption></figure>

***

#### Figure 5: Data Assessment for Public Release Procedure

<figure><img src="../../.gitbook/assets/f5-assessment-for-public-release.png" alt=""><figcaption><p>Figure 5: Data Assessment for Public Release Procedure</p></figcaption></figure>

[^1]: Data was extracted from the _Medi-Cal Long-Term Services and Supports Data_ files for 2021 and 2022, CalHHS Open Data Portal: [https://data.chhs.ca.gov/dataset/long-term-services-and-supports](https://data.chhs.ca.gov/dataset/long-term-services-and-supports)
