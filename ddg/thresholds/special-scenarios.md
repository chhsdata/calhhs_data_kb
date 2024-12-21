# Special Scenarios

### Data with More Specificity

Specific diagnosis and procedure codes have higher risk of identification because of their unique nature. Thus, these diagnosis and procedure codes should be scored based on “Other Variables” in Section 6.2.

Some examples of data with more specificity include:

* Specific ICD codes for surgical procedures: Bariatric surgery (Z98. 84) \[Examples of specific bariatric procedures: Open Roux-en-Y (0D160ZB), Laparoscopic Roux-en-Y (0DB64Z3), Laparoscopic Sleeve Gastrectomy (0DB64Z3), Biliopancreatic Diversion with Duodenal Switch (BPD/DS) (0DB60Z3+0D160ZB+0D194ZB), Adjustable Gastric Lap Band (Z46. 51), Single Anastomosis Duodeno-ileal Bypass with Sleeve Gastrectomy(0D16079)] \[i,ii, iii\[A1] ].
* Specific diagnoses: Disability \[Complete Paraplegia G82.21], birth defects \[e.g., Cleft Palate (Q35. 9)], neurological disorders \[e.g., Dyslexia and alexia (R48.0), Cerebral Palsy (G80. 9)], and End stage renal disease (N18.6).
* Specific procedure codes: Transcranial doppler ultrasound (CPT code 93886 or 93971), Sickle cell screening (Z 13.0 or D57. 1).

### High-Risk Populations which require suppression of counts <11 regardless of score

911 calls and court records are considered public information. Therefore, a large amount of information is publicly available about individuals who interact with emergency services or the justice system, including identifying information such as name, gender, date of birth, age, and, when applicable, the location of where the patient is currently housed or is committed to. Examples of populations that interact with emergency services or the justice system include people with: substance use disorder, serious mental illnesses (SMI), persons with psychological or emotional trauma, children in foster care, people living without homes, victims of crime, incarcerated people,developmentally disabled people\[A2] \[A3] , and immigrants who are undocumented. Therefore, for these populations, suppression of counts less than 11 is always required regardless of their underlying population.

Note that most of the demographic variables are assigned risk scores that are consistent with those of Table 2. However, the above-mentioned high-risk populations have been exempted from this requirement due to the higher potential visibility of these individuals in public information (e.g., from police reports or news reports) that inherently increases risk of re-identification that is a risk that is not otherwise accounted for with the scoring criteria.

Some examples of the above include:

* SUD: medication assisted treatment services, prescription opioid misuse, other illicit drugs use
* SMI: schizophrenia, schizoaffective disorders, bipolar disorder, unspecified psychosis not due to a substance or known physiological condition, paraphilias, personality disorders, major depressive disorders, delusional disorders, stimulant related disorders, delusional disorders, post-traumatic stress disorder
* Claims for emergency transport

### Re-Identification Risk with Increased Granularity

Sometimes, we may be asked to provide more granular data. However, increasing the number of demographic attributes or providing additional variables to achieve this,\[1] \[2] \[3] increases the risk that the unique combination of variables can effectively re-identify an individual.

If the expert determines that the provided information could be used, alone or in combination with other available information to identify or re-identify an individual, then the data should not be released. Instead, an alternative method that protects the privacy of individuals should be used to provide the requester with the data they need.

***

\[1] Sweeney, “Uniqueness of Simple Demographics in the U.S. Population”, LIDAPWP4. Carnegie Mellon University, Laboratory for International Data Privacy, Pittsburgh, PA, 2000.

\[2] Golle, “Revisiting the Uniqueness of Simple Demographics in the US Population”, Accessed [from stanford.edu](https://crypto.stanford.edu/~pgolle/papers/census.pdf): [https://crypto.stanford.edu/\~pgolle/papers/census.pdf](https://crypto.stanford.edu/~pgolle/papers/census.pdf)

\[3] Rocher, et al. “Estimating the success of re-identifications in incomplete datasets using generative models”, Nat Commun 10, 3069 (2019). [https://doi.org/10.1038/s41467-019-10933-3](https://doi.org/10.1038/s41467-019-10933-3)
