# B. The HIPAA De-Identification Standard

The Center for Data Insights and Innovation (CDII) is authorized by state statute to coordinate and monitor HIPAA compliance by all California State entities within the executive branch of government covered or impacted by HIPAA. One difference between the California IPA and HIPAA is the documentation requirement in HIPAA for data de-identified using the Expert Determination method.&#x20;

The HIPAA Standard <sup>\[1]</sup> for de-identification of protected health information (PHI)<sup>\[2]</sup> states “Health information that does not identify an individual and with respect to which there is no reasonable basis to believe that the information can be used to identify an individual is not individually identifiable health information.” If the data are de-identified, and it is not reasonably likely that the data could be re-identified, the Privacy Rule no longer restricts the use or disclosure of the de-identified data.

The following is quoted from the “Guidance Regarding Methods for De-Identification of Protected Health Information in Accordance with the Health Insurance Portability and Accountability Act (HIPAA) Privacy Rule”, published November, 2012 by the U.S. Department of Health & Human Services, Office for Civil Rights: ([https://www.hhs.gov/ocr/privacy/hipaa/understanding/coveredentities/De-identification/guidance.html](https://www.hhs.gov/ocr/privacy/hipaa/understanding/coveredentities/De-identification/guidance.html))&#x20;

### 1.1        The HIPAA De-Identification Standard <a href="#toc196116310" id="toc196116310"></a>

Section 164.514(a) of the HIPAA Privacy Rule (45 CFR) provides the standard for de-identification of protected health information. Under this standard, health information is not individually identifiable if it does not identify an individual and if the covered entity has no reasonable basis to believe it can be used to identify an individual.

§ 164.514 Other requirements relating to uses and disclosures of protected health information.

(a) _Standard: de-identification of protected health information._ Health information that does not identify an individual and with respect to which there is no reasonable basis to believe that the information can be used to identify an individual is not individually identifiable health information.

Sections 164.514(b) and(c) of the Privacy Rule contain the implementation specifications that a covered entity must follow to meet the de-identification standard. As summarized in Figure 7, the Privacy Rule provides two methods by which health information can be designated as de-identified.

Figure 7. Two methods to achieve de-identification in accordance with the HIPAA Privacy Rule.

_The first is the “Expert Determination” method:_

§ 164.514(b) _Implementation specifications: requirements for de-identification of protected health information._ A covered entity may determine that health information is not individually identifiable health information only if:

(1) A person with appropriate knowledge of and experience with generally accepted statistical and scientific principles and methods for rendering information not individually identifiable:

(i) Applying such principles and methods, determines that the risk is very small that the information could be used, alone or in combination with other reasonably available information, by an anticipated recipient to identify an individual who is a subject of the information; and

(ii) Documents the methods and results of the analysis that justify such determination; or

_The second is the “Safe Harbor” method:_

(2)(i) The following identifiers of the individual or of relatives, employers, or household members of the individual, are removed:

(A) Names

(B) All geographic subdivisions smaller than a state, including street address, city, county, precinct, ZIP code, and their equivalent geocodes, except for the initial three digits of the ZIP code if, according to the current publicly available data from the Bureau of the Census:

(1) The geographic unit formed by combining all ZIP codes with the same three initial digits contains more than 20,000 people; and

(2) The initial three digits of a ZIP code for all such geographic units containing 20,000 or fewer people is changed to 000

(C) All elements of dates (except year) for dates that are directly related to an individual, including birth date, admission date, discharge date, death date, and all ages over 89 and all elements of dates (including year) indicative of such age, except that such ages and elements may be aggregated into a single category of age 90 or older

(D) Telephone numbers

(E) Fax numbers

(F) Email addresses

(G) Social security numbers

(H) Medical record numbers

(I) Health plan beneficiary numbers

(J) Account numbers

(K) Certificate/license numbers

(L) Vehicle identifiers and serial numbers, including license plate numbers

(M) Device identifiers and serial numbers

(N) Web Universal Resource Locators (URLs)

(O) Internet Protocol (IP) addresses

(P) Biometric identifiers, including finger and voice prints

(Q) Full-face photographs and any comparable images

(R) Any other unique identifying number, characteristic, or code, except as permitted by paragraph (c) of this section \[Paragraph (c) is presented below in the section “Re-identification”]; and

(ii) The covered entity does not have actual knowledge that the information could be used alone or in combination with other information to identify an individual who is a subject of the information.

Satisfying either method would demonstrate that a covered entity has met the standard in §164.514(a) above. De-identified health information created following these methods is no longer protected by the Privacy Rule because it does not fall within the definition of PHI. Of course, de-identification leads to information loss which may limit the usefulness of the resulting health information in certain circumstances. As described in the forthcoming sections, covered entities may wish to select de-identification strategies that minimize such loss.

Re-identification

The implementation specifications further provide direction with respect to re-identification, specifically the assignment of a unique code to the set of de-identified health information to permit re-identification by the covered entity.

§ 164.514 (c) Implementation specifications: re-identification. A covered entity may assign a code or other means of record identification to allow information de-identified under this section to be re-identified by the covered entity, provided that:

(1) Derivation. The code or other means of record identification is not derived from or related to information about the individual and is not otherwise capable of being translated so as to identify the individual; and

(2) Security. The covered entity does not use or disclose the code or other means of record identification for any other purpose, and does not disclose the mechanism for re-identification.

If a covered entity or business associate successfully undertook an effort to identify the subject of de-identified information it maintained, the health information now related to a specific individual would again be protected by the Privacy Rule, as it would meet the definition of PHI. Disclosure of a code or other means of record identification designed to enable coded or otherwise de-identified information to be re-identified is also considered a disclosure of PHI.

<br>

&#x20;

### 1.2        Expert Determination Template <a href="#toc196116311" id="toc196116311"></a>

HIPAA covered entities in CalHHS must de-identify data in compliance with the HIPAA standard. Under the HIPAA standard, either Safe Harbor or Expert Determination must be used. If Expert Determination is used then the documentation of the review is essential. The following may serve as a template for this documentation with the reference to the CalHHS DDG to support the analysis documented.

Documentation of Expert Determination Template

Name of Report:

Reason for Data Release:

Identify why the data release does not meet Safe Harbor. For example:

The request does not meet the Safe Harbor standard because it includes counts by county (geographic area smaller than the state) or counts by month (which does not meet the criteria for dates). Therefore, the steps in the CalHHS DDG are being used to assess the tables.

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">Document how the conditions of each step are met or not met</td><td valign="top">Result</td></tr><tr><td valign="top"><p>Step 1 – Presence of Personal Characteristics</p><p><em>Summary:</em> </p><p> </p></td><td valign="top"> </td></tr><tr><td valign="top"><p>Step 2 – Numerator Denominator Condition</p><p><em>Summary:</em> </p><p> </p></td><td valign="top"> </td></tr><tr><td valign="top"><p>Step 3 – Assess Potential Risk</p><p><em>Summary:</em> </p><p> </p></td><td valign="top"> </td></tr><tr><td valign="top"><p>Step 4 – Statistical Masking</p><p><em>Summary:</em> </p><p> </p></td><td valign="top"> </td></tr><tr><td valign="top"><p>Step 5 – Expert Review</p><p><em>Summary:</em> </p><p><em>“Risk is very small that the information could be used, alone or in combination with other reasonably available information, by an anticipated recipient to identify an individual who is a subject of the information”</em></p></td><td valign="top"> </td></tr></tbody></table>

<br>

***

\[1] The Standard is found in the HIPAA Privacy Rule, 45 CFR section 164.514(a).

\[2] “PHI” is defined as information which relates to the individual’s past, present, or future physical or mental health or condition, the provision of health care to the individual, or the past, present, or future payment for the provision of health care to the individual, and that identifies the individual, or for which there is a reasonable basis to believe can be used to identify the individual. (45 CFR section 160.103)
