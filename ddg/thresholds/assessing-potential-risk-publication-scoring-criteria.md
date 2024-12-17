# Assessing Potential Risk – Publication Scoring Criteria

The Publication Scoring Criteria is provided as an example of a method that meets the requirements of Step 3 in the Data Assessment for Public Release Procedure. It is a tool to assess and quantify potential risk for re-identification of de-identified data based on three identification risks: size of potential population, variable specificity, and the impact of re-identification. The Publication Scoring Criteria is used to assess the need to suppress small cells less than 11 as a result of a small numerator (less than 11), small denominator (less than 20,001), or both small numerator and small denominator. That is why the Publication Scoring Criteria takes into account both numerator (e.g., Events) and denominator (e.g., Geography) variables. &#x20;

The Publication Scoring Criteria is based on a framework that was used by the Illinois Department of Public Health, Illinois Center for Health Statistics when CalHHS Data Deidentification Guidelines V1.0 was first prepared in 2016. Various other methods have been used to assess risk and the presence of sensitive or small cells. Public health has a long history of public provision of data and many methods have been used. Further discussion of other methods used to assess tables for sensitive or small cells is found in Section 6.4.

This section provides a more detailed review of the criteria that make up the Publication Scoring Criteria.

***

## Publication Scoring Criteria

### Events

Table 1: Events Scoring

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>1000+ events in a specified population</td><td>+2</td></tr><tr><td>100-999 events</td><td>+3</td></tr><tr><td>11-99 events</td><td>+5</td></tr><tr><td>&#x3C;11 events</td><td>+7</td></tr></tbody></table>

The Events score represents a score for the numerator. The Events category will be scored based on the smallest cell size in the table.&#x20;

The lowest value for the Events variable (<11 events) which has the highest score (+7) was chosen to be consistent with the Numerator Condition. The Publication Scoring Criteria is used when the Numerator-Denominator Condition is not met.  Therefore, when the Numerator Condition is not met with respect to the Events variable, a high score is given.

### Generalized Scoring for Personal Characteristics

Scores for all personal characteristics (e.g., age, race/ethnicity, language spoken) have been determined based on thresholds derived from the statewide population sizes as below and the CalHHS DDG V1.0\[1] age range scores.   \[A1]&#x20;

Table 2: Generalized Scoring Criteria Based on Statewide Population

<table><thead><tr><th>Population Size</th><th width="100">Score</th></tr></thead><tbody><tr><td>Population >4,000,000</td><td>+1</td></tr><tr><td>Population 300,001 – 4,000,000</td><td>+2</td></tr><tr><td>Population 100,001 – 300,000</td><td>+3</td></tr><tr><td>Population 20,001 – 100,000</td><td>+5</td></tr><tr><td>Population ≤20,000</td><td>+7</td></tr></tbody></table>

&#x20;

### Age Range

Table 3: Age Range Scoring

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>>29-year age range</td><td>+1</td></tr><tr><td>11-29 year age range</td><td>+2</td></tr><tr><td>6-10 year age range</td><td>+3</td></tr><tr><td>3-5 year age range</td><td>+5</td></tr><tr><td>1-2 year age range</td><td>+7</td></tr></tbody></table>

The last four categories of Age Range scores in the above table are prepared based on the 2020 Census population counts and Table 2.

Since general fertility rates and sexually transmitted infection rates are often reported for the female population of childbearing age using the 30-year age range for 15-44 years old and the approximate population size for 30-year age range is 4 million. Therefore, to incorporate these populations, an additional category with a score of +1 for age ranges greater than 29 years has been included which also reflects the lower identification risk for very large age ranges.

On the other side, age ranges receive a higher score for smaller ranges of years and smaller corresponding population sizes due to an increased risk for identification.

The smallest statewide populations for contiguous ranges of ages under 100 years, as reported for the 2020 Census in table below, were used to establish these thresholds. Note that the smallest population is always associated with the oldest age range and are given a score of 7 due to increased variable specificity. These are used to establish standard scoring criteria.&#x20;

Table 4: Lowest Populations for Age Ranges

| Age Range | Lowest Population Age Range | Lowest Population\[2] |
| --------- | --------------------------- | --------------------- |
| 1-year    | 99 years                    | 6,708                 |
| 2-year    | 98-99 years                 | 16,163                |
| 3-year    | 97-99 years                 | 28,974                |
| 5-year    | 95-99 years                 | 69,636                |
| 6-year    | 94-99 years                 | 98,643                |
| 10-year   | 90-99 years                 | 286,307               |
| 11-year   | 89-99 years                 | 355,657               |
| 29-year   | 71-99 years                 | 3,675,749             |
| 30-year   | 70-99 years                 | 4,035,466             |

Be aware that other restrictions may apply when reporting age ranges, such as only reporting ages 90 and older as a single category for HIPAA Safe Harbor. Of note, the HIPAA Safe Harbor method specifically identifies the following as an identifier: “All elements of dates (except year) for dates that are directly related to an individual, including birth date, admission date, discharge date, death date, and all ages over 89 and all elements of dates (including year) indicative of such age, except that such ages and elements may be aggregated into a single category of age 90 or older.” Although dates are included in the Safe Harbor list, age (<90 years old) is not. The risk score to age ranges reflects the two components of the scoring criteria: size of the potential population and the variable specificity.   &#x20;

### Race Group and Ethnicity

#### Table 5: Race or Race/Ethnicity Combined

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>White, Asian, Black or African American, Hispanic or Latino, Middle Eastern or North African</td><td>+2</td></tr><tr><td>White, Asian, Black or African American, Hispanic or Latino, Middle Eastern or North African, American Indian or Alaska Native, Native Hawaiian or Other Pacific Islander, Mixed</td><td>+3</td></tr></tbody></table>

#### Table 6: Detailed Race or Race/Ethnicity Combined

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td><p>Detailed Ethnicity with Population >4,000,000</p><p><em>e.g., Mexican</em></p></td><td>+1</td></tr><tr><td><p> Detailed Race with Population 300,001 – 4,000,000</p><p><em>e</em>.<em>g., Chinese, Filipino, German, Asian Indian, Italian, Korean, Salvadoran, Guatemalan</em></p></td><td>+2</td></tr><tr><td><p>Detailed Race with Population 100,001 – 300,000</p><p><em>e.g., Japanese, Armenian, Iranian, Aztec, Portuguese, Taiwanese, Hmong, Puerto Rican, Peruvian</em></p></td><td>+3</td></tr><tr><td><p>Detailed Race with Population 20,001 – 100,000</p><p><em>e.g., Cambodian, Dutch, Pakistani, Egyptian, Thai, Maya, Afghan, Nigerian, Indonesian, Fijian, Native Hawaiian, Jamaican, Cuban, Colombian, Argentinean</em></p></td><td>+5</td></tr><tr><td><p>Detailed Race with Population ≤20,000</p><p><em>e.g., Tongan, Chamorro, Bangladeshi, Sri Lankan, Brazilian, Mixtec, Kenyan, Zapotec, Malaysian, Belizean, Chumash, Sudanese, Pomo, Inca, Pipil</em></p></td><td>+7</td></tr></tbody></table>

#### Table 7: Ethnicity Scoring

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>Hispanic or Latino - yes or no</td><td>+1</td></tr></tbody></table>

#### Table 8: Detailed Ethnicity Scoring

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td><p>Detailed Ethnicity with Population >4,000,000</p><p><em>e.g., Mexican</em></p></td><td>+1</td></tr><tr><td><p>Detailed Ethnicity with Population 300,001 – 4,000,000</p><p><em>e.g., Salvadoran, Guatemalan, Central American, South American</em></p></td><td>+2</td></tr><tr><td><p>Detailed Ethnicity with Population 100,001 – 300,000</p><p><em>e.g., Puerto Rican, Spaniard, Peruvian, Nicaraguan, Honduran</em></p></td><td>+3</td></tr><tr><td><p>Detailed Ethnicity with Population 20,001 – 100,000</p><p><em>e.g., Cuban, Colombian, Argentinean, Dominican, Panamanian</em></p></td><td>+5</td></tr><tr><td><p>Detailed Ethnicity with Population ≤20,000</p><p><em>e.g., Bolivian, Uruguayan, Paraguayan</em></p></td><td>+7</td></tr></tbody></table>

&#x20;

Race and Ethnicity are collected in several different ways on the different state and federal data collection tools. At the federal level, starting in 1997, Office of Management and Budget required federal agencies to use a minimum of five race categories:\[3]

* White
* Black or African American
* American Indian or Alaska Native
* Asian
* Native Hawaiian or Other Pacific Islander

The 1997 OMB guidance required a separate question on Ethnicity which asked whether individuals are Hispanic or Latino.  The 2020 Census asked if individuals were of Hispanic, Latino, or Spanish origin, and additional specific detail for ethnicity was requested. The US Census Bureau often reports this information as Hispanic or Latino origin and Hispanic origin interchangeably.

#### Table 9: California Population by Race Group based on the 2020 Census

<table><thead><tr><th width="550">Race Group</th><th>Population[4]</th></tr></thead><tbody><tr><td>White alone</td><td>16,296,122</td></tr><tr><td>Black or African American alone</td><td>2,237,044</td></tr><tr><td>American Indian and Alaska Native alone</td><td>631,016</td></tr><tr><td>Asian alone</td><td>6,085,947</td></tr><tr><td>Native Hawaiian and Other Pacific Islander alone</td><td>157,263</td></tr><tr><td>Some Other Race alone</td><td>8,370,596</td></tr><tr><td>Two or more races</td><td>5,760,235</td></tr></tbody></table>

#### Table 10: California Population by Ethnicity or Race/Ethnicity based on the 2020 Census

| Ethnicity or Race/Ethnicity                                                | Population\[5] |
| -------------------------------------------------------------------------- | -------------- |
| Hispanic or Latino, any race                                               | 15,579,652     |
| Not Hispanic or Latino, any race                                           | 23,958,571     |
|   White alone, not Hispanic or Latino                                      | 13,714,587     |
|   Black or African American alone, not Hispanic or Latino                  | 2,119,286      |
|   American Indian and Alaska Native alone, not Hispanic or Latino          | 156,085        |
|   Asian alone, not Hispanic or Latino                                      | 5,978,795      |
|   Native Hawaiian and Other Pacific Islander alone, not Hispanic or Latino | 138,167        |
|   Some Other Race alone, not Hispanic or Latino                            | 223,929        |
|   Two or more races, not Hispanic or Latino                                | 1,627,722      |

&#x20;In 2024, the Office of Management and Budget approved an update\[6] to “Statistical Policy Directive No. 15: Standards for Maintaining, Collecting, and Presenting Federal Data on Race and Ethnicity”. The three major changes are:

* Addition of “Middle Eastern and North African” category. Previously these individuals were classified as White.
* Combination of race and ethnicity into a single question.
* Allowing individuals to select multiple racial groups that they identify with, rather than allowing only one selection.

The scores as described for population size (Table 2) were used to assess risk for race group, ethnicity, and race/ethnicity, based on comparable California populations as reported for the 2020 Census. Note that these risk scores are higher than the equivalent population numbers for location, as demographic traits such as age and race/ethnicity are publicly identifiable in a way that residence is not.

* Race group reported with the categories White, Asian, Black or African American, Middle Eastern and North African, and Hispanic or Latino have been assigned a +2 score. The smallest population is Middle Eastern and North African, estimated to be above 700,000 for California. The +2 score is consistent with the score in Table 2 for a statewide population of 300,001 to 4 million.
* Race group and race/ethnicity reporting that include the above categories plus American Indian and Pacific Islander are assessed a +3 score. The smallest (exclusionary) categories are Pacific Islander (157,263) and non-Hispanic/non-Latino Pacific Islander (138,167). The +3 score is consistent with the score in Table 2 for a statewide population of 100,001 to 300,000.

Scores for race, ethnicity and race/ethnicity are based on populations associated with these categories as reported for the 2020 Census, except for Middle Eastern and North African which was not recorded as a separate category but was allowed as a write-in response. If reported categories differ from the 2020 Census classification methodology, scores may need to be adjusted accordingly. For more information on these populations and categories see Appendix C.

While preparing the scores of race/ethnicity groups, it was not possible to consider the population size of counties since the distribution of each race/ethnicity group is different for each county in California. Please see the distribution of race/ethnicity groups within each county population in Appendix C. Thus, only statewide distributions of race/ethnicity groups within the California population are considered to score the race/ethnicity groups.

_Examples_

Three scenarios are presented below to help demonstrate how to use the race group and ethnicity scoring criteria for data that conforms to 1997-2024 OMB standards.

_First Scenario – Complete Cross-Tabulation between Race Group and Ethnicity_

Consider this table:

#### Table 11: First Scenario Example

| Race Group       | Hispanic | Non-Hispanic | _Any Hispanic response_ |
| ---------------- | -------- | ------------ | ----------------------- |
| Black            | 50       | 250          | _300_                   |
| White            | 200      | 1,000        | _1,200_                 |
| Asian            | 5        | 95           | _100_                   |
| _Any race group_ | _255_    | _1,345_      | _1,600_                 |

With this cross-tabulation, you would add both the Race score and Ethnicity score independently to the overall total for your scoring metric (i.e., greatest risk for re-identification). Note that you can replace “Ethnicity” with “Sex” and the principle still applies—you have a cross-tabulated table of Race and Sex.

_Second Scenario – Race and Ethnicity merged into exclusive categories_

Usually, the algorithm is that Ethnicity trumps Race when categorizing. This results in a Hispanic category, with the other categories effectively becoming “Non-Hispanic Race.” Accordingly, the above table would become:

#### Table 12: Second Scenario Example

| Mutually exclusive race/ethnicity | Number of Events |
| --------------------------------- | ---------------- |
| Non-Hispanic Black                | 250              |
| Non-Hispanic White                | 1,000            |
| Non-Hispanic Asian                | 95               |
| Hispanic                          | 255              |
| _Total_                           | _1,600_          |

&#x20;

The second scenario is when you would use the combined Race/Ethnicity score in the guidelines for your scoring metric.

_Third Scenario – No Interaction between Race and Ethnicity_

Without an interaction between Race and Ethnicity, this could be reported as follows:

#### Table 13: 3rd Scenario Example

| Race or Ethnicity            | Number of Events |
| ---------------------------- | ---------------- |
| Black, any Hispanic response | 300              |
| White, any Hispanic response | 1,200            |
| Asian, any Hispanic response | 100              |
| Hispanic, any race group     | 255              |

&#x20;Note that as displayed above, you cannot add up the categories to get a total population. For assigning a score, this is the same as reporting in two separate tables that are each scored independently:

#### Table 14: 3rd Scenario Example Continued

| Race Group | Number of Events |
| ---------- | ---------------- |
| Black      | 300              |
| White      | 1,200            |
| Asian      | 100              |
| _Total_    | _1,600_          |

#### Table 15: 3rd Scenario Example Continued

| Ethnicity    | Number of Events |
| ------------ | ---------------- |
| Hispanic     | 255              |
| Non-Hispanic | 1,345            |
| _Total_      | _1,600_          |

Also, you would need to run the scoring metric separately for your Race-only and Ethnicity-only datasets. Like the First Scenario, you can replace Ethnicity with Sex and it still makes sense—you now have two tables, one displaying Race and the other Sex, with no interaction between the two—which lessens the Small Cell Size problem.

### Risk Assessment for Detailed Race and Ethnicity Groups

The scores for detailed race, ethnicity, and race/ethnicity categories are harmonized with the scores for the minimum OMB categories and created based on Table 2.

Be aware that when reporting hierarchical data with multiple levels of the hierarchy, such as broad race/ethnicity alongside detailed race/ethnicity groups, that any complementary suppression algorithm will need to account for this dependent relationship between the values.

_Risk Assessment for Multi-Racial and Multi-Ethnic Populations_

Both OMB SPD 15 and California Government Code Section 8310.9 recommend providing the ability for individuals to “select all that apply” in order to capture multi-racial and multi-ethnic identities accurately. Data display would then aggregate all responses where a specific choice is selected.

* For example, the previous “exclusionary” approach would only count an individual as “Black” if “Black” was the only race selected. If another race group was also selected, that individual would be labeled as “Multi-race.”
* In the new "inclusionary" approach, all responses where “Black” was selected would be included in the “Black” category, regardless of another racial or ethnic choice was selected as well.

Statistically, this “inclusionary” approach would increase both numerator and denominator values for specific racial/ethnic groups and subgroups. Because groups would no longer be exclusionary of one another, it would also prevent the back-calculation of suppressed cells by subtracting non-suppressed cells from the total. Both these factors result in decreased re-identification risk. Therefore, no additional risk score is needed for an “inclusive” approach when displaying data on specific race/ethnicity groups and subgroups.

When identifying the score for a variable, use the highest scoring criteria. For example, if a table had age groups of 0 to 11 years (+2), 12 to 14 years (+5), and 15 to 18 years (+5) then the score for the Age Range variable would be +5 because the smallest age range is 12 to 14, which is an age range of three years. Similarly, if a table had race groups of Chinese (+2), Japanese (+3), Cambodian (+5), and Malaysian (+7) then the score for the Detailed Race Group variable would be +7 because it is the highest score for the reported groups.

### Language Spoken

#### Table 16: Language Spoken Scoring

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>English, Spanish, Other Language</td><td>+1</td></tr><tr><td><p>Detailed Language with Population 300,001 - 4,000,000</p><p><em>e.g., Chinese, Tagalog, Vietnamese, Korean</em></p></td><td>+2</td></tr><tr><td><p>Detailed Language with Population 100,001 - 300,000</p><p><em>e.g., Persian, Hindi, Arabic, Russian, Japanese, French</em></p></td><td>+3</td></tr><tr><td><p>Detailed Language with Population 20,001 - 100,000</p><p><em>e.g., German, Portuguese, Hmong, Hebrew, Bengali, Polish</em></p></td><td>+5</td></tr><tr><td><p>Detailed Language with Population ≤20,000</p><p><em>e.g., Haitian, Navajo</em></p></td><td>+7</td></tr></tbody></table>

Language spoken is captured in a variety of data systems to support individuals in receiving services in the language they speak. Language Spoken is not collected as part of the decennial Census, so the following estimates of language spoken at home are used to assess the population sizes of various languages. These estimates of language spoken are taken from the 2017-2021 5-year American Community Survey (ACS). These Statewide population estimates of language spoken along with Table 2 are used to determine the groupings for the scoring above.&#x20;

#### Table 17: California Population Estimates by Language Spoken

<table><thead><tr><th width="298">Language Spoken at Home for the Population 5 years and older</th><th>California Estimate</th><th>Margin of Error</th></tr></thead><tbody><tr><td>Total:</td><td>37,105,018</td><td>±669</td></tr><tr><td>    Speak only English</td><td>20,833,290</td><td>±49,117</td></tr><tr><td>    Spanish:</td><td>10,514,821</td><td>±34,689</td></tr><tr><td>    Chinese (incl. Mandarin, Cantonese):</td><td>1,259,668</td><td>±13,770</td></tr><tr><td>    Tagalog (incl. Filipino):</td><td>780,024</td><td>±10,075</td></tr><tr><td>    Vietnamese:</td><td>556,398</td><td>±8,380</td></tr><tr><td>    Korean:</td><td>358,018</td><td>±7,365</td></tr><tr><td>    Persian (incl. Farsi, Dari):</td><td>211,089</td><td>±6,309</td></tr><tr><td>    Hindi:</td><td>203,238</td><td>±6,535</td></tr><tr><td>    Arabic:</td><td>198,914</td><td>±7,807</td></tr><tr><td>    Armenian:</td><td>195,413</td><td>±5,581</td></tr><tr><td>    Russian:</td><td>170,508</td><td>±4,817</td></tr><tr><td>    Punjabi:</td><td>142,450</td><td>±6,035</td></tr><tr><td>    Japanese:</td><td>136,009</td><td>±4,890</td></tr><tr><td>    French (incl. Cajun):</td><td>126,338</td><td>±4,041</td></tr><tr><td>    Ilocano, Samoan, Hawaiian, or other Austronesian languages (aggregated group)</td><td>120,223</td><td>±4,014</td></tr><tr><td>    German:</td><td>93,471</td><td>±2,737</td></tr><tr><td>    Portuguese:</td><td>91,042</td><td>±3,852</td></tr><tr><td>    Thai, Lao, or other Tai-Kadai languages (aggregated group)</td><td>75,646</td><td>±3,518</td></tr><tr><td>    Other Indo-European languages (aggregated group)</td><td>75,233</td><td>±3,511</td></tr><tr><td>    Hmong:</td><td>74,317</td><td>±3,670</td></tr><tr><td>    Telugu:</td><td>67,956</td><td>±3,101</td></tr><tr><td>    Khmer:</td><td>67,756</td><td>±3,552</td></tr><tr><td>    Other languages of Asia (aggregated group)</td><td>65,969</td><td>±3,512</td></tr><tr><td>    Amharic, Somali, or other Afro-Asiatic languages (aggregated group)</td><td>63,318</td><td>±3,433</td></tr><tr><td>    Tamil:</td><td>60,594</td><td>±2,885</td></tr><tr><td>    Nepali, Marathi, or other Indic languages (aggregated group)</td><td>58,552</td><td>±2,832</td></tr><tr><td>    Urdu:</td><td>54,569</td><td>±2,938</td></tr><tr><td>    Italian:</td><td>53,954</td><td>±2,128</td></tr><tr><td>    Gujarati:</td><td>51,662</td><td>±2,772</td></tr><tr><td>    Hebrew:</td><td>44,540</td><td>±2,542</td></tr><tr><td>    Ukrainian or other Slavic languages (aggregated group)</td><td>41,606</td><td>±2,630</td></tr><tr><td>    Malayalam, Kannada, or other Dravidian languages (aggregated group)</td><td>37,709</td><td>±2,672</td></tr><tr><td>    Yoruba, Twi, Igbo, or other languages of Western Africa (aggregated group)</td><td>34,305</td><td>±2,830</td></tr><tr><td>    Bengali:</td><td>30,223</td><td>±2,043</td></tr><tr><td>    Yiddish, Pennsylvania Dutch or other West Germanic languages (aggregated group)</td><td>26,359</td><td>±1,870</td></tr><tr><td>    Polish:</td><td>21,304</td><td>±1,639</td></tr><tr><td>    Serbo-Croatian:</td><td>20,022</td><td>±1,470</td></tr><tr><td>    Greek:</td><td>19,783</td><td>±1,576</td></tr><tr><td>    Swahili or other languages of Central, Eastern, and Southern Africa (aggregated group)</td><td>16,547</td><td>±1,558</td></tr><tr><td>    Haitian:</td><td>7,878</td><td>±1,071</td></tr><tr><td>    Other Native languages of North America (aggregated group)</td><td>5,841</td><td>±713</td></tr><tr><td>    Navajo:</td><td>1,043</td><td>±305</td></tr><tr><td>    Other and unspecified languages:</td><td>37,418</td><td>±2,389</td></tr></tbody></table>

&#x20;

Based on the above numbers, the majority of individuals speak English or Spanish. Therefore if the table includes “English”, “Spanish”, and “Other Language” as the categories for “Language Spoken”, then the score is +1 which is comparable to reporting Hispanic or Latino Ethnicity as a “Yes or No”.&#x20;

As noted for Race and Ethnicity demographics, language spoken demographics may vary significantly based on geography as well as based on particular conditions. So although the scoring criteria presents a guideline for assessing risk, the population frequencies for the specific geography and/or condition should also be taken into account.&#x20;

If more specificity for Language Spoken is being requested with respect to reporting on the other languages in the table above, the request will need to be reviewed on a case-by-case basis. The additional review is necessary given the variability of language spoken by different populations or geographies and the consideration for potential increased risk of identification.&#x20;

### Sexual Orientation and Gender Identity

There are no census estimates for Sexual Orientation and Gender Identity (SOGI). Instead, we have based our risk scores on the California Health Interview Survey (CHIS) population estimates, as CHIS is the largest California survey and has publicly reproducible results via [AskCHIS](https://ask.chis.ucla.edu/ask/SitePages/AskChisLogin.aspx) and harmonized with the risk scores assigned to the age and race/ethnicity category population thresholds. AskCHIS 2021 population estimates for SOGI are as follows (Gender Identity population estimate is from pooled years 2019-2021 as per CHIS recommendations):

* Gay/lesbian: 1.2 mil
* Bisexual: 1.5 mil
* Asexual: 400K
* Transgender or non-conforming: 279K

Based on the risk scores for age and race/ethnicity, Sexual Orientation data aggregated to the above CHIS categories would be assigned a +2 score as the smallest group (Asexual) falls within the "300,001 – 4 million" risk category. Gender Identity data aggregated to the above CHIS categories would be assigned a +3 score as "Transgender or non-confirming" falls within the "100,001 – 300,000" risk category.&#x20;

There are no estimates for more granular categories such as genderqueer and two-spirit. A +5 risk score was assigned based on the “Other Variable” category for 5-9 groups in the DDG.

The option for a variable limited to "Male or Female" has been kept for datasets that are limited to these options, or in cases where other categories aren't displayed due to confidentiality concerns. The risk score remains at +1 as both populations are greater than 4 million.

#### Table 18: Sex, Sexual Orientation, and Gender Identity Scoring

<table><thead><tr><th>Variable</th><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>Sex</td><td>Male or Female</td><td>+1</td></tr><tr><td>Sexual Orientation</td><td>Straight, Gay or Lesbian, Bisexual, Asexual</td><td>+2</td></tr><tr><td>Gender Identity</td><td>Man/Male, Woman/Female, Transgender or Non-Binary</td><td>+3</td></tr><tr><td>Gender Identity</td><td>Man/Male, Woman/Female, disaggregation of Transgender/Non-Binary category into more specific identities (e.g. Genderqueer, Two-Spirit, etc.)</td><td>+5</td></tr></tbody></table>

### Sex Assigned At Birth

"Sex Assigned At Birth" is a variable which is defined at [USCDI website](https://www.healthit.gov/isa/united-states-core-data-interoperability-uscdi)\[A3]  and that is distinct from Gender Identity and Sexual Orientation. [California Statute](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=HSC\&sectionNum=103426.) specifies that individuals have the right to change their birth certificate to specify male, female, or non-binary. The annual number of non-binary births has generally been below 11 for the entire state, making this variable at high risk for re-identification. For this reason, "Sex Assigned At Birth" has not been assigned a risk score. Instead, the Vital Statistics Branch combines "non-binary" with "unknown" to help mask the data.

_Distinction Between Sexual Orientation and Men Having Sex With Men (MSM) Activity_

While the CDC definition of sexual orientation includes an implicit behavior in "sexual attraction", this guidance defines Sexual Orientation and Gender Identity as identifiable factors (akin to race, ethnicity, and age) to distinguish them from sexual behaviors such as "Men having Sex with Men" (MSM). This is because the former may be a publicly identifiable trait and thus a re-identification risk, while the latter is, generally, not an identification risk. For example, some individuals may engage in MSM activity but not identify as gay, while others may identify as gay but practice abstinence.&#x20;

We acknowledge that the boundary between the two is not clear cut and programs will need to assess on a case-by-case basis as to whether MSM should be considered a risk factor for redisclosure. An example of this is [an incident](https://www.pillarcatholic.com/p/pillar-investigates-usccb-gen-sec) cited in [NIST SP 800-188](https://www.nist.gov/privacy-framework/nist-sp-800-188) where geographic location from app data was used to infer MSM activity for an individual:

> _According to commercially available records of app signal data obtained by The Pillar, a mobile device correlated to Burrill emitted app data signals from the location-based hookup app Grindr on a near-daily basis during parts of 2018, 2019, and 2020 — at both his USCCB office and his USCCB-owned residence, as well as during USCCB meetings and events in other cities._

This incident demonstrates the possibility that if an individual is known to use an app or frequent certain locations, one may infer MSM activity for the individual. This makes it potentially usable as a quasi-identifier to re-identify an individual. As mentioned by Abowd and Hawes in [21st Century Statistical Disclosure Limitation: Motivations and Challenges](https://arxiv.org/abs/2303.00845v1):

> _The release of any statistic derived from a confidential source always carries some incremental risk of disclosure of identifiable information._

### Intersex

AB 1163 added the requirement to collect intersex status in Government Code 8310.8 when collecting “ancestry or ethnic origins of Californians.” There are no California estimates of the intersex population but the national estimate is 1.7% of the total population. That would be a population of \~595K in California, which would be a +2 risk score as per the risk score table. The question can be asked as part of the Sex question or as its own question.

Table 19: Intersex Scoring

<table><thead><tr><th>Variable</th><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td>Intersex (asked as separate question)</td><td>Yes or No</td><td>+2</td></tr><tr><td>Intersex (combined with Sex question)</td><td>Male, Female, Intersex</td><td>+2</td></tr></tbody></table>

### Immigration Status

#### Table 20: Immigration Status Scoring

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>U.S. Citizen, Foreign Born (can be characterized into Naturalized Citizen, Noncitizen)</td><td>+1</td></tr><tr><td>U.S. Citizen, Foreign Born (can be characterized into Naturalized Citizen, Noncitizen), Lawful Permanent Resident</td><td>+2</td></tr><tr><td>Detailed Immigration Status with Disaggregation of Noncitizen Statuses (Lawful Permanent Resident, Nonimmigrant), with Disaggregation of Nonimmigrants (Temporary Workers, Students, Exchange Visitors, and Refugees and Asylees)</td><td>+7</td></tr><tr><td>Undocumented Immigrants – Refer to High-Risk Populations</td><td>N/A</td></tr></tbody></table>

In this version of DDG, immigration status is added as a new variable because immigration status in the summarized healthcare data may increase the re-identification risk of individuals due to increased granularity of the aggregated data. This additional information has potential to make it easier to narrow down and identify individuals, especially if the dataset is combined with other publicly available sources. Immigration status often intersects with other demographic factors such as age, gender, ethnicity, and location. When combined, these factors can create a more distinct profile for certain individuals.

The U.S. Census Bureau\[7] collects citizenship data via the American Community Survey (ACS) and categorizes the population as either “U.S. citizen” or “foreign born”. The “foreign born” population is then categorized further as “natural citizen” or “noncitizen”. The noncitizen status is disaggregated into the following statuses:

* Lawful Permanent Resident
* Nonimmigrant
  * Temporary Workers
  * Students
  * Exchange Visitors
  * Refugees and Asylees
* Undocumented Immigrant

Based on reporting by the U.S. Census Bureau and the U.S. Department of Homeland Security, population estimates for different characteristics of immigration status are as below.\[8] \[9] However, the population estimates for undocumented immigrants are based on population statistics reported by the Center for Migration Studies.\[10]

Table 21: Population Estimates related to Immigration Status

| Immigration Status         | Population Estimate  |
| -------------------------- | -------------------- |
| U.S. Citizen               | \~28.8 million\[11]  |
| Foreign Born               | \~10.5 million30     |
| Naturalized Citizens       | \~5.7 million30      |
| Noncitizens                | \~4.7 million30      |
| Lawful Permanent Residents | \~2.2 million\[12]   |
| Nonimmigrants              | \~560,000\[13]       |
| Temporary Workers          | \~300,00032          |
| Students                   | \~210,00032          |
| Exchange Visitors          | \~50,00032           |
| Refugees/Asylees           | <10,000\[14]         |
| Undocumented Immigrants    | 2,251,756\[15]\[A4]  |

&#x20;

Immigration Status scores are prepared based on the U.S. Census Bureau 30 population data collected on U.S. citizen and foreign-born populations (including naturalized citizens and noncitizens). Disaggregated immigration status scores are prepared based on the Department of Homeland Security Population Estimates for lawful permanent residents 31 and nonimmigrants 32 including temporary workers, students, exchange visitors, and refugees/asylees. The scores are then harmonized with the risk scores assigned to the latest population size thresholds, Table 2. Immigration statuses receive a higher score for disaggregated statuses and smaller corresponding population size due to an increased risk for identification.

### Undocumented Immigrants&#x20;

Undocumented Immigrants have a higher risk and higher stakes for identification than most individuals. Undocumented immigrants (roughly 2.3 million in California in 2019 34) are individuals who reside in the country illegally or otherwise without permission and face deportation at any time. Any information released about undocumented immigrants, including protected health information (PHI), could be used in deportation proceedings.\[16] Medical providers and state agencies can alleviate this by having stringent privacy policies in place and communicating to the immigrant community that these safeguards apply to everyone, including undocumented immigrants. Likewise, data related to undocumented immigrants should be carefully assessed for possible re-identification risk before any data is released. Please see High-Risk Populations tab for the guidance in how to de-identify data related to Undocumented Immigrants.

### Expected Payer

Expected Payer is a factor that may be a proxy for other identifiers. For example, employment-based payers may provide information about a person’s job status. Other types of payers, such as Medicaid, may provide information about a person’s income. There is demographic data that indicates populations by income level in the public domain as published by the U.S. Census Bureau,\[17] as well as public information related to various jobs and employment status through labor agencies.\[18] \[19] Given the opportunities to use information about the payer in combination with other public information, this variable is given a risk score.

The risk is scored as below given the size of the population in the various categories.\[20] \[21]

#### Table 22: Expected Payer Scoring

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>Medi-Cal, Medicare, Private Insurance</td><td>+1</td></tr><tr><td><p>Medi-Cal, Medicare, Private Insurance</p><p>Self-Pay/Uninsured</p></td><td>+2</td></tr></tbody></table>

It's important to be aware of the potential risks associated with this data and to ensure its security and protection. For instance, eligibility for benefits in the Medi-Cal program may be determined based on income, property, and assets. Similarly, self-pay data, often associated with the uninsured, can also indicate low income, highlighting the need for data security. There are approximately 14 million Californians enrolled in the Medi-Cal program in 2024 and more than 6 million California residents had Medicare coverage. The Medi-Cal or Medicare category has been assigned a +1 DDG score.  There are approximately 5.5 million patients captured in the HCAI Health Care Payments Database who have private insurance, and thus assigned as +1 score.  The uninsured population, who we presume would self-pay seems to be less than 4 million (2,752,067 based on the 2022 5-year American Community Survey estimate for California \[22]), has been assigned a +2 score.

### Time – Reporting Period

#### Table 23: Time – Reporting Period Scoring

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>5 years aggregated</td><td>-5</td></tr><tr><td>2-4 years aggregated</td><td>-3</td></tr><tr><td>1 year (e.g., 2001)</td><td>0</td></tr><tr><td>Bi-Annual</td><td>+3</td></tr><tr><td>Quarterly</td><td>+4</td></tr><tr><td>Monthly</td><td>+5</td></tr></tbody></table>

Many reports are published based on the calendar year. However, the combination of years of data is an excellent way to provide increased aggregation in a way that allows for more specificity elsewhere, such as county identifiers. Inversely, the smaller the time period in the data, the closer the time period comes to approximating a date. Thus monthly reported data has a high score of +5.

Of note, the HIPAA Safe Harbor method list includes “All elements of dates (except year) for dates that are directly related to an individual, including birth date, admission date, discharge date, death date, and all ages over 89 and all elements of dates (including year) indicative of such age, except that such ages and elements may be aggregated into a single category of age 90 or older.” This is a potential identifier when in combination with other information. This potential as an identifier influences the higher scores in the Publication Scoring Criteria as the time period for aggregation gets smaller.&#x20;

The “0” value for this variable is set at one year as this is the criteria for Safe Harbor under the HIPAA de-identification standard.&#x20;

### Geography

#### Table 24: Residence Geography Scoring

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>State or geography with population >2,000,000</td><td>-5</td></tr><tr><td>Population 1,000,001 - 2,000,000</td><td>-3</td></tr><tr><td>Population 560,001 - 1,000,000</td><td>-1</td></tr><tr><td>Population 250,000 - 560,000</td><td>0</td></tr><tr><td>Population 100,000 - 250,000</td><td>+1</td></tr><tr><td>Population 50,001 - 100,000</td><td>+3</td></tr><tr><td>Population 20,001 - 50,000</td><td>+4</td></tr><tr><td>Population ≤ 20,000</td><td>+5</td></tr><tr><td>Population ≤ 4,000</td><td>+7</td></tr></tbody></table>

#### Table 25: Service Geography Scoring

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>State or geography with population >2,000,000</td><td>-5</td></tr><tr><td>Population 1,000,001 - 2,000,000</td><td>-4</td></tr><tr><td>Population 560,001 - 1,000,000</td><td>-3</td></tr><tr><td>Population 250,000 - 560,000</td><td>-1</td></tr><tr><td>Population of reporting region 20,001 - 250,000</td><td>0</td></tr><tr><td>Population of reporting region ≤20,000</td><td>+1</td></tr><tr><td>Address (Street and ZIP)</td><td>+3</td></tr><tr><td>Address in rural [23] area</td><td>+5</td></tr><tr><td>Address in frontier [24], [25] area</td><td>+7</td></tr></tbody></table>



{% hint style="info" %}
If the geography of the reporting is based on the residence of the individual, use the “Residence Geography”. If the geography of the reporting is based on the location of service, use the “Service Geography”.
{% endhint %}

The Geography score, while it may or may not represent the denominator of the table, does provide a reference to the base population about which the reporting is occurring. This will often be reflected in the title of the table if a statewide table.  Otherwise the geography may be represented in the rows or columns. There are two different scoring sets based on whether the geography reporting is based on the residence of the individual to which the information applies or to the service location.&#x20;

The scores are higher for geography related to residence address because so much information is publicly available about individuals and their address of residence. For large populations greater than 560,000, which is equivalent to the size of a state, there is a negative score because the size of the denominator masks the individual. The number 560,000 was chosen as a cut-off because this is the size of the smallest state (Wyoming). We chose to use the cut-off at the smallest state’s population because state level reporting is not listed as one of the 18 identifiers in the HIPAA Safe Harbor method.&#x20;

The scores for the service geography are lower because clients can generally come from diverse locations for services. Although people often seek services or have health conditions close to their homes, they may also travel extensive distances. Reviewers do need to make sure that there are not constraints associated with services that would mean the service geography and resident geography are the same. For example, if a program publishes service utilization by county and the county services can only be used by county residents, then the service utilization by county is also the county of residence. Scoring should be based on the criteria that result in the highest score and, thus, the highest risk.

There are smaller areas within counties where the population is significantly lower than the overall county population. One example of this is census tracts, which are small, relatively stable statistical subdivisions of a county or an equivalent statistical entity. These tracts can be updated by local participants before each decennial census through the Census Bureau’s Participant Statistical Areas Program (PSAP). Census tracts\[26] typically cover contiguous areas, but their size can vary widely based on population density. The boundaries of these tracts are designed to remain unchanged over time, allowing for consistent statistical comparisons from one census to the next. Generally, census tracts have populations ranging from 1,200 to 8,000 people, with an optimum size of population around 4,000. To account for the higher re-identification risk associated with smaller populations, a score of +7 is assigned when the population size is 4,000 or fewer in the residential area.

Service Geography includes a level of detail that is identified as “Address (Street and ZIP).” This deals with reporting by provider (hospital, clinic, provider office, etc.) Provider addresses are public information and are public at the street address level. A given provider will tend to have a standard catchment area or the geographic boundaries from which most patients come from. This information is published by the Department of Health Care Access and Information (previously the Office of Statewide Health Planning and Development \[A5] -OSHPD) \[27] f\[A6] or hospitals. While this addresses where most patients or clients come from, patients or clients may also come from outside the catchment area. For that reason, this does not score as high as the more detailed geography under Residence Geography.

However, addresses associated with rural and frontier areas have a higher re-identification risk due to lower population density per square mile and isolation of communities in these areas. Thus, higher scores are assigned for Provider’s addresses in rural and frontier areas.\[28] \[29]

### Variable Interactions

#### Table 26: Variable Interactions Scoring

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>Only Events (minimum of 5), Time, and Geography (Residence or Service)</td><td>-5</td></tr><tr><td>Only Events (minimum of 3), Time, and Geography (Residence or Service)</td><td>-3</td></tr><tr><td>Only Events (no minimum), Time, and Geography (Residence or Service)</td><td>0</td></tr><tr><td>Events, Time, and Geography (Residence or Service) + 1 variable</td><td>+1</td></tr><tr><td>Events, Time, and Geography (Residence or Service) + 2 variables</td><td>+2</td></tr><tr><td>Events, Time, and Geography (Residence or Service) + 3 variables</td><td>+4</td></tr></tbody></table>

These criteria specifically address the interaction of the variables in a given data presentation and requires the analyst to identify dependent as opposed to independent variables. These criteria are used with respect to dependent variables. This is demonstrated in the two tables below.

#### _Illustration A: Dependent Variables_

In this example the Event (counts of Disease A) is shown for Males who are also 0-17 years old or Males who are also 18-25 years old. In this case Sex and Age are dependent because the stratification for each variable is stacked. This commonly occurs in pivot tables.

#### Table 27: Illustration A: Dependent Variables Example

<table data-full-width="false"><thead><tr><th>Counts of disease A by year</th><th>Males and 0-17 years old</th><th>Males and 18-25 years old</th><th>Females and 0-17 years old</th><th>Females and 18-25 years old</th></tr></thead><tbody><tr><td>Year 1</td><td>6</td><td>10</td><td>5</td><td>8</td></tr><tr><td>Year 2</td><td>8</td><td>14</td><td>3</td><td>20</td></tr></tbody></table>

_Illustration B: Independent Variables_

In this example the Event (counts of Disease A) is for Males or Females which is shown side by side to a table with ages 0-17 years old or 18-25 years old. In this case Sex and Age are independent because the stratification for each variable is not stacked. Although the two variables Sex and Age are shown in the same table, they are presented independently of each other. While you can compile the data in Example B from Example A, the reverse is not true.&#x20;

#### Table 28: Illustration B: Independent Variables Example

| Counts of disease A by year | Males | Females | 0-17 years old | 18-25 years old |
| --------------------------- | ----- | ------- | -------------- | --------------- |
| Year 1                      | 16    | 13      | 11             | 18              |
| Year 2                      | 22    | 23      | 11             | 34              |

These criteria are structured to have less impact if personal characteristics outside of time and geography are excluded and more impact if multiple personal characteristics are included. This provides for a subtraction of points if the only variables presented are the events (numerator), time and geography and an addition of points for including more variables in a given presentation. With respect to the subtraction of points, the score is based on the minimum value for the Events variable. For example, if the smallest value for the Events is 5 or more, then the score would be -5. However, if the smallest value for the Events is 2, then the score would be 0.&#x20;

The minimum value for Events of 3 _(Only Events (minimum of 3), Time, and Geography (Residence or Service)_ is used as a threshold to address concern for pre-existing knowledge by users about individuals. For example, if an entity knows who one person is with disease A and the count for Events is “1” or “2”, then the entity could identify the person they know of or the person they know of plus information about the other person. The use of a minimum of 3 does not protect against two entities colluding to determine a third person.\[30]  For this reason, the threshold of 5 for Events is also given. The threshold of 5 is frequently used in public health reporting regarding various events.

In contrast, if additional demographic variables are added, then the risk increases significantly. For example, for Events, Time and Geography (Residence or Service) with three additional variables, a table would show how many individuals are female by age group by race for a given time period and geography. This allows for a more detailed comparison to census data and assessment of the number of individuals with a particular set of characteristics.\[31] For this reason, additional points are added because of the inclusion of multiple dependent variables.

### Other Variables

Variables not specified in the Publication Scoring Criteria can be released only after an additional, case-by-case review by the department’s Statistical De-Identification Expert or Statistical De-Identification Supervisor Expert. We suggest that this review considers population size-based scores if population size of the characteristics of a variable is present, or otherwise scores based on number of groups or categories.

1\. Other Variable Scores Based on Population Size

#### Table 29: Generalized Scoring Criteria based on Statewide Population&#x20;

| Population Size                 | Score |
| ------------------------------- | ----- |
| Population >4,000,000           | +1    |
| Population 300,001 – 4,000,000  | +2    |
| Population 100,001 – 300,000    | +3    |
| Population 20,001 – 100,000     | +5    |
| Population ≤20,000              | +7    |

The above table shows scoring criteria for population size in general and can be used to score veteran status and educational attainment. Examples follow below of how these variables can be considered by using data at the Census American Community Survey.\[32]

### Veteran Status

For the California statewide population estimate of 1,467,025 listed below for the adult civilian veteran population, a score of +2 would be assigned from the Table 2 based on Statewide Population (Population 300,001 – 4,000,000).

#### Table 30: Veteran Status recorded from the 2021 American Community Survey

| Veteran Status for Population 18 years and over  | California Estimate | Margin of Error |
| ------------------------------------------------ | ------------------- | --------------- |
| Civilian veterans                                | 1,467,026           | ±9,913          |

Note that even though there is an implicit age associated with veteran status, this information is incorporated into the population estimate used for the score. Therefore, an additional score modifier for the age should not be applied.

Other aspects of the subpopulation should be considered when assessing risk. For example, more than 90 percent of the veteran population is male.\[33] Therefore, reporting of veterans by sex would have more risk than the scores for sex based on the statewide population due to the small number of female veterans.

### Educational Attainment

Similarly, the population estimates\[34] in the table below can be used to score Education Attainment Status by using Table 2.&#x20;

Table 31: Educational Attainment Status recorded from the 2021 American Community Survey

| Educational Attainment for Population 25 years and over  | California Estimate  | Margin of Error  |
| -------------------------------------------------------- | -------------------- | ---------------- |
| Less than 9th grade, no high school diploma              | 2,342,364            | ±15,809          |
| 9th to 12th grade, no high school diploma                | 1,893,671            | ±12,037          |
| High school graduate (includes equivalency)              | 5,477,154            | ±28,244          |
| Some college, no degree                                  | 5,496,578            | ±16,961          |
| Associate degree                                         | 2,135,865            | ±13,333          |
| Bachelor degree                                          | 5,855,383            | ±22,797          |
| Graduate or professional degree                          | 3,596,055            | ±25,828          |
| High school graduate or higher                           | 22,561,035           | ±20,560          |
| Bachelor's degree or higher                              | 9,451,438            | ±40,058          |



For example, the smallest California population with a recorded educational attainment level is 2,135,865 for Associate degree. Thus, a score of +2 (Population 300,001 – 4,000,000) from the Table 2 would be assigned. Whereas the score would be +1 (Population >4,000,000) if educational attainment is combined from the table into two categories as follows:

* No college (sum of rows 1-3): 9,713,189 (2,342,364 + 1,893,671 + 5,477,154)
* At least some college (sum of rows 4-7): 17,083,881 (5,496,578 + 2,135,865 + 5,855,383 + 3,596,055)

2\. Other Variable Scores Based on Number of Groups or Categories

#### Table 32: Other Variable Scoring Based on Number of Groups or Categories

| Number of Groups or Categories   | Score   |
| -------------------------------- | ------- |
| <5 groups or categories          | +3      |
| 5-9 groups                       | +5      |
| 10+ groups                       | +7      |

If population size is not available for a variable, then score the variable based on number of groups or categories as well as the characteristics of the variables. &#x20;

For example, legal class groupings associated with a patient’s commitment to the state hospital system are an example of groups or categories. At the highest level, patients can be categorized into two groups: forensic commitment or civil commitments. At a more granular level, patients can be categorized into specific legal classes such defendants found incompetent to stand trial, parolees diagnosed with mental health disorders, individuals found to be not guilty by reason of insanity, mentally ill prisoners transferred from prison to a state hospital for mental health care, individuals committed to the state hospital system as sexually violent predators, or patients civilly committed to a state hospital as described in the Lanterman-Petris-Short Act.

#### Table 33: Example Scoring for Legal Class Groupings

<table><thead><tr><th>Groups or Categories </th><th width="100">Score</th></tr></thead><tbody><tr><td><p>2 Groups </p><p>Forensic commitments </p><p>Civil commitments </p></td><td>+3 </td></tr><tr><td><p>6 Groups </p><p>Incompetent to stand trial  </p><p>Offenders with a mental health disorder </p><p>Not guilty by reason of insanity </p><p>Mentally ill prisoners  </p><p>Sexually violent predators </p><p>Lanterman-Petris-Short Act commitments </p></td><td>+5 </td></tr></tbody></table>

Some additional examples can be found in “Data with more Specificity” section 6.3. Along with number of groups or categories, consider the specificity of the groups or categories, that is, whether the variable represents an aggregation (e.g., Diagnosis Related Groups) or a specific item (e.g., ICD-10 Code).

Also consider the availability of the variable to the public when also associated with other information, particularly the availability of variables that are personal characteristics.

How publicly identifiable the trait in question is should also be considered. For example, unreconstructed cleft palate is a physically identifiable trait. Dyslexia is a condition that, while not physically identifiable, may be something an individual mentions they have and should also be considered a publicly identifiable trait.

***

### Footnotes:

\[1] California Health and Human Services, Data De-Identification Guidelines (DDG), version 1.0, September 23, 2016, https://chhsa.dsh.ca.gov/wp-content/uploads/2021/04/CHHS-Data\_Deidentification\_Guidelines-V1.0-092316.pdf

\[2] U.S. Census Bureau, "SEX BY SINGLE-YEAR AGE," 2020. Decennial Census, DEC Demographic and Housing Characteristics, Table PCT12, 2020, accessed on October 6, 2023, https://data.census.gov/table/DECENNIALDHC2020.PCT12?g=040XX00US06.&#x20;

\[3] U.S. Office of Management and Budget. Revisions to the Standards for the Classification of Federal Data on Race and Ethnicity, https://www.federalregister.gov/d/97-28653.

\[4] U.S. Census Bureau, "RACE," 2020. Decennial Census, DEC Redistricting Data (PL 94-171), Table P1, 2020, accessed on October 6, 2023, https://data.census.gov/table/DECENNIALPL2020.P1?g=040XX00US06,06$0500000.

\[5] U.S. Census Bureau, "HISPANIC OR LATINO, AND NOT HISPANIC OR LATINO BY RACE," 2020. Decennial Census, DEC Redistricting Data (PL 94-171), Table P2, 2020, accessed on October 6, 2023, https://data.census.gov/table/DECENNIALPL2020.P2?g=040XX00US06,06$0500000.

\[6] U.S. Office of Management and Budget. Initial Proposals For Updating OMB's Race and Ethnicity Statistical Standards, https://www.federalregister.gov/d/2023-01635.

\[7] U.S. Census Bureau, " SELECTED CHARACTERISTICS OF THE NATIVE AND FOREIGN-BORN POPULATIONS," 2022. American Community Survey, ACS 5-Year Estimates Subject Tables, Table S0501, 2022, accessed on December 11, 2023, https://data.census.gov/table/ACSST5Y2022.S0501?q=S0501

\[8] U.S. Department of Homeland Security. (2021, June). Population Estimates of Nonimmigrants Residing in the United States: Fiscal Years 2017-2019. dhs.gov. https://www.dhs.gov/sites/default/files/publications/immigration-statistics/Pop\_Estimate/NI/ni\_population\_estimates\_fiscal\_years\_2017\_-\_2019v2.pdf.&#x20;

\[9] U.S. Department of Homeland Security. (2022, March). Fiscal Year 2020 Refugees and Asylees Annual Flow Report. Dhs.gov. https://www.dhs.gov/sites/default/files/2022-03/22\_0308\_plcy\_refugees\_and\_asylees\_fy2020\_1.pdf.&#x20;

\[10] 2019 estimate from Estimates of Undocumented and Eligible-to-Naturalize Populations by State, Center for Migration Studies, http://data.cmsny.org/state.html.

\[11] U.S. Census Bureau, " SELECTED CHARACTERISTICS OF THE NATIVE AND FOREIGN-BORN POPULATIONS," 2022. American Community Survey, ACS 5-Year Estimates Subject Tables, Table S0501, 2022, accessed on December 11, 2023, https://data.census.gov/table/ACSST5Y2022.S0501?q=S0501

\[12] U.S. Department of Homeland Security. (2022, September). September 2022 Population estimates of the Lawful Permanent Resident Population in the United States and the Subpopulation Eligible to Naturalize: 2022. dhs.gov https://www.dhs.gov/sites/default/files/2022-10/2022\_0920\_plcy\_lawful\_permenent\_resident\_population\_estimate\_2022\_0.pdf.

\[13] U.S. Department of Homeland Security. (2022, September). September 2022 Population estimates of the Lawful Permanent Resident Population in the United States and the Subpopulation Eligible to Naturalize: 2022. dhs.gov https://www.dhs.gov/sites/default/files/2022-10/2022\_0920\_plcy\_lawful\_permenent\_resident\_population\_estimate\_2022\_0.pdf.

\[14] U.S. Department of Homeland Security. (2022, March). Fiscal Year 2020 Refugees and Asylees Annual Flow Report. Dhs.gov. https://www.dhs.gov/sites/default/files/2022-03/22\_0308\_plcy\_refugees\_and\_asylees\_fy2020\_1.pdf.&#x20;

\[15] 2019 estimate from Estimates of Undocumented and Eligible-to-Naturalize Populations by State, Center for Migration Studies, http://data.cmsny.org/state.html.&#x20;

\[16] AMA J Ethics. 2019;21(1):E32-37. doi: 10.1001/amajethics.2019.32.&#x20;

\[17] U.S. Census Bureau, Census Datasets on income topics,[ (census.gov)](https://www.census.gov/data/datasets.html)

\[18] U.S. Bureau of Labor Statistics, [Occupation Finder: Occupational Outlook Handbook (bls.gov)](https://www.bls.gov/ooh/occupation-finder.htm)

\[19] California Employment Development Department, California Open Data Portal datasets, [https://data.ca.gov/organization/california-employment-development-department](https://data.ca.gov/organization/california-employment-development-department) &#x20;

\[20] Department of Health Care Information and Access, Health Care Payments Data Snapshot “Data Overview – Count of Individuals by Payer Type”, [https://hcai.ca.gov/visualizations/healthcare-payments-data-hpd-snapshot/](https://hcai.ca.gov/visualizations/healthcare-payments-data-hpd-snapshot/)

\[21] Department of Health Care Information and Access, Report to the Legislature “Program Report: Health Care Payments Data Program”, May 2024, [https://hcai.ca.gov/wp-content/uploads/2024/04/HPD-Report-to-the-Legislature-March-2024-1.pdf](https://hcai.ca.gov/wp-content/uploads/2024/04/HPD-Report-to-the-Legislature-March-2024-1.pdf)

\[22] U.S. Census Bureau, “Selected Characteristics of the Uninsured in the United States”, American Community Survey, _ACS 5-Year Estimates Subject Tables, Table S2702,_ 2022 [https://data.census.gov/table/ACSST5Y2022.S2702?g=040XX00US06](https://data.census.gov/table/ACSST5Y2022.S2702?g=040XX00US06) (Accessed October 10, 2024)

\[23] U.S. Census Bureau, 2020 Census ”Urban and Rural” Classifications, [https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html](https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html)

\[24] Rural Health Information Hub, ”Health and Healthcare in Frontier Areas”,  https://www.ruralhealthinfo.org/topics/frontier#definition

\[25] U.S. Department of Agriculture Economic Research Service, ”Frontier and Remote Area Codes”, https://www.ers.usda.gov/data-products/frontier-and-remote-area-codes.aspx

\[26] [https://www.census.gov/programs-surveys/geography/about/glossary.html#:\~:text=Census%20Tract,-Census%20Tracts%20are\&text=The%20primary%20purpose%20of%20census,optimum%20size%20of%204%2C000%20people.](https://www.census.gov/programs-surveys/geography/about/glossary.html)

\[27] Department of Health Care Access and Information , Patient Origin & Market Share Reports, Retrieved from [http://www.oshpd.ca.gov/HID/Products/PatDischargeData/PivotTables/PatOrginMkt/default.asp](http://www.oshpd.ca.gov/HID/Products/PatDischargeData/PivotTables/PatOrginMkt/default.asp) on January 22, 2016.

\[28] Medical Service Study Areas 2010, Retrieved from: [https://gis.data.ca.gov/maps/fe411f2d74494b89a74ab181b22fc8a1/about on April 2](https://gis.data.ca.gov/maps/fe411f2d74494b89a74ab181b22fc8a1/about%20on%20April%202), 2024.

\[29] United States Census Bureau “About Geographic Areas: Urban and Rural”, Retrieved from: [https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html on April 2](https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html%20on%20April%202), 2024.

\[30] NORC, “NORC Recommendations for California Department of Health Care Services (DHCS) Data De-Identification Guidelines (DDG),” January 8, 2016.

\[31] NORC, “Case Study: The Disclosure Risk Implications of Small Cells Combined with Multiple Tables or External Data,” January 8, 2016.

\[32] U.S. Census Bureau, "Selected Social Characteristics in the United States," 2021. American Community Survey, ACS 5-Year Estimates Data Profiles, Table DP02, 2021, accessed on December 5, 2023, https://data.census.gov/table/ACSDP5Y2021.DP02?g=040XX00US06.&#x20;

\[33]  U.S. Department of Veterans Affairs, “VetPop2020 State Estimates 2000 to 2020,” updated on April 6, 2023, https://www.data.va.gov/dataset/VetPop2020-State-Estimates-2000-to-2020/fkjq-z6m8.&#x20;

\[34] U.S. Census Bureau, 2017-2021 American Community Survey 5-Year Estimates, “2021 Educational Attainment, California Estimates, Population 25 Years and Over”, Table S1501: https://data.census.gov/table/ACSST5Y2021.S1501?q=S1501\&g=040XX00US06\&y=2021

***
