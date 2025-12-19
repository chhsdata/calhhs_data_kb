---
layout:
  width: wide
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# 16. Appendix D: Justification of Thresholds Identified

## 16.1 Establishing Minimum Numerator and Denominator <a href="#toc196116314" id="toc196116314"></a>

The DDG workgroup reviewed the published literature including information from other states and from the federal government. There was a great deal of variation in the numerical values chosen for the Numerator Condition. While the Centers for Disease Control and Prevention (CDC) WONDER database suppresses cells with numerators less than 10, the National Environmental Public Health Tracking Network suppresses cells that are greater than 0 but less than 6. Examples range from 3 to 40 with many being 10 to 15. The Centers for Medicare and Medicaid Services (CMS) uses a small cell policy of suppressing values derived from fewer than 11 individuals. As stated in a 2014 publication associated with a data release of Medicare Provider Data, “to protect the privacy of Medicare beneficiaries, any aggregated records which are derived from 10 or fewer beneficiaries are excluded from the Physician and Other Supplier PUF \[public use file].” \[1] Of note, CMS only uses a Numerator Condition.

Just as there is no consistent value for the Numerator Condition, neither is there a consistent value for the Denominator Condition. Some examples include:

* National Center for Health Statistics (public micro-data) – 250,000
* National Environmental Health Tracking Network – 100,000
* Maine Integrated Youth Health Survey – 5,000

In establishing a minimum denominator to protect confidentiality, the DDG workgroup began by looking at the risk associated with providing geography associated with record level data. As noted in the “Guidance Regarding Methods for De-Identification of Protected HIPAA Privacy Rule”, published November 2012 by the U.S. Department of Health & Human Services, Office for Civil Rights there is varying risk based on the level of zip code and how the zip code is combined with other variables. It has been estimated that the combination of a patient’s Date of Birth, Sex, and 5-Digit ZIP Code is unique for over 50% of residents in the United States.<sup>\[2],\[3]</sup> This means that over half of U.S. residents could be uniquely described just with these three data elements. In contrast, it has been estimated that the combination of Year of Birth, Sex, and 3-Digit ZIP Code is unique for approximately 0.04% of residents in the United States.\[4] For this reason, the HIPAA Safe Harbor rule specifies that the 3-Digit ZIP Code can be provided at the record level if the 3-Digit ZIP Code has a minimum of 20,000 people. By aggregating data for a given 3-Digit ZIP Code, the potential for identifying a unique individual is less than 0.04%.  By combining with the Numerator Condition, the risk becomes less than 0.04% because there will be a minimum of 11 individuals with a particular age and sex for the 3-Digit ZIP Code. Additionally, most tables will provide additional levels of aggregation further reducing risk. This reduction of risk is discussed further with respect to the Publication Scoring Criteria.&#x20;

A minimum denominator of 20,000 was chosen as part of the numerator-denominator condition to leverage the risk assessment cited above.&#x20;

The Numerator-Denominator Condition serves as an initial screening to assess potential risk for a dataset. If this condition is met, additional analysis is not necessary.  If the condition is not met, then the analysis proceeds to Step 3.

## 16.2 Assessing Potential Risk – Publication Scoring Criteria <a href="#toc196116315" id="toc196116315"></a>

The Publication Scoring Criteria is provided as an example of a method that meets the requirements of Step 3 in the Data Assessment for Public Release Procedure. It is a tool to assess and quantify potential risk for re-identification of de-identified data based on three identification risks: size of potential population, variable specificity, and the impact of re-identification. The Publication Scoring Criteria is used to assess the need to suppress small cells less than 11 as a result of a small numerator (less than 11), small denominator (less than 20,001), or both small numerator and small denominator. That is why the Publication Scoring Criteria takes into account both numerator (e.g., Events) and denominator (e.g., Geography or Insurance Coverage variables).&#x20;

The Publication Scoring Criteria is based on a framework that was used by the Illinois Department of Public Health, Illinois Center for Health Statistics when CalHHS Data De-Identification Guidelines Edition 1.0 was first prepared in 2016. Various other methods have been used to assess risk and the presence of sensitive or small cells. Public health has a long history of public provision of data and many methods have been used. Further discussion of other methods used to assess tables for sensitive or small cells is found in Section 4.4.

This section provides a more detailed review of the criteria that make up the Publication Scoring Criteria.

### 16.2.1 Events

#### Table 1: Events Scoring

<table><thead><tr><th width="700.5999755859375" valign="middle">Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle">1000+ events in a specified population</td><td align="center" valign="middle">+2</td></tr><tr><td valign="middle">100-999 events</td><td align="center" valign="middle">+3</td></tr><tr><td valign="middle">11-99 events</td><td align="center" valign="middle">+5</td></tr><tr><td valign="middle">&#x3C;11 events</td><td align="center" valign="middle">+7</td></tr></tbody></table>

The Events score represents a score for the numerator. The Events category will be scored based on the smallest cell size in the table.&#x20;

The lowest value for the Events variable (<11 events) which has the highest score (+7) was chosen to be consistent with the Numerator Condition. The Publication Scoring Criteria is used when the Numerator-Denominator Condition is not met. Therefore, when the Numerator Condition is not met with respect to the Events variable, a high score is given.

### 16.2.2 Generalized Scoring for Personal Characteristics

Scores for all personal characteristics (e.g., age, race/ethnicity, language spoken) have been determined based on thresholds derived from the statewide population sizes as below and the CalHHS DDG Edition 1.0 \[5] age range scores. &#x20;

#### Table 2: Generalized Scoring Criteria Based on Statewide Population

<table><thead><tr><th width="700.6000366210938" valign="middle">Population Size</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle">Population >4,000,000</td><td align="center" valign="middle">+1</td></tr><tr><td valign="middle">Population 300,001 – 4,000,000</td><td align="center" valign="middle">+2</td></tr><tr><td valign="middle">Population 100,001 – 300,000</td><td align="center" valign="middle">+3</td></tr><tr><td valign="middle">Population 20,001 – 100,000</td><td align="center" valign="middle">+5</td></tr><tr><td valign="middle">Population ≤20,000</td><td align="center" valign="middle">+7</td></tr></tbody></table>

### 16.2.3 Age Range

#### Table 3: Age Range Scoring

<table><thead><tr><th width="700.6000366210938" valign="middle">Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle">>29-year age range</td><td align="center" valign="middle">+1</td></tr><tr><td valign="middle">11-29 year age range</td><td align="center" valign="middle">+2</td></tr><tr><td valign="middle">6-10 year age range</td><td align="center" valign="middle">+3</td></tr><tr><td valign="middle">3-5 year age range</td><td align="center" valign="middle">+5</td></tr><tr><td valign="middle">1-2 year age range</td><td align="center" valign="middle">+7</td></tr></tbody></table>

The last four categories of Age Range scores in the above table are prepared based on the 2020 Census population counts and Table 2.

General fertility rates and sexually transmitted infection rates are often reported for the female population of childbearing age using the 30-year age range for 15-44 years old and the approximate population size for the female 30-year age range is four million. Therefore, to incorporate these populations, an additional category with a score of +1 for age ranges greater than 29 years has been included which also reflects the lower identification risk for very large age ranges.

On the other side, age ranges receive a higher score for smaller ranges of years and smaller corresponding population sizes due to an increased risk for identification.

The smallest statewide populations for contiguous ranges of ages under 100 years, as reported for the 2020 Census in table below, were used to establish these thresholds. Note that the smallest population is always associated with the oldest age range and are given a score of seven (7) due to increased variable specificity. These are used to establish standard scoring criteria.&#x20;

#### Table 4: Lowest Populations for Age Ranges

<table><thead><tr><th width="312.8000183105469" align="center" valign="middle">Age Range</th><th width="422.79998779296875" align="center" valign="middle">Lowest Population Age Range</th><th align="center" valign="middle">Lowest Population[6]</th></tr></thead><tbody><tr><td align="center" valign="middle">1-year</td><td align="center" valign="middle">99 years</td><td align="center" valign="middle">6,708</td></tr><tr><td align="center" valign="middle">2-year</td><td align="center" valign="middle">98-99 years</td><td align="center" valign="middle">16,163</td></tr><tr><td align="center" valign="middle">3-year</td><td align="center" valign="middle">97-99 years</td><td align="center" valign="middle">28,974</td></tr><tr><td align="center" valign="middle">5-year</td><td align="center" valign="middle">95-99 years</td><td align="center" valign="middle">69,636</td></tr><tr><td align="center" valign="middle">6-year</td><td align="center" valign="middle">94-99 years</td><td align="center" valign="middle">98,643</td></tr><tr><td align="center" valign="middle">10-year</td><td align="center" valign="middle">90-99 years</td><td align="center" valign="middle">286,307</td></tr><tr><td align="center" valign="middle">11-year</td><td align="center" valign="middle">89-99 years</td><td align="center" valign="middle">355,657</td></tr><tr><td align="center" valign="middle">29-year</td><td align="center" valign="middle">71-99 years</td><td align="center" valign="middle">3,675,749</td></tr><tr><td align="center" valign="middle">30-year</td><td align="center" valign="middle">70-99 years</td><td align="center" valign="middle">4,035,466</td></tr></tbody></table>

Be aware that other restrictions may apply when reporting age ranges, such as only reporting ages 90 and older as a single category for HIPAA Safe Harbor. Of note, the HIPAA Safe Harbor method specifically identifies the following as an identifier: “All elements of dates (except year) for dates that are directly related to an individual, including birth date, admission date, discharge date, death date, and all ages over 89 and all elements of dates (including year) indicative of such age, except that such ages and elements may be aggregated into a single category of age 90 or older.” Although dates are included in the Safe Harbor list, age (<90 years old) is not. The risk score to age ranges reflects the two components of the scoring criteria: size of the potential population and the variable specificity.

### 16.2.4 Race Group and Ethnicity

#### Table 5: Race or Race/Ethnicity Combined

<table><thead><tr><th width="701.4000244140625" valign="top">Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="top">White, Asian, Black or African American, Hispanic or Latino, Middle Eastern or North African</td><td align="center" valign="middle">+2</td></tr><tr><td valign="top">White, Asian, Black or African American, Hispanic or Latino, Middle Eastern or North African, American Indian or Alaska Native, Native Hawaiian or Other Pacific Islander, Mixed</td><td align="center" valign="middle">+3</td></tr></tbody></table>

#### Table 6: Detailed Race or Race/Ethnicity Combined

<table><thead><tr><th width="700.6000366210938" valign="middle">Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle"><p>Detailed Race or Race/Ethnicity Combined with Population >4,000,000</p><p><em>e.g., Mexican</em></p></td><td align="center" valign="middle">+1</td></tr><tr><td valign="middle"><p> Detailed Race or Race/Ethnicity Combined with Population 300,001 – 4,000,000</p><p><em>e</em>.<em>g., Chinese, Filipino, German, Asian Indian, Italian, Korean, Salvadoran, Guatemalan</em></p></td><td align="center" valign="middle">+2</td></tr><tr><td valign="middle"><p>Detailed Race or Race/Ethnicity Combined with Population 100,001 – 300,000</p><p><em>e.g., Japanese, Armenian, Iranian, Aztec, Portuguese, Taiwanese, Hmong, Puerto Rican, Peruvian</em></p></td><td align="center" valign="middle">+3</td></tr><tr><td valign="middle"><p>Detailed Race or Race/Ethnicity Combined with Population 20,001 – 100,000</p><p><em>e.g., Cambodian, Dutch, Pakistani, Egyptian, Thai, Maya, Afghan, Nigerian, Indonesian, Fijian, Native Hawaiian, Jamaican, Cuban, Colombian, Argentinean</em></p></td><td align="center" valign="middle">+5</td></tr><tr><td valign="middle"><p>Detailed Race or Race/Ethnicity Combined with Population ≤20,000</p><p><em>e.g., Tongan, Chamorro, Bangladeshi, Sri Lankan, Brazilian, Mixtec, Kenyan, Zapotec, Malaysian, Belizean, Chumash, Sudanese, Pomo, Inca, Pipil</em></p></td><td align="center" valign="middle">+7</td></tr></tbody></table>

#### Table 7: Ethnicity Scoring

<table><thead><tr><th width="700.5999755859375"> Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td>Hispanic or Latino - yes or no</td><td align="center" valign="middle">+1</td></tr></tbody></table>

#### Table 8: Detailed Ethnicity Scoring

<table><thead><tr><th width="699.7999877929688"> Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td><p>Detailed Ethnicity with Population >4,000,000</p><p><em>e.g., Mexican</em></p></td><td align="center" valign="middle">+1</td></tr><tr><td><p>Detailed Ethnicity with Population 300,001 – 4,000,000</p><p><em>e.g., Salvadoran, Guatemalan, Central American, South American</em></p></td><td align="center" valign="middle">+2</td></tr><tr><td><p>Detailed Ethnicity with Population 100,001 – 300,000</p><p><em>e.g., Puerto Rican, Spaniard, Peruvian, Nicaraguan, Honduran</em></p></td><td align="center" valign="middle">+3</td></tr><tr><td><p>Detailed Ethnicity with Population 20,001 – 100,000</p><p><em>e.g., Cuban, Colombian, Argentinean, Dominican, Panamanian</em></p></td><td align="center" valign="middle">+5</td></tr><tr><td><p>Detailed Ethnicity with Population ≤20,000</p><p><em>e.g., Bolivian, Uruguayan, Paraguayan</em></p></td><td align="center" valign="middle">+7</td></tr></tbody></table>

Race and Ethnicity are collected in several different ways on the different state and federal data collection tools. At the federal level from 1997 to 2024 Office of Management and Budget required federal agencies to use a minimum of five race categories:\[7] &#x20;

* White,
* Black or African American,
* American Indian or Alaska Native,
* Asian, and
* Native Hawaiian or Other Pacific Islander.

The 1997 OMB guidance required a separate question on Ethnicity which asked whether individuals are Hispanic or Latino. The 2020 Census asked if individuals were of Hispanic, Latino, or Spanish origin, and additional specific detail for ethnicity was requested. The US Census Bureau often reports this information as Hispanic or Latino origin and Hispanic origin interchangeably.

#### Table 9: California Population by Race Group based on the 2020 Census

<table><thead><tr><th width="700.6000366210938" valign="middle">Race Group</th><th align="center" valign="middle">Population[8]</th></tr></thead><tbody><tr><td valign="middle">White alone</td><td align="center" valign="middle">16,296,122</td></tr><tr><td valign="middle">Black or African American alone</td><td align="center" valign="middle">2,237,044</td></tr><tr><td valign="middle">American Indian and Alaska Native alone</td><td align="center" valign="middle">631,016</td></tr><tr><td valign="middle">Asian alone</td><td align="center" valign="middle">6,085,947</td></tr><tr><td valign="middle">Native Hawaiian and Other Pacific Islander alone</td><td align="center" valign="middle">157,263</td></tr><tr><td valign="middle">Some Other Race alone</td><td align="center" valign="middle">8,370,596</td></tr><tr><td valign="middle">Two or more races</td><td align="center" valign="middle">5,760,235</td></tr></tbody></table>

#### Table 10: California Population by Ethnicity or Race/Ethnicity based on the 2020 Census

<table><thead><tr><th width="699.7999877929688" valign="middle">Ethnicity or Race/Ethnicity</th><th align="center" valign="middle">Population [9]</th></tr></thead><tbody><tr><td valign="middle">Hispanic or Latino, any race</td><td align="center" valign="middle">15,579,652</td></tr><tr><td valign="middle">Not Hispanic or Latino, any race</td><td align="center" valign="middle">23,958,571</td></tr><tr><td valign="middle">White alone, not Hispanic or Latino</td><td align="center" valign="middle">13,714,587</td></tr><tr><td valign="middle">Black or African American alone, not Hispanic or Latino</td><td align="center" valign="middle">2,119,286</td></tr><tr><td valign="middle">American Indian and Alaska Native alone, not Hispanic or Latino</td><td align="center" valign="middle">156,085</td></tr><tr><td valign="middle">Asian alone, not Hispanic or Latino</td><td align="center" valign="middle">5,978,795</td></tr><tr><td valign="middle">Native Hawaiian and Other Pacific Islander alone, not Hispanic or Latino</td><td align="center" valign="middle">138,167</td></tr><tr><td valign="middle">Some Other Race alone, not Hispanic or Latino</td><td align="center" valign="middle">223,929</td></tr><tr><td valign="middle">Two or more races, not Hispanic or Latino</td><td align="center" valign="middle">1,627,722</td></tr></tbody></table>

In 2024, the Office of Management and Budget approved an update\[10] to “Statistical Policy Directive No. 15: Standards for Maintaining, Collecting, and Presenting Federal Data on Race and Ethnicity”. The three major changes are:

* Addition of “Middle Eastern and North African” category. Previously these individuals were classified as White.
* Combination of race and ethnicity into a single question.
* Allowing individuals to select multiple racial groups that they identify with, rather than allowing only one selection.

The scores as described for population size (Table 2) were used to assess risk for race group, ethnicity, and race/ethnicity, based on comparable California populations as reported for the 2020 Census. Note that these risk scores are higher than the equivalent population numbers for location, as demographic traits such as age and race/ethnicity are publicly identifiable in a way that residence is not.

* Race group reported with the categories White, Asian, Black or African American, Middle Eastern and North African, and Hispanic or Latino have been assigned a +2 score. The smallest population is Middle Eastern and North African, estimated to be above 700,000 for California. The +2 score is consistent with the score in Table 2 for a statewide population of 300,001 to 4 million.
* Race group and race/ethnicity reporting that include the above categories plus American Indian and Pacific Islander are assessed a +3 score. The smallest (exclusionary) categories are Pacific Islander (157,263) and non-Hispanic/non-Latino Pacific Islander (138,167). The +3 score is consistent with the score in Table 2 for a statewide population of 100,001 to 300,000.

Scores for race, ethnicity and race/ethnicity are based on populations associated with these categories as reported for the 2020 Census, except for Middle Eastern and North African which was not recorded as a separate category but was allowed as a write-in response. If reported categories differ from the 2020 Census classification methodology, scores may need to be adjusted accordingly. For more information on these populations and categories see Appendix G.

While preparing the scores of race/ethnicity groups, it was not possible to consider the population size of counties since the distribution of each race/ethnicity group is different for each county in California. Please see the distribution of race/ethnicity groups within each county population in Appendix G. Thus, only statewide distributions of race/ethnicity groups within the California population are considered to score the race/ethnicity groups.

**Examples**

Three scenarios are presented below to help demonstrate how to use the race group and ethnicity scoring criteria for data that conforms to 1997-2024 OMB standards.

First Scenario – Complete Cross-Tabulation between Race Group and Ethnicity

Consider this table:

#### Table 11: First Scenario Example

<table><thead><tr><th valign="middle">Race Group</th><th align="center" valign="middle">Hispanic</th><th align="center" valign="middle">Non-Hispanic</th><th align="center" valign="middle">Any Hispanic response</th></tr></thead><tbody><tr><td valign="middle">Black</td><td align="center" valign="middle">50</td><td align="center" valign="middle">250</td><td align="center" valign="middle"><em>300</em></td></tr><tr><td valign="middle">White</td><td align="center" valign="middle">200</td><td align="center" valign="middle">1,000</td><td align="center" valign="middle"><em>1,200</em></td></tr><tr><td valign="middle">Asian</td><td align="center" valign="middle">5</td><td align="center" valign="middle">95</td><td align="center" valign="middle"><em>100</em></td></tr><tr><td valign="middle"><em>Any race group</em></td><td align="center" valign="middle"><em>255</em></td><td align="center" valign="middle"><em>1,345</em></td><td align="center" valign="middle"><em>1,600</em></td></tr></tbody></table>

With this cross-tabulation, you would add both the Race score and Ethnicity score independently to the overall total for your scoring metric (i.e., greatest risk for re-identification). Note that you can replace “Ethnicity” with “Sex” and the principle still applies—you have a cross-tabulated table of Race and Sex.

Second Scenario – Race and Ethnicity merged into exclusive categories

Usually, the algorithm is that Ethnicity trumps Race when categorizing. This results in a Hispanic category, with the other categories effectively becoming “Non-Hispanic Race.” Accordingly, the above table would become:

#### Table 12: Second Scenario Example

<table><thead><tr><th width="700.6000366210938" valign="middle">Mutually exclusive race/ethnicity</th><th align="center" valign="middle">Number of Events</th></tr></thead><tbody><tr><td valign="middle">Non-Hispanic Black</td><td align="center" valign="middle">250</td></tr><tr><td valign="middle">Non-Hispanic White</td><td align="center" valign="middle">1,000</td></tr><tr><td valign="middle">Non-Hispanic Asian</td><td align="center" valign="middle">95</td></tr><tr><td valign="middle">Hispanic</td><td align="center" valign="middle">255</td></tr><tr><td valign="middle"><em>Total</em></td><td align="center" valign="middle"><em>1,600</em></td></tr></tbody></table>

The second scenario is when you would use the combined Race/Ethnicity score in the guidelines for your scoring metric.

Third Scenario – No Interaction between Race and Ethnicity

Without an interaction between Race and Ethnicity, this could be reported as follows:

#### Table 13: Third Scenario Example

<table><thead><tr><th width="701.3999633789062" valign="middle">Race or Ethnicity</th><th align="center" valign="middle">Number of Events</th></tr></thead><tbody><tr><td valign="middle">Black, any Hispanic response</td><td align="center" valign="middle">300</td></tr><tr><td valign="middle">White, any Hispanic response</td><td align="center" valign="middle">1,200</td></tr><tr><td valign="middle">Asian, any Hispanic response</td><td align="center" valign="middle">100</td></tr><tr><td valign="middle">Hispanic, any race group</td><td align="center" valign="middle">255</td></tr></tbody></table>

Note that as displayed above, you cannot add up the categories to get a total population. For assigning a score, this is the same as reporting in two separate tables that are each scored independently:

#### Table 14: Third Scenario Example Continued

<table><thead><tr><th width="699.7999877929688" valign="middle">Race Group</th><th align="center" valign="middle">Number of Events</th></tr></thead><tbody><tr><td valign="middle">Black</td><td align="center" valign="middle">300</td></tr><tr><td valign="middle">White</td><td align="center" valign="middle">1,200</td></tr><tr><td valign="middle">Asian</td><td align="center" valign="middle">100</td></tr><tr><td valign="middle"><em>Total</em></td><td align="center" valign="middle"><em>1,600</em></td></tr></tbody></table>

#### Table 15: Third Scenario Example Continued

<table><thead><tr><th width="700.6000366210938" valign="middle">Ethnicity</th><th align="center" valign="middle">Number of Events</th></tr></thead><tbody><tr><td valign="middle">Hispanic</td><td align="center" valign="middle">255</td></tr><tr><td valign="middle">Non-Hispanic</td><td align="center" valign="middle">1,345</td></tr><tr><td valign="middle"><em>Total</em></td><td align="center" valign="middle"><em>1,600</em></td></tr></tbody></table>

Also, you would need to run the scoring metric separately for your Race-only and Ethnicity-only datasets. Like the First Scenario, you can replace Ethnicity with Sex and it still makes sense—you now have two tables, one displaying Race and the other Sex, with no interaction between the two—which lessens the Small Cell Size problem.

**Risk Assessment for Detailed Race and Ethnicity Groups**

The scores for detailed race, ethnicity, and race/ethnicity categories are harmonized with the scores for the minimum OMB categories and created based on Table 2.

Be aware that when reporting hierarchical data with multiple levels of the hierarchy, such as broad race/ethnicity alongside detailed race/ethnicity groups, that any complementary suppression algorithm will need to account for this dependent relationship between the values.

**Risk Assessment for Multi-Racial and Multi-Ethnic Populations**

Both OMB SPD 15 and California Government Code Section 8310.9 recommend providing the ability for individuals to “select all that apply” in order to capture multi-racial and multi-ethnic identities accurately. Data display would then aggregate all responses where a specific choice is selected.

* For example, the previous “exclusionary” approach would only count an individual as “Black” if “Black” was the only race selected. If another race group was also selected, that individual would be labeled as “Multi-race.”
* In the new "inclusionary" approach, all responses where “Black” was selected would be included in the “Black” category, regardless of whether another racial or ethnic choice was selected as well.

Statistically, this “inclusionary” approach would increase both numerator and denominator values for specific racial/ethnic groups and subgroups. Because groups would no longer be exclusionary of one another, it would also prevent the back-calculation of suppressed cells by subtracting non-suppressed cells from the total. Both these factors result in decreased re-identification risk. Therefore, no additional risk score is needed for an “inclusive” approach when displaying data on specific race/ethnicity groups and subgroups.

When identifying the score for a variable, use the highest scoring criteria. For example, if a table had age groups of 0 to 11 years (+2), 12 to 14 years (+5), and 15 to 18 years (+5) then the score for the Age Range variable would be +5 because the smallest age range is 12 to 14, which is an age range of three years. Similarly, if a table had race groups of Chinese (+2), Japanese (+3), Cambodian (+5), and Malaysian (+7) then the score for the Detailed Race Group variable would be +7 because it is the highest score for the reported groups.

### 16.2.5 Language Spoken

#### Table 16: Language Spoken Scoring

<table><thead><tr><th width="699.7999877929688">Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td>English, Spanish, Other Language</td><td align="center" valign="middle">+1</td></tr><tr><td><p>Detailed Language with Population 300,001 - 4,000,000</p><p><em>e.g., Chinese, Tagalog, Vietnamese, Korean</em></p></td><td align="center" valign="middle">+2</td></tr><tr><td><p>Detailed Language with Population 100,001 - 300,000</p><p><em>e.g., Persian, Hindi, Arabic, Russian, Japanese, French</em></p></td><td align="center" valign="middle">+3</td></tr><tr><td><p>Detailed Language with Population 20,001 - 100,000</p><p><em>e.g., German, Portuguese, Hmong, Hebrew, Bengali, Polish</em></p></td><td align="center" valign="middle">+5</td></tr><tr><td><p>Detailed Language with Population ≤20,000</p><p><em>e.g., Haitian, Navajo</em></p></td><td align="center" valign="middle">+7</td></tr></tbody></table>

Language spoken is captured in a variety of data systems to support individuals in receiving services in the language they speak. Language Spoken is not collected as part of the decennial Census, so the following estimates of language spoken at home are used to assess the population sizes of various languages. These estimates of language spoken are taken from the 2017-2021 5-year American Community Survey (ACS). These Statewide population estimates of language spoken along with Table 2 are used to determine the groupings for the scoring above.&#x20;

#### Table 17: California Population Estimates by Language Spoken

<table><thead><tr><th width="524" valign="middle">Language Spoken at Home for the Population 5 years and older</th><th width="238" align="center" valign="middle">California Estimate</th><th align="center" valign="middle">Margin of Error</th></tr></thead><tbody><tr><td valign="middle">Total</td><td align="center" valign="middle">37,105,018</td><td align="center" valign="middle">±669</td></tr><tr><td valign="middle">Speak only English</td><td align="center" valign="middle">20,833,290</td><td align="center" valign="middle">±49,117</td></tr><tr><td valign="middle">Spanish</td><td align="center" valign="middle">10,514,821</td><td align="center" valign="middle">±34,689</td></tr><tr><td valign="middle">Chinese (incl. Mandarin, Cantonese)</td><td align="center" valign="middle">1,259,668</td><td align="center" valign="middle">±13,770</td></tr><tr><td valign="middle">Tagalog (incl. Filipino)</td><td align="center" valign="middle">780,024</td><td align="center" valign="middle">±10,075</td></tr><tr><td valign="middle">Vietnamese</td><td align="center" valign="middle">556,398</td><td align="center" valign="middle">±8,380</td></tr><tr><td valign="middle">Korean</td><td align="center" valign="middle">358,018</td><td align="center" valign="middle">±7,365</td></tr><tr><td valign="middle">Persian (incl. Farsi, Dari)</td><td align="center" valign="middle">211,089</td><td align="center" valign="middle">±6,309</td></tr><tr><td valign="middle">Hindi</td><td align="center" valign="middle">203,238</td><td align="center" valign="middle">±6,535</td></tr><tr><td valign="middle">Arabic</td><td align="center" valign="middle">198,914</td><td align="center" valign="middle">±7,807</td></tr><tr><td valign="middle">Armenian</td><td align="center" valign="middle">195,413</td><td align="center" valign="middle">±5,581</td></tr><tr><td valign="middle">Russian</td><td align="center" valign="middle">170,508</td><td align="center" valign="middle">±4,817</td></tr><tr><td valign="middle">Punjabi</td><td align="center" valign="middle">142,450</td><td align="center" valign="middle">±6,035</td></tr><tr><td valign="middle">Japanese</td><td align="center" valign="middle">136,009</td><td align="center" valign="middle">±4,890</td></tr><tr><td valign="middle">French (incl. Cajun)</td><td align="center" valign="middle">126,338</td><td align="center" valign="middle">±4,041</td></tr><tr><td valign="middle">Ilocano, Samoan, Hawaiian, or other Austronesian languages (aggregated group)</td><td align="center" valign="middle">120,223</td><td align="center" valign="middle">±4,014</td></tr><tr><td valign="middle">German</td><td align="center" valign="middle">93,471</td><td align="center" valign="middle">±2,737</td></tr><tr><td valign="middle">Portuguese</td><td align="center" valign="middle">91,042</td><td align="center" valign="middle">±3,852</td></tr><tr><td valign="middle">Thai, Lao, or other Tai-Kadai languages (aggregated group)</td><td align="center" valign="middle">75,646</td><td align="center" valign="middle">±3,518</td></tr><tr><td valign="middle">Other Indo-European languages (aggregated group)</td><td align="center" valign="middle">75,233</td><td align="center" valign="middle">±3,511</td></tr><tr><td valign="middle">Hmong</td><td align="center" valign="middle">74,317</td><td align="center" valign="middle">±3,670</td></tr><tr><td valign="middle">Telugu</td><td align="center" valign="middle">67,956</td><td align="center" valign="middle">±3,101</td></tr><tr><td valign="middle">Khmer</td><td align="center" valign="middle">67,756</td><td align="center" valign="middle">±3,552</td></tr><tr><td valign="middle">Other languages of Asia (aggregated group)</td><td align="center" valign="middle">65,969</td><td align="center" valign="middle">±3,512</td></tr><tr><td valign="middle">Amharic, Somali, or other Afro-Asiatic languages (aggregated group)</td><td align="center" valign="middle">63,318</td><td align="center" valign="middle">±3,433</td></tr><tr><td valign="middle">Tamil</td><td align="center" valign="middle">60,594</td><td align="center" valign="middle">±2,885</td></tr><tr><td valign="middle">Nepali, Marathi, or other Indic languages (aggregated group)</td><td align="center" valign="middle">58,552</td><td align="center" valign="middle">±2,832</td></tr><tr><td valign="middle">Urdu</td><td align="center" valign="middle">54,569</td><td align="center" valign="middle">±2,938</td></tr><tr><td valign="middle">Italian</td><td align="center" valign="middle">53,954</td><td align="center" valign="middle">±2,128</td></tr><tr><td valign="middle">Gujarati</td><td align="center" valign="middle">51,662</td><td align="center" valign="middle">±2,772</td></tr><tr><td valign="middle">Hebrew</td><td align="center" valign="middle">44,540</td><td align="center" valign="middle">±2,542</td></tr><tr><td valign="middle">Ukrainian or other Slavic languages (aggregated group)</td><td align="center" valign="middle">41,606</td><td align="center" valign="middle">±2,630</td></tr><tr><td valign="middle">Malayalam, Kannada, or other Dravidian languages (aggregated group)</td><td align="center" valign="middle">37,709</td><td align="center" valign="middle">±2,672</td></tr><tr><td valign="middle">Yoruba, Twi, Igbo, or other languages of Western Africa (aggregated group)</td><td align="center" valign="middle">34,305</td><td align="center" valign="middle">±2,830</td></tr><tr><td valign="middle">Bengali</td><td align="center" valign="middle">30,223</td><td align="center" valign="middle">±2,043</td></tr><tr><td valign="middle">Yiddish, Pennsylvania Dutch or other West Germanic languages (aggregated group)</td><td align="center" valign="middle">26,359</td><td align="center" valign="middle">±1,870</td></tr><tr><td valign="middle">Polish</td><td align="center" valign="middle">21,304</td><td align="center" valign="middle">±1,639</td></tr><tr><td valign="middle">Serbo-Croatian</td><td align="center" valign="middle">20,022</td><td align="center" valign="middle">±1,470</td></tr><tr><td valign="middle">Greek</td><td align="center" valign="middle">19,783</td><td align="center" valign="middle">±1,576</td></tr><tr><td valign="middle">Swahili or other languages of Central, Eastern, and Southern Africa (aggregated group)</td><td align="center" valign="middle">16,547</td><td align="center" valign="middle">±1,558</td></tr><tr><td valign="middle">Haitian</td><td align="center" valign="middle">7,878</td><td align="center" valign="middle">±1,071</td></tr><tr><td valign="middle">Other Native languages of North America (aggregated group)</td><td align="center" valign="middle">5,841</td><td align="center" valign="middle">±713</td></tr><tr><td valign="middle">Navajo</td><td align="center" valign="middle">1,043</td><td align="center" valign="middle">±305</td></tr><tr><td valign="middle">Other and unspecified languages</td><td align="center" valign="middle">37,418</td><td align="center" valign="middle">±2,389</td></tr></tbody></table>

Based on the above numbers, the majority of individuals speak English or Spanish. Therefore, if the table includes “English”, “Spanish”, and “Other Language” as the categories for “Language Spoken”, then the score is +1 which is comparable to reporting Hispanic or Latino Ethnicity as a “Yes or No”.&#x20;

As noted for Race and Ethnicity demographics, language spoken demographics may vary significantly based on geography as well as based on particular conditions. So although the scoring criteria presents a guideline for assessing risk, the population frequencies for the specific geography and/or condition should also be taken into account.&#x20;

If more specificity for Language Spoken is being requested with respect to reporting on the other languages in the table above, the request will need to be reviewed on a case-by-case basis. The additional review is necessary given the variability of language spoken by different populations or geographies and the consideration for potential increased risk of identification.&#x20;

### 16.2.6 Sexual Orientation and Gender Identity

There are no census estimates for Sexual Orientation and Gender Identity (SOGI). Instead, we have based our risk scores on the California Health Interview Survey (CHIS) population estimates, as CHIS is the largest California survey and has publicly reproducible results via [AskCHIS](https://ask.chis.ucla.edu/ask/SitePages/AskChisLogin.aspx) and harmonized with the risk scores assigned to the age and race/ethnicity category population thresholds.

AskCHIS 2021 population estimates for SOGI are as follows (Gender Identity population estimate is from pooled years 2019-2021 as per CHIS recommendations):

* Gay/lesbian: 1.2 mil
* Bisexual: 1.5 mil
* Asexual: 400K
* Transgender or non-conforming: 279K

Based on the risk scores for age and race/ethnicity, Sexual Orientation data aggregated to the above CHIS categories would be assigned a +2 score as the smallest group (Asexual) falls within the "300,001 – 4 million" risk category. Gender Identity data aggregated to the above CHIS categories would be assigned a +3 score as "Transgender or non-confirming" falls within the "100,001 – 300,000" risk category.&#x20;

There are no estimates for more granular categories such as genderqueer and two-spirit. A +5 risk score was assigned based on the “Other Variable” category for 5-9 groups in the DDG.

The option for a variable limited to "Male or Female" has been kept for datasets that are limited to these options, or in cases where other categories aren't displayed due to confidentiality concerns. The risk score remains at +1 as both populations are greater than 4 million.

#### Table 18: Sex, Sexual Orientation, and Gender Identity Scoring

<table><thead><tr><th valign="middle">Variable</th><th valign="middle">Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle">Sex</td><td valign="middle">Male or Female</td><td align="center" valign="middle">+1</td></tr><tr><td valign="middle">Sexual Orientation</td><td valign="middle">Straight, Gay or Lesbian, Bisexual, Asexual</td><td align="center" valign="middle">+2</td></tr><tr><td valign="middle">Gender Identity</td><td valign="middle">Man/Male, Woman/Female, Transgender or Non-Binary</td><td align="center" valign="middle">+3</td></tr><tr><td valign="middle">Gender Identity</td><td valign="middle">Man/Male, Woman/Female, disaggregation of Transgender/ Non-Binary category into more specific identities (e.g. Genderqueer, Two-Spirit, etc.)</td><td align="center" valign="middle">+5</td></tr></tbody></table>

**Distinction Between Sexual Orientation and Men Having Sex with Men (MSM) Activity**

While the CDC definition of sexual orientation includes an implicit behavior in "sexual attraction", this guidance defines Sexual Orientation and Gender Identity as identifiable factors (akin to race, ethnicity, and age) to distinguish them from sexual behaviors such as "Men having Sex with Men" (MSM). This is because the former may be a publicly identifiable trait and thus a re-identification risk, while the latter is, generally, not an identification risk. For example, some individuals may engage in MSM activity but not identify as gay, while others may identify as gay but practice abstinence.&#x20;

We acknowledge that the boundary between the two is not clear cut and programs will need to assess on a case-by-case basis as to whether MSM should be considered a risk factor for redisclosure. An example of this is [an incident](https://www.pillarcatholic.com/p/pillar-investigates-usccb-gen-sec) cited in [NIST SP 800-188](https://www.nist.gov/privacy-framework/nist-sp-800-188) where geographic location from app data was used to infer MSM activity for an individual:

_According to commercially available records of app signal data obtained by The Pillar, a mobile device correlated to Burrill emitted app data signals from the location-based hookup app Grindr on a near-daily basis during parts of 2018, 2019, and 2020 — at both his USCCB office and his USCCB-owned residence, as well as during USCCB meetings and events in other cities._

This incident demonstrates the possibility that if an individual is known to use an app or frequent certain locations, one may infer MSM activity for the individual. This makes it potentially usable as a quasi-identifier to re-identify an individual. As mentioned by Abowd and Hawes in [21st Century Statistical Disclosure Limitation: Motivations and Challenges](https://arxiv.org/abs/2303.00845v1):

_The release of any statistic derived from a confidential source always carries some incremental risk of disclosure of identifiable information._

### 16.2.7 Intersex

AB 1163 (Chapter 832, Statutes of 2023) added the requirement to collect intersex status in Government Code 8310.8 when collecting “ancestry or ethnic origins of Californians.” There are no California estimates of the intersex population, but the national estimate is 1.7% of the total population. That would be a population of \~595K in California, which would be a +2 risk score as per the risk score table. The question can be asked as part of the Sex question or as its own question.

Table 19: Intersex Scoring

<table><thead><tr><th valign="middle">Variable</th><th align="center" valign="middle">Characteristic</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle">Intersex (asked as separate question)</td><td align="center" valign="middle">Yes or No</td><td align="center" valign="middle">+2</td></tr><tr><td valign="middle">Intersex (combined with Sex question)</td><td align="center" valign="middle">Male, Female, Intersex</td><td align="center" valign="middle">+2</td></tr></tbody></table>

### 16.2.8 Immigration Status

#### Table 20: Immigration Status Scoring

<table><thead><tr><th width="703" valign="top">Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="top">U.S. Citizen, Foreign Born (combines Naturalized Citizen and Noncitizen)</td><td align="center" valign="middle">+1</td></tr><tr><td valign="top">U.S. Citizen, Naturalized Citizen, Noncitizen</td><td align="center" valign="middle">+1</td></tr><tr><td valign="top">Detailed Immigration Status with Disaggregation of Noncitizen Statuses – Refer to High-Risk Populations (Section 5.6.2)</td><td align="center" valign="middle">N/A</td></tr></tbody></table>

In this version of DDG, immigration status is added as a new variable because immigration status in the summarized health care data may increase the re-identification risk of individuals due to increased granularity of the aggregated data. This additional information has the potential to make it easier to narrow down and identify individuals, especially if the dataset is combined with other publicly available sources. Immigration status often intersects with other demographic factors such as age, gender, ethnicity, and location. When combined, these factors can create a more distinct profile for certain individuals.

The U.S. Census Bureau\[11] collects citizenship data via the American Community Survey (ACS) and categorizes the population as either “U.S. citizen” or “foreign born”. The “foreign born” population is then categorized further as “natural citizen” or “noncitizen”. The noncitizen status is disaggregated into the following statuses:

* Lawful Permanent Resident
* Nonimmigrant
  * Temporary Workers
  * Students
  * Exchange Visitors
  * Refugees and Asylees
* Undocumented Immigrant

Based on reporting by the U.S. Census Bureau and the U.S. Department of Homeland Security, population estimates for different characteristics of immigration status are as below.\[12]<sup>,\[13]</sup> However, the population estimates for undocumented immigrants are based on population statistics reported by the Center for Migration Studies.\[14]

#### Table 21: Population Estimates Related to Immigration Status

<table><thead><tr><th width="555">Immigration Status</th><th valign="middle">Population Estimate</th></tr></thead><tbody><tr><td>U.S. Citizen</td><td valign="middle">~28.8 million</td></tr><tr><td>Foreign Born</td><td valign="middle">~10.5 million</td></tr><tr><td><ul><li>Naturalized Citizens</li></ul></td><td valign="middle">~5.7 million</td></tr><tr><td><ul><li><p>Noncitizens</p><ul><li>Lawful Permanent Residents</li><li><p>Nonimmigrants</p><ul><li>Temporary Workers</li><li>Students</li><li>Exchange Visitors</li><li>Refugees/Asylees</li></ul></li><li>Undocumented Immigrants</li></ul></li></ul></td><td valign="middle"><ul><li><p>~4.7 million</p><ul><li>~2.2 million</li><li><p>~560,000</p><ul><li>~300,000</li><li>~210,000</li><li>~50,000</li><li>&#x3C;10,000</li></ul></li><li><a data-footnote-ref href="#user-content-fn-1">2,251,756</a></li></ul></li></ul></td></tr></tbody></table>

Immigration Status scores are prepared based on the [U.S. Census Bureau](#user-content-fn-2)[^2] population data collected on U.S. citizen and foreign-born populations (Table 21 rows for Naturalized Citizens and Noncitizens). Disaggregated immigration status population sizes are prepared based on the Department of Homeland Security Population Estimates for [lawful permanent residents](#user-content-fn-3)[^3] (Table 21 row for Lawful Permanent Residents) and nonimmigrants[^4] (Table 21 rows for Nonimmigrants, Temporary Workers, Students, and Exchange Visitors), including Refugees/Asylees[^5]. The scores are then harmonized with the risk scores assigned to the latest population size thresholds, Table 2. Immigration statuses for disaggregated statuses, and smaller corresponding population sizes are added to the high-risk populations due to the sensitive nature of these populations and an increased risk for identification.

### 16.2.9 Insurance Coverage

Insurance Coverage is a factor that may be a proxy for other identifiers. For example, employment-based payers may provide information about a person’s job status. Other types of payers, such as Medicaid, may provide information about a person’s income. There is demographic data that indicates populations by income level in the public domain as [published by the U.S. Census Bureau](#user-content-fn-6)[^6], as well as public information related to various jobs and employment status through[ labor agencies.](#user-content-fn-7)[^7] Given the opportunities to use information about the payer in combination with other public information, this variable is given a risk score. The risk is scored as below given the member size of the Insurance [Coverage in the various categories](#user-content-fn-8)[^8].

#### Table 22: Insurance Coverage

<table><thead><tr><th width="699.800048828125" valign="middle">Characteristic</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle">Coverage with >2,000,000 members</td><td align="center" valign="middle">-5</td></tr><tr><td valign="middle">Coverage with 1,000,001 - 2,000,000 members</td><td align="center" valign="middle">-3</td></tr><tr><td valign="middle">Coverage with 560,001 - 1,000,000 members</td><td align="center" valign="middle">-1</td></tr><tr><td valign="middle">Coverage with 250,001 - 560,000 members</td><td align="center" valign="middle">0</td></tr><tr><td valign="middle">Coverage with 100,001 - 250,000 members</td><td align="center" valign="middle">+1</td></tr><tr><td valign="middle">Coverage with 50,001 - 100,000 members</td><td align="center" valign="middle">+3</td></tr><tr><td valign="middle">Coverage with 20,001 - 50,000 members</td><td align="center" valign="middle">+4</td></tr><tr><td valign="middle">Coverage with ≤ 20,000 members</td><td align="center" valign="middle">+5</td></tr></tbody></table>

See Appendix I for more details on scoring scenarios involving the overlap of Insurance Coverage, Expected Payer/Public Assistance and Means-Tested Programs, and Geography. Below are three key points that summarize all the scenarios:

1. If the data is ONLY related to Residence or Service Geography, then DO NOT USE Insurance Coverage or Means-Tested Tables.
2. Means-Tested Programs—Only add interaction if enrollment in the Public Assistance program is 10 million or fewer people. No interaction is needed for Medi-Cal as the current enrollment is approximately 14 million, which exceeds 10 million.
3. If the number of members enrolled in Insurance Coverage is less than the population of the geographic subdivision, then use the Insurance Table. If the number of members enrolled in Insurance Coverage is greater than or equal to the population of the geographic subdivision, then use the Geography Table.

### 16.2.10 Expected Payer/ Public Assistance and Means-Tested Programs

Expected Payer is a factor that may be a proxy for other identifiers. For example, employment-based payers may provide information about a person’s job status. Other types of payers, such as Medicaid, may provide information about a person’s income. There is demographic data that indicates populations by income level in the public domain as [published by the U.S. Census Bureau](#user-content-fn-6)[^6], as well as public information related to various jobs and employment status [through labor agencies](#user-content-fn-7)[^7]. Given the opportunities to use information about the payer in combination with other public information, this variable is given a risk score.

It's important to be aware of the potential risks associated with this data and to ensure its security and protection. For instance, eligibility for benefits in the Medi-Cal program may be determined based on income, property, and assets. Similarly, self-pay data, often associated with the uninsured, can also indicate low income, highlighting the need for data security.

#### Table 23: Expected Payer/ Public Assistance and Means-Tested Programs Scoring

<table><thead><tr><th width="699.800048828125" valign="middle">Size of program enrollment</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle">Enrollment > 10,000,000 people</td><td align="center" valign="middle">+0</td></tr><tr><td valign="middle">Enrollment > 4,000,001 – 10,000,000</td><td align="center" valign="middle">+1</td></tr><tr><td valign="middle">Enrollment 300,001 – 4,000,000</td><td align="center" valign="middle">+2</td></tr><tr><td valign="middle">Enrollment 100,001 – 300,000</td><td align="center" valign="middle">+3</td></tr><tr><td valign="middle">Enrollment 20,001 – 100,000</td><td align="center" valign="middle">+5</td></tr><tr><td valign="middle">Enrollment ≤20,000</td><td align="center" valign="middle">+7</td></tr></tbody></table>

It is important to note that Medi-Cal is a Means-Tested Program, and overall enrollment is managed at the statewide level. In 2024, approximately 14 million Californians were enrolled in the Medi-Cal program, therefore, the Medi-Cal category has been assigned a +0 DDG score. Also, more than 6 million California residents had Medicare coverage, therefore, the Medicare category has been assigned a +1 DDG score. There are approximately 5.5 million patients captured in the HCAI Health Care Payments Database who have private insurance and thus assigned as +1 score. The uninsured population, who we presume would self-pay seems to be less than 4 million (2,752,067 based on the 2022 5-year American Community Survey estimate for California), has been assigned a +2 score.

In addition to Medi-Cal, CalHHS administers and collects data on a variety of [public assistance programs](#user-content-fn-9)[^9] or [means-tested programs](#user-content-fn-10)[^10]. In these programs, a granting entity uses information on an individual’s income and resources to determine eligibility for the program. Knowing that an individual is on a means-tested program or a public assistance program can reveal sensitive information about their income, employment status, or other personal characteristic related to eligibility. For example, recipients of SNAP are typically at 130% of the Federal Poverty Level. To qualify for TANF, assistance units must be at 100% of the Federal Poverty Level. Major federal programs include Medicaid (Medi-Cal in California), the Earned Income Tax Credit, the Supplemental Nutrition Assistance Program (CalFresh), Supplemental Security Income (SSI), and Special Supplemental Nutrition Program for Women, Infants, and Children (WIC). Additionally, there are several state-funded public assistance programs, including state anti-poverty tax credits, housing and homelessness programs, and programs such as the Cash Assistance Program for Immigrants (CAPI) and the California Food Assistance Program (CFAP).

The size of these programs ranges widely; as noted in the previous section, 14 million Californians are enrolled in Medi-Cal. Roughly 5.5 million Californians [participated in CalFresh in 2024](#user-content-fn-11)[^11]. CalWORKs served a little [over 900,000 Californians in 2023](#user-content-fn-12)[^12]. In the Housing Support Program, fewer than 13,000 [applications were approved](#user-content-fn-13)[^13]. Risk scores should be assigned to data related to (or breaking out) participation by program enrollment. To prevent the inadvertent disclosure of an individual’s participation in a means-tested or public assistance program, the following risk scores can be assigned to data that includes information on program participation, based on the size of the program (note, these numbers are derived from Table 2) and Means-Tested Programs, and Geography.

### 16.2.11 Geography

If the level of reporting is best described by the geography of the individual/service, use one of the following two tables. Specifically, if the geography of the reporting is based on the residence of the individual, use the “Residence Geography”. If the geography of the reporting is based on the location of service, use the “Service Geography”. Also see Appendix I for details on scoring scenarios involving the overlap of Insurance Coverage, Expected Payer/Public Assistance and Means-Tested Programs, and Geography.

#### Table 24: Residence Geography Scoring

<table><thead><tr><th width="701.4000244140625" valign="top">Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="top">State or geography with population >2,000,000</td><td align="center" valign="middle">-5</td></tr><tr><td valign="top">Population 1,000,001 - 2,000,000</td><td align="center" valign="middle">-3</td></tr><tr><td valign="top">Population 560,001 - 1,000,000</td><td align="center" valign="middle">-1</td></tr><tr><td valign="top">Population 250,001 - 560,000</td><td align="center" valign="middle">0</td></tr><tr><td valign="top">Population 100,001 - 250,000</td><td align="center" valign="middle">+1</td></tr><tr><td valign="top">Population 50,001 - 100,000</td><td align="center" valign="middle">+3</td></tr><tr><td valign="top">Population 20,001 - 50,000</td><td align="center" valign="middle">+4</td></tr><tr><td valign="top">Population 4,001- 20,000</td><td align="center" valign="middle">+5</td></tr><tr><td valign="top">Population ≤ 4,000</td><td align="center" valign="middle">+7</td></tr></tbody></table>

#### Table 25: Service Geography Scoring

<table><thead><tr><th width="701.4000244140625" valign="middle">Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle">State or geography with population >2,000,000</td><td align="center" valign="middle">-5</td></tr><tr><td valign="middle">Population 1,000,001 - 2,000,000</td><td align="center" valign="middle">-4</td></tr><tr><td valign="middle">Population 560,001 - 1,000,000</td><td align="center" valign="middle">-3</td></tr><tr><td valign="middle">Population 250,001 - 560,000</td><td align="center" valign="middle">-1</td></tr><tr><td valign="middle">Population of reporting region 20,001 - 250,000</td><td align="center" valign="middle">0</td></tr><tr><td valign="middle">Population of reporting region ≤20,000</td><td align="center" valign="middle">+1</td></tr><tr><td valign="middle">Address (Street and ZIP)</td><td align="center" valign="middle">+3</td></tr><tr><td valign="middle"><a data-footnote-ref href="#user-content-fn-14">Address in rural area</a></td><td align="center" valign="middle">+5</td></tr><tr><td valign="middle"><a data-footnote-ref href="#user-content-fn-15">Address in frontier area</a></td><td align="center" valign="middle">+7</td></tr></tbody></table>

The Geography score, while it may or may not represent the denominator of the table, does provide a reference to the base population about which the reporting is occurring. This will often be reflected in the title of the table if a statewide table. Otherwise, the geography may be represented in the rows or columns. There are two different scoring sets based on whether the geography reporting is based on the residence of the individual to which the information applies or to the service location.

The scores are higher for geography related to residence address because so much information is publicly available about individuals and their address of residence. For large populations greater than 560,000, which is equivalent to the size of a state, there is a negative score because the size of the denominator masks the individual. The number 560,000 was chosen as a cut-off because this is the size of the smallest state (Wyoming). We chose to use the cut-off at the smallest state’s population because state level reporting is not listed as one of the 18 identifiers in the HIPAA Safe Harbor method.

The scores for the service geography are lower because clients can generally come from diverse locations for services. Although people often seek services or have health conditions close to their homes, they may also travel extensive distances. Reviewers do need to make sure that there are no constraints associated with services that would mean the service geography and resident geography are the same. For example, if a program publishes service utilization by county and the county services can only be used by county residents, then the service utilization by county is also the county of residence. Scoring should be based on the criteria that result in the highest score and, thus, the highest risk.

There are smaller areas within counties where the population is significantly lower than the overall county population. One example of this is census tracts, which are small, relatively stable statistical subdivisions of a county or an equivalent statistical entity. These tracts can be updated by local participants before each decennial census through the Census Bureau’s Participant Statistical Areas Program (PSAP). [Census tracts](#user-content-fn-16)[^16] typically cover contiguous areas, but their size can vary widely based on population density. The boundaries of these tracts are designed to remain unchanged over time, allowing for consistent statistical comparisons from one census to the next. Generally, census tracts have populations ranging from 1,200 to 8,000 people, with an optimum size of population around 4,000. To account for the higher re-identification risk associated with smaller populations, a score of +7 is assigned when the population size is 4,000 or fewer in the residential area.

Service Geography includes a level of detail that is identified as “Address (Street and ZIP).” This deals with reporting by provider (hospital, clinic, provider office, etc.) Provider addresses are public information and are public at the street address level. A given provider will tend to have a standard catchment area or the geographic boundaries from which most patients come from. [This information is published by the Department of Health Care Access and Information (previously the Office of Statewide Health Planning and Development - OSHPD)](#user-content-fn-17)[^17] for hospitals. While this addresses where most patients or clients come from, patients or clients may also come from outside the catchment area. For that reason, this does not score as high as the more detailed geography under Residence Geography.

However, addresses associated with rural and frontier areas have a higher re-identification risk due to lower population density per square mile and isolation of communities in these areas. Thus, higher scores are assigned for Providers’ addresses, except where the Provider is defined as Hospital, in rural and frontier areas.\[38] \[39]

### 16.2.12 Time – Reporting Period

#### Table 26: Time – Reporting Period Scoring

<table><thead><tr><th width="699.7999877929688" valign="middle">Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle">5 years aggregated</td><td align="center" valign="middle">-5</td></tr><tr><td valign="middle">2-4 years aggregated</td><td align="center" valign="middle">-3</td></tr><tr><td valign="middle">1 year (e.g., 2001)</td><td align="center" valign="middle">0</td></tr><tr><td valign="middle">Bi-Annual</td><td align="center" valign="middle">+3</td></tr><tr><td valign="middle">Quarterly</td><td align="center" valign="middle">+4</td></tr><tr><td valign="middle">Monthly</td><td align="center" valign="middle">+5</td></tr></tbody></table>

Many reports are published based on the calendar year. However, the combination of years of data is an excellent way to provide increased aggregation in a way that allows for more specificity elsewhere, such as county identifiers. Inversely, the smaller the time period in the data, the closer the time period comes to approximating a date. Thus, monthly reported data has a high score of +5.

Of note, the HIPAA Safe Harbor method list includes “All elements of dates (except year) for dates that are directly related to an individual, including birth date, admission date, discharge date, death date, and all ages over 89 and all elements of dates (including year) indicative of such age, except that such ages and elements may be aggregated into a single category of age 90 or older.” This is a potential identifier when in combination with other information. This potential as an identifier influences the higher scores in the Publication Scoring Criteria as the time period for aggregation gets smaller.&#x20;

The “0” value for this variable is set at one year as this is the criteria for Safe Harbor under the HIPAA de-identification standard.

### 16.2.13 Variable Interactions

#### Table 27: Variable Interactions Scoring

<table><thead><tr><th width="700.5999755859375" valign="top">Characteristics</th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="top">Only Events (minimum of 5), Time, and Population (Residence/Service Geography or Insurance Coverage</td><td align="center" valign="middle">-5</td></tr><tr><td valign="top">Only Events (minimum of 3), Time, and Population (Residence/Service Geo. or Insurance Coverage)</td><td align="center" valign="middle">-3</td></tr><tr><td valign="top">Only Events (no minimum), Time, and Population (Residence/Service Geo. or Insurance Coverage)</td><td align="center" valign="middle">0</td></tr><tr><td valign="top">Events, Time, and Population (Residence/Service Geo. or Insurance Coverage) + 1 variable</td><td align="center" valign="middle">+1</td></tr><tr><td valign="top">Events, Time, and Population (Residence/Service Geo. or Insurance Coverage) + 2 variables</td><td align="center" valign="middle">+2</td></tr><tr><td valign="top">Events, Time, and Population (Residence/Service Geo. or Insurance Coverage) + 3 variables</td><td align="center" valign="middle">+4</td></tr></tbody></table>

These criteria specifically address the interaction of the variables in a given data presentation and require the analyst to identify dependent as opposed to independent variables. These criteria are used with respect to dependent variables. This is demonstrated in the two tables below.

Illustration A: Dependent Variables

In this example the Event (counts of Disease A) is shown for Males who are also 0-17 years old or Males who are also 18-25 years old. In this case Sex and Age are dependent because the stratification for each variable is stacked. This commonly occurs in pivot tables.

#### Table 28: Illustration A: Dependent Variables Example

<table><thead><tr><th valign="middle">Counts of disease A by year</th><th align="center" valign="middle">Males and 0-17 years old</th><th align="center" valign="middle">Males and 18-25 years old</th><th align="center" valign="middle">Females and 0-17 years old</th><th align="center" valign="middle">Females and 18-25 years old</th></tr></thead><tbody><tr><td valign="middle">Year 1</td><td align="center" valign="middle">6</td><td align="center" valign="middle">10</td><td align="center" valign="middle">5</td><td align="center" valign="middle">8</td></tr><tr><td valign="middle">Year 2</td><td align="center" valign="middle">8</td><td align="center" valign="middle">14</td><td align="center" valign="middle">3</td><td align="center" valign="middle">20</td></tr></tbody></table>

Illustration B: Independent Variables

In this example the Event (counts of Disease A) is for Males or Females which is shown side by side to a table with ages 0-17 years old or 18-25 years old. In this case Sex and Age are independent because the stratification for each variable is not stacked. Although the two variables Sex and Age are shown in the same table, they are presented independently of each other. While you can compile the data in Example B from Example A, the reverse is not true.

#### Table 29: Illustration B: Independent Variables Example

<table><thead><tr><th valign="top">Counts of disease A by year</th><th align="center" valign="middle">Males</th><th align="center" valign="middle">Females</th><th align="center" valign="middle">0-17 years old</th><th align="center" valign="middle">18-25 years old</th></tr></thead><tbody><tr><td valign="top">Year 1</td><td align="center" valign="middle">16</td><td align="center" valign="middle">13</td><td align="center" valign="middle">11</td><td align="center" valign="middle">18</td></tr><tr><td valign="top">Year 2</td><td align="center" valign="middle">22</td><td align="center" valign="middle">23</td><td align="center" valign="middle">11</td><td align="center" valign="middle">34</td></tr></tbody></table>

These criteria are structured to have less impact if personal characteristics outside of time and geography are excluded and more impact if multiple personal characteristics are included. This provides for a subtraction of points if the only variables presented are the events (numerator), time and geography and an addition of points for including more variables in a given presentation. With respect to the subtraction of points, the score is based on the minimum value for the Events variable. For example, if the smallest value for the Events is 5 or more, then the score would be -5. However, if the smallest value for the Events is 2, then the score would be 0.&#x20;

The minimum value for Events of 3 _(Only Events (minimum of 3), Time, and Geography (Residence or Service))_ is used as a threshold to address concern for pre-existing knowledge by users about individuals. For example, if an entity knows who one person is with disease A and the count for Events is “1” or “2”, then the entity could identify the person they know of or the person they know of plus information about the other person. The use of a minimum of 3 does not protect against two entities colluding to determine a third person.\[40]  For this reason, the threshold of 5 for Events is also given. The threshold of 5 is frequently used in public health reporting regarding various events.

In contrast, if additional demographic variables are added, then the risk increases significantly. For example, for Events, Time and Geography (Residence or Service) with three additional variables, a table would show how many individuals are female by age group by race for a given time period and geography. This allows for a more detailed comparison to census data and assessment of the number of individuals with a particular set of characteristics.\[41] For this reason, additional points are added because of the inclusion of multiple dependent variables.

### 16.2.14 Other Variables

Variables not specified in the Publication Scoring Criteria can be released only after an additional, case-by-case review by the department’s Statistical De-Identification Expert or Statistical De-Identification Supervisor Expert. We suggest that this review considers population size-based scores if population size of the characteristics of a variable is present, or otherwise scores based on number of groups or categories.

#### 1. Other Variable Scores Based on Population Size

#### Table 30: Generalized Scoring Criteria based on Statewide Population&#x20;

<table><thead><tr><th width="699.800048828125" valign="top">Population Size </th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="top">Population >4,000,000 </td><td align="center" valign="middle">+1 </td></tr><tr><td valign="top">Population 300,001 – 4,000,000 </td><td align="center" valign="middle">+2 </td></tr><tr><td valign="top">Population 100,001 – 300,000 </td><td align="center" valign="middle">+3 </td></tr><tr><td valign="top">Population 20,001 – 100,000 </td><td align="center" valign="middle">+5 </td></tr><tr><td valign="top">Population ≤20,000 </td><td align="center" valign="middle">+7  </td></tr></tbody></table>

The above table shows scoring criteria for population size in general and can be used to score veteran status and educational attainment. Examples follow below of how these variables can be considered by using data at the Census American Community Survey.\[42]

Veteran Status

For the California statewide population estimate of 1,467,025 listed below for the adult civilian veteran population, a score of +2 would be assigned from Table 2 based on Statewide Population (Population 300,001 – 4,000,000).

Table 31: Veteran Status recorded from the 2021 American Community Survey

<table><thead><tr><th valign="top">Veteran Status for Population 18 years and over</th><th align="center" valign="middle">California Estimate</th><th align="center" valign="middle">Margin of Error</th></tr></thead><tbody><tr><td valign="top">Civilian veterans </td><td align="center" valign="middle">1,467,026</td><td align="center" valign="middle">±9,913</td></tr></tbody></table>

Note that even though there is an implicit age associated with veteran status, this information is incorporated into the population estimate used for the score. Therefore, an additional score modifier for the age should not be applied.

Other aspects of the subpopulation should be considered when assessing risk. For example, more than 90 percent of the veteran population is male.\[43] Therefore, reporting of veterans by sex would have more risk than the scores for sex based on the statewide population due to the small number of female veterans.

Educational Attainment

Similarly, the population estimates\[44] in the table below can be used to score Education Attainment Status by using Table 2.&#x20;

### Table 32: Educational Attainment Status recorded from the 2021 American Community Survey

<table><thead><tr><th valign="middle">Educational Attainment for Population 25 years and over </th><th align="center" valign="middle">California Estimate</th><th align="center" valign="middle">Margin of Error</th></tr></thead><tbody><tr><td valign="middle">Less than 9th grade, no high school diploma </td><td align="center" valign="middle">2,342,364 </td><td align="center" valign="middle">±15,809</td></tr><tr><td valign="middle">9th to 12th grade, no high school diploma </td><td align="center" valign="middle">1,893,671 </td><td align="center" valign="middle">±12,037</td></tr><tr><td valign="middle">High school graduate (includes equivalency) </td><td align="center" valign="middle">5,477,154 </td><td align="center" valign="middle">±28,244</td></tr><tr><td valign="middle">Some college, no degree </td><td align="center" valign="middle">5,496,578 </td><td align="center" valign="middle">±16,961</td></tr><tr><td valign="middle">Associate's degree </td><td align="center" valign="middle">2,135,865 </td><td align="center" valign="middle">±13,333</td></tr><tr><td valign="middle">Bachelor's degree </td><td align="center" valign="middle">5,855,383 </td><td align="center" valign="middle">±22,797</td></tr><tr><td valign="middle">Graduate or professional degree </td><td align="center" valign="middle">3,596,055 </td><td align="center" valign="middle">±25,828</td></tr><tr><td valign="middle">High school graduate or higher </td><td align="center" valign="middle">22,561,035 </td><td align="center" valign="middle">±20,560</td></tr><tr><td valign="middle">Bachelor's degree or higher </td><td align="center" valign="middle">9,451,438 </td><td align="center" valign="middle">±40,058</td></tr></tbody></table>

For example, the smallest California population with a recorded educational attainment level is 2,135,865 for an Associate degree. Thus, a score of +2 (Population 300,001 – 4,000,000) from the Table 2 would be assigned. Whereas the score would be +1 (Population >4,000,000) if educational attainment is combined from the table into two categories as follows:

* No college (sum of rows 1-3): 9,713,189 (2,342,364 + 1,893,671 + 5,477,154)
* At least some college (sum of rows 4-7): 17,083,881 (5,496,578 + 2,135,865 + 5,855,383 + 3,596,055)

**2. Other Variable Scores Based on Number of Groups or Categories**

#### Table 33: Other Variable Scoring Based on Number of Groups or Categories

<table><thead><tr><th width="699.7999877929688" valign="middle">Number of Groups or Categories  </th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle">&#x3C;5 groups or categories  </td><td align="center" valign="middle">+3 </td></tr><tr><td valign="middle">5-9 groups </td><td align="center" valign="middle">+5</td></tr><tr><td valign="middle">10+ groups  </td><td align="center" valign="middle">+7 </td></tr></tbody></table>

If population size is not available for a variable, then score the variable based on number of groups or categories as well as the characteristics of the variables. &#x20;

For example, legal class groupings associated with a patient’s commitment to the state hospital system are an example of groups or categories. At the highest level, patients can be categorized into two groups: forensic commitment or civil commitments. At a more granular level, patients can be categorized into specific legal classes such defendants found incompetent to stand trial, parolees diagnosed with mental health disorders, individuals found to be not guilty by reason of insanity, mentally ill prisoners transferred from prison to a state hospital for mental health care, individuals committed to the state hospital system as sexually violent predators, or patients civilly committed to a state hospital as described in the Lanterman-Petris-Short Act.

#### Table 34: Example Scoring for Legal Class Groupings

<table><thead><tr><th width="700.6001586914062" valign="middle">Groups or Categories </th><th align="center" valign="middle">Score</th></tr></thead><tbody><tr><td valign="middle"><p>2 Groups</p><ul><li>Forensic commitments</li><li>Civil commitments</li></ul></td><td align="center" valign="middle">+3 </td></tr><tr><td valign="middle"><p>6 Groups</p><ul><li>Incompetent to stand trial</li><li>Offenders with a mental health disorder</li><li>Not guilty by reason of insanity</li><li>Mentally ill prisoners</li><li>Sexually violent predators</li><li>Lanterman-Petris-Short Act commitments</li></ul></td><td align="center" valign="middle">+5 </td></tr></tbody></table>

Some additional examples can be found in “Data with more Specificity” Section 5.61. Along with number of groups or categories, consider the specificity of the groups or categories, that is, whether the variable represents an aggregation (e.g., Diagnosis Related Groups) or a specific item (e.g., ICD-10 Code).

Also consider the availability of the variable to the public when also associated with other information, particularly the availability of variables that are personal characteristics.

How publicly identifiable the trait in question is should also be considered. For example, unreconstructed cleft palate is a physically identifiable trait. Dyslexia is a condition that, while not physically identifiable, may be something an individual mentions they have and should also be considered a publicly identifiable trait.

***

\[1] “Medicare Fee-For Service Provider Utilization & Payment Data Physician and Other Supplier Public Use File: A Methodological Overview,” Prepared by: The Centers for Medicare and Medicaid Services, Office of Information Products and Data Analytics, April 7, 2014.

\[2] See P. Golle. Revisiting the uniqueness of simple demographics in the US population. In _Proceedings of the 5th ACM Workshop on Privacy in the Electronic Society_. ACM Press, New York, NY. 2006: 77-80.

\[3] See L. Sweeney. K-anonymity: a model for protecting privacy. _International Journal of Uncertainty, Fuzziness, and Knowledge-Based Systems_. 2002; 10(5): 557-570.

\[4] See L. Sweeney. Testimony before that National Center for Vital and Health Statistics Workgroup for Secondary Uses of Health Information. August 23, 2007.

\[5] California Health and Human Services, Data De-Identification Guidelines (DDG), Edition 1.0, September 23, 2016, [https://chhsa.dsh.ca.gov/wp-content/uploads/2021/04/CHHS-Data\_Deidentification\_Guidelines-V1.0-092316.pdf](https://chhsa.dsh.ca.gov/wp-content/uploads/2021/04/CHHS-Data_Deidentification_Guidelines-V1.0-092316.pdf)

\[6] U.S. Census Bureau, "SEX BY SINGLE-YEAR AGE," 2020. Decennial Census, DEC Demographic and Housing Characteristics, Table PCT12, 2020, accessed on October 6, 2023, [https://data.census.gov/table/DECENNIALDHC2020.PCT12?g=040XX00US06](https://data.census.gov/table/DECENNIALDHC2020.PCT12?g=040XX00US06).&#x20;

\[7] U.S. Office of Management and Budget. Revisions to the Standards for the Classification of Federal Data on Race and Ethnicity, [https://www.federalregister.gov/d/97-28653](https://www.federalregister.gov/d/97-28653).

\[8] U.S. Census Bureau, "RACE," 2020. Decennial Census, DEC Redistricting Data (PL 94-171), Table P1, 2020, accessed on October 6, 2023, [https://data.census.gov/table/DECENNIALPL2020.P1?g=040XX00US06,06$0500000](https://data.census.gov/table/DECENNIALPL2020.P1?g=040XX00US06,06$0500000).

\[9] U.S. Census Bureau, "HISPANIC OR LATINO, AND NOT HISPANIC OR LATINO BY RACE," 2020. Decennial Census, DEC Redistricting Data (PL 94-171), Table P2, 2020, accessed on October 6, 2023, [https://data.census.gov/table/DECENNIALPL2020.P2?g=040XX00US06,06$0500000](https://data.census.gov/table/DECENNIALPL2020.P2?g=040XX00US06,06$0500000).

\[10] U.S. Office of Management and Budget. Initial Proposals For Updating OMB's Race and Ethnicity Statistical Standards, [https://www.federalregister.gov/d/2023-01635](https://www.federalregister.gov/d/2023-01635).

\[11] U.S. Census Bureau, " SELECTED CHARACTERISTICS OF THE NATIVE AND FOREIGN-BORN POPULATIONS," 2022. American Community Survey, ACS 5-Year Estimates Subject Tables, Table S0501, 2022, accessed on December 11, 2023, [https://data.census.gov/table/ACSST5Y2022.S0501?q=S0501](https://data.census.gov/table/ACSST5Y2022.S0501?q=S0501)

\[12] U.S. Department of Homeland Security, Office of Homeland Security Statistics, “Population Estimates of Nonimmigrants Residing in the United States: Fiscal Years 2017-2019” May 2021, Retrieved June 2, 2025, from [https://ohss.dhs.gov/sites/default/files/2023-12/ni\_population\_estimates\_fiscal\_years\_2017\_-\_2019v2.pdf](https://ohss.dhs.gov/sites/default/files/2023-12/ni_population_estimates_fiscal_years_2017_-_2019v2.pdf)

\[13] U.S. Department of Homeland Security, Office of Homeland Security Statistics, “Refugees and Asylees: 2020” Annual Flow Report for Fiscal Year 2020. March 2022, [Retrieved June 2](file:///C:/Users/daggarwa/AppData/Local/Microsoft/Windows/INetCache/Content.Outlook/P0BIF5U8/Retrieved%20June%202), 2025, from [https://ohss.dhs.gov/sites/default/files/2023-12/2022\_0308\_plcy\_refugee\_and\_asylee\_fy2020v2.pdf](https://ohss.dhs.gov/sites/default/files/2023-12/2022_0308_plcy_refugee_and_asylee_fy2020v2.pdf) &#x20;











\[18] U.S. Department of Homeland Security, Office of Homeland Security Statistics, “Population Estimates of Nonimmigrants Residing in the United States: Fiscal Years 2017-2019” May 2021, Retrieved June 2, 2025, from [https://ohss.dhs.gov/sites/default/files/2023-12/ni\_population\_estimates\_fiscal\_years\_2017\_-\_2019v2.pdf](https://ohss.dhs.gov/sites/default/files/2023-12/ni_population_estimates_fiscal_years_2017_-_2019v2.pdf).

\[19] U.S. Department of Homeland Security, Office of Homeland Security Statistics, “Refugees and Asylees: 2020” Annual Flow Report for Fiscal Year 2020. March 2022, [Retrieved June 2](file:///C:/Users/daggarwa/AppData/Local/Microsoft/Windows/INetCache/Content.Outlook/P0BIF5U8/Retrieved%20June%202), 2025, from [https://ohss.dhs.gov/sites/default/files/2023-12/2022\_0308\_plcy\_refugee\_and\_asylee\_fy2020v2.pdf](https://ohss.dhs.gov/sites/default/files/2023-12/2022_0308_plcy_refugee_and_asylee_fy2020v2.pdf).&#x20;

\[20] U.S. Census Bureau, Census Datasets on income topics,[ (census.gov)](https://www.census.gov/data/datasets.html)

\[21] U.S. Bureau of Labor Statistics, [Occupation Finder: Occupational Outlook Handbook (bls.gov)](https://www.bls.gov/ooh/occupation-finder.htm)

\[22] California Employment Development Department, California Open Data Portal datasets, [https://data.ca.gov/organization/california-employment-development-department](https://data.ca.gov/organization/california-employment-development-department)&#x20;

\[23] Department of Health Care Access and Information, Health Care Payments Data Snapshot “Data Overview – Count of Individuals by Payer Type”, [https://hcai.ca.gov/visualizations/healthcare-payments-data-hpd-snapshot/](https://hcai.ca.gov/visualizations/healthcare-payments-data-hpd-snapshot/)

\[24] Department of Health Care Access and Information, Report to the Legislature “Program Report: Health Care Payments Data Program”, May 2024, [https://hcai.ca.gov/wp-content/uploads/2024/04/HPD-Report-to-the-Legislature-March-2024-1.pdf](https://hcai.ca.gov/wp-content/uploads/2024/04/HPD-Report-to-the-Legislature-March-2024-1.pdf)

\[25] U.S. Census Bureau, Census Datasets on income topics,[ (census.gov)](https://www.census.gov/data/datasets.html)

\[26] U.S. Bureau of Labor Statistics, [Occupation Finder: Occupational Outlook Handbook (bls.gov)](https://www.bls.gov/ooh/occupation-finder.htm)

\[27] California Employment Development Department, California Open Data Portal datasets, [https://data.ca.gov/organization/california-employment-development-department](https://data.ca.gov/organization/california-employment-development-department)&#x20;

\[28] U.S. Census Bureau, “About Program Income and Public Assistance,” (2025) [https://www.census.gov/topics/income-poverty/public-assistance/about.html](https://www.census.gov/topics/income-poverty/public-assistance/about.html), Accessed March 25, 2025

\[29] https://studentaid.gov/help/means-tested-benefits

\[30] California Department of Social Services. CalFresh Dashboard. [https://public.tableau.com/app/profile/california.department.of.social.services/viz/CFdashboard-PUBLIC/AnnualParticipation](https://public.tableau.com/app/profile/california.department.of.social.services/viz/CFdashboard-PUBLIC/AnnualParticipation). 2025. Accessed March 25, 2025.

\[31] California Department of Social Services. CalWORKs Take up. CalWORKs Interactive Summary. [https://www.cdss.ca.gov/inforesources/calworks-summary/program-overview/take-up#C018](https://www.cdss.ca.gov/inforesources/calworks-summary/program-overview/take-up#C018). 2025. Accessed March 25, 2025.

\[32] California Department of Social Services. Housing Support Program. CalWORKs Interactive Summary. [https://www.cdss.ca.gov/inforesources/calworks-summary/program-services-utilization/housing-and-homelessness#C004](https://www.cdss.ca.gov/inforesources/calworks-summary/program-services-utilization/housing-and-homelessness#C004). 2025. Accessed March 25, 2025

\[33] U.S. Census Bureau, 2020 Census ”Urban and Rural” Classifications, [https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html](https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html)

\[34] National Rural Health Association, “Definition of Frontier”, Retrieved June 2, 2025, from [https://www.ruralhealth.us/getmedia/132306e1-1643-4b40-818a-4d743317dc7e/NRHAFrontierDefPolicyPaperFeb2016.pdf](https://www.ruralhealth.us/getmedia/132306e1-1643-4b40-818a-4d743317dc7e/NRHAFrontierDefPolicyPaperFeb2016.pdf) &#x20;

\[35] U.S. Department of Agriculture Economic Research Service, ”Frontier and Remote Area Codes”, Retrieved June 2, 2025, from [https://www.ers.usda.gov/data-products/frontier-and-remote-area-codes](https://www.ers.usda.gov/data-products/frontier-and-remote-area-codes)

\[36] United States Census Bureau, Geography Program Glossary, [https://www.census.gov/programs-surveys/geography/about/glossary.html#:\~:text=Census%20Tract,-Census%20Tracts%20are\&text=The%20primary%20purpose%20of%20census,optimum%20size%20of%204%2C000%20people.](https://www.census.gov/programs-surveys/geography/about/glossary.html)

\[37] Department of Health Care Access and Information, “Facility Market Share and Patient Origin” Reports, Retrieved June 2, 2025, from [https://hcai.ca.gov/visualizations/facility-market-share-and-patient-origin/](https://hcai.ca.gov/visualizations/facility-market-share-and-patient-origin/)

\[38] Medical Service Study Areas 2010, Retrieved on April 2, 2024, from: [https://gis.data.ca.gov/maps/fe411f2d74494b89a74ab181b22fc8a1/about](https://gis.data.ca.gov/maps/fe411f2d74494b89a74ab181b22fc8a1/about%20)

\[39] United States Census Bureau, “About Geographic Areas: Urban and Rural”, Retrieved on April 2, 2024, from: [https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html](https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html)

\[40] NORC, “NORC Recommendations for California Department of Health Care Services (DHCS) Data De-Identification Guidelines (DDG),” January 8, 2016.

\[41] NORC, “Case Study: The Disclosure Risk Implications of Small Cells Combined with Multiple Tables or External Data,” January 8, 2016.

\[42] U.S. Census Bureau, "Selected Social Characteristics in the United States," 2021. American Community Survey, ACS 5-Year Estimates Data Profiles, Table DP02, 2021, accessed on December 5, 2023, [https://data.census.gov/table/ACSDP5Y2021.DP02?g=040XX00US06](https://data.census.gov/table/ACSDP5Y2021.DP02?g=040XX00US06).&#x20;

\[43] U.S. Department of Veterans Affairs, “VetPop2020 State Estimates 2000 to 2020,” updated on April 6, 2023, Retrieved December 2024 from [https://www.data.va.gov/dataset/VetPop2020-State-Estimates-2000-to-2020/fkjq-z6m8](https://www.data.va.gov/dataset/VetPop2020-State-Estimates-2000-to-2020/fkjq-z6m8).

\[44] U.S. Census Bureau, 2017-2021 American Community Survey 5-Year Estimates, “2021 Educational Attainment, California Estimates, Population 25 Years and Over”, Table S1501: [https://data.census.gov/table/ACSST5Y2021.S1501?q=S1501\&g=040XX00US06\&y=2021](https://data.census.gov/table/ACSST5Y2021.S1501?q=S1501\&g=040XX00US06\&y=2021).

[^1]: 2019 estimate from Estimates of Undocumented and Eligible-to-Naturalize Populations by State, Center for Migration Studies, [http://data.cmsny.org/state.htm](http://data.cmsny.org/state.htm)l.

[^2]: U.S. Census Bureau, " SELECTED CHARACTERISTICS OF THE NATIVE AND FOREIGN-BORN POPULATIONS," 2022. American Community Survey, ACS 5-Year Estimates Subject Tables, Table S0501, 2022, accessed on December 11, 2023, [https://data.census.gov/table/ACSST5Y2022.S0501?q=S0501](https://data.census.gov/table/ACSST5Y2022.S0501?q=S0501).

[^3]: U.S. Department of Homeland Security. (2022, September). September 2022 Population estimates of the Lawful Permanent Resident Population in the United States and the Subpopulation Eligible to Naturalize: 2022. dhs.gov [https://www.dhs.gov/sites/default/files/2022-10/2022\_0920\_plcy\_lawful\_permenent\_resident\_population\_estimate\_2022\_0.pdf](https://www.dhs.gov/sites/default/files/2022-10/2022_0920_plcy_lawful_permenent_resident_population_estimate_2022_0.pdf).

[^4]: U.S. Department of Homeland Security, Office of Homeland Security Statistics, “Population Estimates of Nonimmigrants Residing in the United States: Fiscal Years 2017-2019” May 2021, Retrieved June 2, 2025, from [https://ohss.dhs.gov/sites/default/files/2023-12/ni\_population\_estimates\_fiscal\_years\_2017\_-\_2019v2.pdf](https://ohss.dhs.gov/sites/default/files/2023-12/ni_population_estimates_fiscal_years_2017_-_2019v2.pdf).

[^5]: U.S. Department of Homeland Security, Office of Homeland Security Statistics, “Refugees and Asylees: 2020” Annual Flow Report for Fiscal Year 2020. March 2022, [Retrieved June 2](file:///C:/Users/daggarwa/AppData/Local/Microsoft/Windows/INetCache/Content.Outlook/P0BIF5U8/Retrieved%20June%202), 2025, from [https://ohss.dhs.gov/sites/default/files/2023-12/2022\_0308\_plcy\_refugee\_and\_asylee\_fy2020v2.pdf](https://ohss.dhs.gov/sites/default/files/2023-12/2022_0308_plcy_refugee_and_asylee_fy2020v2.pdf).&#x20;

[^6]: U.S. Census Bureau, Census Datasets on income topics,[ (census.gov)](https://www.census.gov/data/datasets.html)

[^7]: U.S. Bureau of Labor Statistics, [Occupation Finder: Occupational Outlook Handbook (bls.gov)](https://www.bls.gov/ooh/occupation-finder.htm)



    California Employment Development Department, California Open Data Portal datasets, [https://data.ca.gov/organization/california-employment-development-department](https://data.ca.gov/organization/california-employment-development-department)&#x20;

[^8]: Department of Health Care Access and Information, Health Care Payments Data Snapshot “Data Overview – Count of Individuals by Payer Type”, [https://hcai.ca.gov/visualizations/healthcare-payments-data-hpd-snapshot/](https://hcai.ca.gov/visualizations/healthcare-payments-data-hpd-snapshot/)



    Department of Health Care Access and Information, Report to the Legislature “Program Report: Health Care Payments Data Program”, May 2024, [https://hcai.ca.gov/wp-content/uploads/2024/04/HPD-Report-to-the-Legislature-March-2024-1.pdf](https://hcai.ca.gov/wp-content/uploads/2024/04/HPD-Report-to-the-Legislature-March-2024-1.pdf)

[^9]: U.S. Census Bureau, “About Program Income and Public Assistance,” (2025) [https://www.census.gov/topics/income-poverty/public-assistance/about.html](https://www.census.gov/topics/income-poverty/public-assistance/about.html), Accessed March 25, 2025

[^10]: [https://studentaid.gov/help/means-tested-benefits](https://studentaid.gov/help/means-tested-benefits)

[^11]: California Department of Social Services. CalFresh Dashboard. [https://public.tableau.com/app/profile/california.department.of.social.services/viz/CFdashboard-PUBLIC/AnnualParticipation](https://public.tableau.com/app/profile/california.department.of.social.services/viz/CFdashboard-PUBLIC/AnnualParticipation). 2025. Accessed March 25, 2025.

[^12]: California Department of Social Services. CalWORKs Take up. CalWORKs Interactive Summary. [https://www.cdss.ca.gov/inforesources/calworks-summary/program-overview/take-up#C018](https://www.cdss.ca.gov/inforesources/calworks-summary/program-overview/take-up#C018). 2025. Accessed March 25, 2025.

[^13]: California Department of Social Services. Housing Support Program. CalWORKs Interactive Summary. [https://www.cdss.ca.gov/inforesources/calworks-summary/program-services-utilization/housing-and-homelessness#C004](https://www.cdss.ca.gov/inforesources/calworks-summary/program-services-utilization/housing-and-homelessness#C004). 2025. Accessed March 25, 2025

[^14]: U.S. Census Bureau, 2020 Census ”Urban and Rural” Classifications, [https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html](https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html)

[^15]: National Rural Health Association, “Definition of Frontier”, Retrieved June 2, 2025, from [https://www.ruralhealth.us/getmedia/132306e1-1643-4b40-818a-4d743317dc7e/NRHAFrontierDefPolicyPaperFeb2016.pdf](https://www.ruralhealth.us/getmedia/132306e1-1643-4b40-818a-4d743317dc7e/NRHAFrontierDefPolicyPaperFeb2016.pdf) &#x20;



    U.S. Department of Agriculture Economic Research Service, ”Frontier and Remote Area Codes”, Retrieved June 2, 2025, from [https://www.ers.usda.gov/data-products/frontier-and-remote-area-codes](https://www.ers.usda.gov/data-products/frontier-and-remote-area-codes)

[^16]: United States Census Bureau, Geography Program Glossary, [https://www.census.gov/programs-surveys/geography/about/glossary.html#:\~:text=Census%20Tract,-Census%20Tracts%20are\&text=The%20primary%20purpose%20of%20census,optimum%20size%20of%204%2C000%20people.](https://www.census.gov/programs-surveys/geography/about/glossary.html)

[^17]: Department of Health Care Access and Information, “Facility Market Share and Patient Origin” Reports, Retrieved June 2, 2025, from [https://hcai.ca.gov/visualizations/facility-market-share-and-patient-origin/](https://hcai.ca.gov/visualizations/facility-market-share-and-patient-origin/)
