---
icon: circle-6
---

# Play 6: Describe

<figure><img src="../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

## Play 6: Describe Your Data

In this Play, your data team utilizes the metadata repository created in _Play 5: Establish Your Metadata Repository_ and the dataset prioritization established in _Play 4: Prioritize Your Data_ to improve the usability of your data. By executing this Play, dataset individual fields/attributes are elaborated with the following types of information:

* Business descriptions
* Technical characteristics
* Security classifications
* Citations to governing statutes

This Play guides creating metadata for databases. The provided metadata elaboration approach also applies to describing attributes in Application Program Interfaces (APIs) and other datasets. If your improvement effort includes API-based data-sharing, the supplemental section _Describing Application Program Interfaces_ provides an overview of API standards and development processes to keep your API descriptors current.

### Play 6.1 Secure Needed Staff Resources <a href="#play_6.1_secure_needed_staff_resources" id="play_6.1_secure_needed_staff_resources"></a>

The roles and responsibilities required to complete this Play vary by department. For example, the role of your department’s information security team may guide your effort by providing data classification criteria, or they may want to be more directly involved in the effort. Additionally, the staff roles that coordinate with your legal team may vary. A sample of required staff are listed below and depicted in the following diagram:

* Information technology (e.g., Database Administrators) creates the baseline list of data elements and their technical characteristics.
* Business and data analysts to create business definitions and interpret security classifications, and statute references.
* Program staff to provide background and clarifications to create business definitions.
* Information security to support creating data classifications.
* Access to legal teams to provide guidance on statutes that govern data-sharing. Your department’s staff roles and practices may vary from the list above.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption><p>Populating Your Metadata Repository</p></figcaption></figure>

#### **Engage Required Staff Resources**

You can use the following approaches to engage the needed teams:

* Leverage the executive and team buy-in garnered by completing _Play 3: Create a Business Case._
* Define a specific scope (e.g., Dataset) and schedule that accommodates staff resource constraints.
* Inform participating staff of the benefits for your department’s analytics, information technology, and security teams.
* Demonstrate results through an incremental metadata collection effort to sustain support for the effort.

Participating staff and team management may have concerns about impacts on their regular job duties. Jointly develop a schedule with the staff supporting the effort that maintains progress while incorporating the availability of required staff.

#### Play 6.1 Vignette: The CDW Data-Sharing Team is Assembled

With the first dataset selected by department management and stakeholders, Sally starts the effort to expand the Walk to Work (W2W) metadata. Sally meets with Carlos to develop a high- level plan to collect the W2W metadata and identify the staff roles needed for the effort.

Sally meets with her coach, Ann, for advice on engaging these teams in the effort. Ann suggests that Sally ask the W2W program manager to email the teams to engage their support by summarizing the following:

* The effort is focused on the W2W data to manage scope.
* Specific staff needs and anticipated timeline.
* Benefits to the W2W and improved ability for inter-department data-sharing with the Healthy Habits programs.
* Benefits to the department.
* The approach that incrementally improves metadata based on staff availability.

Sally reviews the notes she and Carlos created during the prioritization effort conducted in _Play 4: Prioritize Your Data_ and the business case created in _Play 3: Create a Business Case_ to summarize the program and department benefits of the effort. She also uses the technical and security benefits from the Guidebook’s supplemental section _Benefits to Your Department by Executing the Plays_ to incentivize CDW team participation.

Sally’s previous work with the CDW program managers and information technology team has established the context for the effort and established relationships to help secure staff resources.

Sally meets with the W2W program manager to explain the requirement for program staff support for this phase of the effort. She requests the assistance of a business analyst to create business definitions and security classifications. Her request also includes access to a program specialist to assist when additional business context is required to create business definitions.

Sally works with CDW executive leadership to send a communication to the CDW information technology and legal departments to secure their support for the effort. Sally drafts an email that includes the points above for transmission by executive management.

Sally will schedule a kickoff meeting to ready the individual team members to review objectives, scope, and the metadata collection process in the Play 6.2 vignette.

### Play 6.2: Collect Your Metadata <a href="#play_6.2-_collect_your_metadata" id="play_6.2-_collect_your_metadata"></a>

With your team assembled, it’s time to start populating your metadata repository created in _Play 5: Establish Your Metadata Repository._ The diagram on the following page depicts the flow of technical, business, security, and legal metadata collection:

<figure><img src="../../.gitbook/assets/image%20(11).png" alt=""><figcaption><p>Metadata Collection Flow</p></figcaption></figure>

**Establish Your Data Element Baseline**

The first step is to create your baseline of data elements to later addition of business definitions, security classifications, and statute citations. This serves as your inventory of data elements to enrich with business definitions, security classifications, and statute citations.

If your department has a data catalog tool, you can use features to auto-discover and populate this information. The supplemental section _Example Metadata Repository Tools_ provides an overview of data catalog and metadata repository tools.

If you don’t have a catalog tool, don’t worry. You can extract this information from most database platforms using SQL queries. The vignette in _Play 5: Establish Your Metadata Repository_ provided an example of this approach.

With the baseline list of fields in place, it is time to start creating business definitions.

**Create Business Definitions**

Understanding the meaning of data elements (e.g., Database Fields) is crucial to accurately consuming data and creating analytics. Misunderstanding data meanings can compromise the results of business rules and calculations. If recipients cannot interpret your data’s meaning, they will need to send clarification inquiries that slow down their analytics efforts and utilize your staff’s time. Business definitions are also required to create security classifications and identify governing statutes.

Field definitions and a supporting business glossary inform data recipients and your internal teams of the meaning of your data. Creating effective data definitions is a vital part of your metadata collection efforts. Your department is investing time and staff resources into the metadata collection effort. To fully realize the benefits of your data catalog, definitions need to be clear and useable to persons not familiar with your department’s unique terms.

Not everyone on your metadata collection team may be familiar with the practice of creating data definitions. For example, program staff may not have previous experience creating data definitions if they are not already incorporated into system design processes. Providing guidance and training to the team promotes consistency of your data definitions.

The Guidebook supplemental section _Creating Effective Data Element Definitions_ provides the following to help your team create effective data definitions:

* Data Glossary examples and a sample template.
* Characteristics of effective field definitions.
* A method to practice and build field definition skills.
* An approach to training your team on creating field definitions.

Even if you have previous experience creating field definitions, we recommend reviewing the _Creating Effective Data Element Definitions_ supplemental section as a tool to train your fellow team members.

**Evaluate Applicable Data Standards**

Using an existing data standard to describe your data improves understanding of data elements; data recipients who are already familiar with a data standard will more quickly be able to interpret shared data. Additionally, incorporating an existing data standard may save time describing your data by leveraging existing descriptions and limiting data definition creation to California program-specific data elements.

Examples of existing data standards are provided in the table below:

|         Domain         |                                                                                                                                                                                                                                                         Standard                                                                                                                                                                                                                                                        |                                                                                                                                      Summary                                                                                                                                     |
| :--------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|       Health Care      | <p><a href="https://www.healthit.gov/isa/united-states-core-data-interoperability-uscdi">United States Core Data for Interoperability</a> <a href="https://www.healthit.gov/isa/united-states-core-data-interoperability-uscdi">(USCDI)</a><br><br><br><br><br><a href="https://github.com/HEAL/heal-metadata-schemas/tree/main/for-investigators-how-to">Helping to End Addiction Long-</a> <a href="https://github.com/HEAL/heal-metadata-schemas/tree/main/for-investigators-how-to">term® (HEAL) Initiative</a></p> | <p>The USCDI is a standardized set of health data classes and constituent data elements for nationwide, interoperable health information exchange.<br><br>Provides a set of standard definitions focused on opioid addiction that can be adapted for other types of studies.</p> |
| General Human Services |                                                                                                                                                        Administration for Children, Youth and Families (ACYF) [Information Exchange](https://www.acf.hhs.gov/niem-human-service-domain-iepds) [Packets](https://www.acf.hhs.gov/niem-human-service-domain-iepds)                                                                                                                                                        |                          ACYF is creating a set of data structures with definitions for the programs it administers. The Information Exchange Packets are in the National Information Exchange Format (NIEM) and can be used as a source of definitions.                         |

Data standards are widely available in the health data domain. Other data domains are more limited but are expanding. For example, the ACYF Information Exchange Package Documentation (IEPD) is currently developing [draft Exchange Packages](https://www.acf.hhs.gov/archive/process-information-exchange-packet-documentation-iepd) that may be available in the future to help describe your data in the future.

Given the benefits of understanding and time savings, it is worth investing time to identify an existing data standard that applies to your programs.

#### **Identify Related Statutes**

Your department’s programs are likely subject to State and Federal statutes beyond broad- reaching legislation such as the Health Insurance Portability and Accountability Act (HIPAA). Some examples of governing statutes that impact data sharing include the following:

* California Welfare Institution Codes (WIC) and Other California Codes
* California-Specific Health and Privacy Laws
* Federal Code of Federal Regulations (CFR)

The Department of Health Care Services [CalAIM Data Sharing Authorization Guidance](https://www.dhcs.ca.gov/CalAIM/ECM/Documents/CalAIM-Data-Sharing-Authorization-Guidance.pdf) provides an example of data-sharing guidance incorporating state and federal-level statutes governing data-sharing.

Governing statutes can impact data-sharing, including:

* Use of the data
* Restrictions on data granularity (e.g., Individual Person Records)
* Requirements for enhanced security controls

Early awareness of the relevant statutes mitigates delays during BUCP creation, approval, and fulfillment. For example, detecting governing statutes late in the BUCP process may cause a re- evaluation of security and data usage approvals. A complete list of governing statutes helps address the following BUCP fields:

* Creating a Use Case that specifically links data-sharing and program purposes.
* Legal Authority for the data provider to share the data and recipients to access data.
* Identifying and establishing an agreement to address the contents of the BUCP

#### Specialized Security and Specialized Privacy fields.

A comprehensive list of governing statutes can also address constraints on data-sharing while addressing business objectives. For example, awareness of restrictions on releasing person- level records may help illuminate alternatives, such as the data provider creating aggregated or cohort-level data. A comprehensive list of governing statutes also may help identify applicable statutes affecting linked data combined from multiple programs that have differing governing statutes.

Your information security and legal departments should provide guidance on the applicable statutes and codes that govern data sharing. The Center for Data Insights and Innovations provides publications to assist in the identification of governing statutes and codes, including:

* [State Health Information Guidance (SHIG)](https://www.cdii.ca.gov/compliance-and-policy/state-health-information-guidance-shig/)
* [Statewide Health Information Policy Manual (SHIPM)](https://www.cdii.ca.gov/compliance-and-policy/statewide-health-information-policy-manual-shipm/shipm-documents/)

Your metadata repository is a tool that provides visibility of the program-specific statutes and codes that govern requested data.

As data is requested, you can run reports to identify relevant statutes early in the BUCP process to address data-sharing requirements proactively. The list of statutes from your metadata repository helps determine requirements and restrictions for incorporation into the initial BUCP formulation. As noted previously, early awareness also helps gain required legal interpretations in the early phase of the BUCP process and opportunities to identify solutions to data-sharing restrictions.

Your metadata repository created in _Play 5: Establish Your Metadata Repository_ included attributes that create traceability to relevant statutes and codes. You can work with your legal and information security teams to classify data during your metadata collection effort. Be sure to classify data with sufficient specificity to correctly identify governing requirements, including [sections, subdivisions, paragraphs, and subparagraphs.](https://californiaglobe.com/fr/using-the-correct-reference-in-california-bills-and-statutes/)

#### **Classify Your Data**

Maintaining data classifications associated with your data elements is an input to identifying restrictions and required security controls when sharing data. As with statute citations, you can run reports from your metadata repository to identify the security classifications of requested data to initiate security approvals and security control identification early in the BUCP process.

The business definitions you previously created provide context to help identify or update classifications for data elements. Work with your information security team to identify the types of security classifications and establish a methodology for your metadata collection team to classify data. One approach is to create a set of evaluations to use for each data element to identify Personally Identifiable Information (PII) and Protected Health Information (PHI). You will want to create data classifications iteratively for each of your data sets and systems.

Some data catalog tools provide suggestions for data classifications based on field names and definitions. These suggestions still require a data security expert to review the data elements.

Your next Play is establishing data management processes to help you maintain your metadata.

#### Play 6.2 Vignette: CDW Collects Its Metadata

Sally schedules a kick-off meeting with the team members collecting and creating the W2W metadata. The team is composed of the following staff:

* Carlos, the department's data architect, will coordinate the creation of the baseline of data elements and technical characteristics from the W2W database.
* Samantha is one of the business analysts from the W2W program. She will create business definitions and coordinate with legal to identify governing statutes. She will also be supported by Angelica, the W2W program specialist, with definitions that need clarification.
* Linda is a CDW data analyst. She works with Samantha to create business definitions. She is also the primary team member creating data classifications using criteria provided by the CDW information security team. As needed Linda confers with the CDW Information Security Officer, to verify the accuracy of data classifications.

During the kick-off, Sally reviewed the same summary of objectives and benefits sent to the team members' managers in the _Play 6.1: Secure Needed Staff Resources_ vignette. She reviews the flow of metadata collection. Carlos will use the W2W database to extract the baseline set of data elements. Samantha will the help of Linda will create business definitions.

As the business definitions are created, Samantha will create legal citations, and Linda will designate data classifications. The team will use communication features in Microsoft Teams and Excel (e.g., Comments, Tasks) to coordinate with one another.

Samantha has not created business definitions before. Linda regularly uses metadata while creating analytics, but she has not created definitions before. To enable the team, Sally schedules a training workshop on creating effective data definitions. She uses the approach provided in the Guidebook’s supplemental section, _Creating Effective Data Element Definitions,_ for staff training.

Carlos starts the effort by having one of his database administrators extract the data elements. The data elements are extracted into an Excel file stored in Microsoft Teams. This process was reviewed in the _Play 5: Create Your Metadata Repository_ vignette.

Samantha and Angelica begin the effort to create business definitions for the data element. The database has some existing definitions that are verified to ensure they are still current. They determine business meaning by:

* Previous experience working with the W2W system and analytics.
* Analyzing how data is entered into the W2W system’s user interface.
* Reviews of design documentation.
* Analyzing training documents.
* Consulting with the W2W program specialist.

Sally has already established an agreement with the CDW IT team to support the collection of data definitions. Technology staff are available for assistance with identifying how the W2W system uses data elements.

Linda reviews the data elements in the metadata repository and uses the business definitions to designate security classifications. Linda reviews data elements and their business definitions to determine if they contain information including:

* Personally Identifiable Information (PII)
* Protect Health Information (PHI)
* Other Sensitive Information

In parallel, Samantha reviews the data elements for governing statutes. Tagging the data elements helps the CDW identify restrictions or the ability to share certain data with other programs. She reviews the [State Health Information Guidance (SHIG)](https://www.cdii.ca.gov/compliance-and-policy/state-health-information-guidance-shig/) for any relevant guidance. Samantha and Angelica also coordinate with legal to identify governing statutes.

As batches of metadata definitions are fully defined with business definitions and security reviews are complete, Carlos loads the definitions into the CDW database used as a metadata repository. This process was reviewed in the _Play 5: Establish Your Metadata Repository_ vignette.

### Play 6.3: Keep Your Metadata Repository Current <a href="#play_6.3-_keep_your_metadata_repository" id="play_6.3-_keep_your_metadata_repository"></a>

Your department just invested staff resources to create and populate your metadata repository. To maintain its value and realize your department’s investment it’s important to keep your metadata repository. The best way to keep your metadata repository current is to update it as your systems change.

A good practice is to integrate updating your metadata into your system development processes. This can be accomplished through the following design and development processes:

* Establish data element definitions, security classifications, and statute citations during functional design.
* Add metadata to your repository as your database or API development team creates system changes.
* Verify metadata is in place through peer reviews and/or your development team’s Definition of Done.

Instruct data consumers such as your data analysts to report missing or unclear metadata (e.g., business definitions) to your data management team.

The vignette for this play provides an example of working with your department’s development team to establish processes to capture metadata as systems change.

#### Play 6.3 Vignette: Establish Metadata Management Processes

Sally schedules a retrospective with the metadata collection team to identify ways to improve efforts to expand the information available for additional CDW datasets. Sally is the facilitator, so other team members can focus on providing their perspectives. The key themes identified by the team are:

* Collecting metadata for many attributes was initially daunting for the team.
* The team had to research data element usage and meaning to create definitions.
* Sometimes, the security team was waiting on definitions to create security classifications accurately.

In the second half of the retrospective, Sally asks the team for their thoughts on addressing these challenges. Daniel, a W2W business analyst, frequently had to review the W2W requirements and design documents to create data definitions. He stated that when creating system designs, they have the information needed to define data elements, but it is inaccessible to data recipients.

Daniel’s point about the source of requirements spurs a thought from Andrea, on how to solve the seemingly overwhelming retroactive effort undertaken by the team. Andrea suggests that the CDW modify their system development processes to incrementally define attributes as the department’s system changes. Defining data during system development provides benefits to the CDW, including:

* Metadata is defined without research; the information needed is already integral to the design process.
* The team can classify data before development; this helps with data-sharing and helps the information security team identify any new security controls.
* The effort is incremental to avoid placing a significant effort on the team.
* The CDW can integrate this into the development processes for the department’s other systems to start the metadata elaboration effort with little investment.

The retrospective was very effective as it provided insights and opportunities. Andrea volunteers to create a plan on how the CDW can incrementally capture its metadata.

Andrea meets with her team leads to review the findings and recommendations from the metadata collection retrospective. They decide to recommend the following practices:

* The CDW business analyst will provide business definitions as part of the system design; this information will now before a design is deemed ready for development.
* Database requirements and specifications will include a definition created by the business analyst. The definition is part of the entrance criteria for a requirement or user story (Definition of Ready) before database development begins.
* The CDW database team will include the definition when making database structure changes.

The new CDW design, development, and documentation process they will follow is depicted in the graphic below:

<figure><img src="../../.gitbook/assets/image (2) (1) (1) (1).png" alt=""><figcaption><p>CDW Process to Keep Metadata Current</p></figcaption></figure>

The changes to the CDW process avoid the mass metadata collection effort the team conducted in _Play 6.2: Collect Your Metadata_ by incrementally collecting metadata during design and development. This new process saves time since the information to create metadata is already in hand during system design. Additionally, the process creates complete and accurate metadata through a closed loop between design and development.
