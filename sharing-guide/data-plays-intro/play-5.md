---
icon: circle-5
---

# Play 5: Metadata

<figure><img src="../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

## Play 5: Establish Your Metadata Repository

For data to be valuable, it must be understandable by data consumers and your internal teams. [Metadata](https://en.wikipedia.org/wiki/Metadata) or “data that provides information on other data1” provides the [technical, business,](https://www.linkedin.com/pulse/business-technical-metadata-luca-de-ioanna/) and [security](https://linfordco.com/blog/what-is-data-classification-levels-compliance/) information needed for consumers to work with your data. Metadata also provides input to complete the BUCP Technical Fields and support analysis for the Specialized Security and Specialized Privacy fields. Metadata contains the following types of information:

* Business Definitions
* Technical Information
* Security Classification
* Governing Statutes

The term “metadata” may not be familiar to your data consumers. When explaining the purpose of your metadata repository it may be more effective to use common language terms or descriptions such as “data definitions” in place of “metadata”.

This diagram depicts your metadata repository and its consumers across your department’s various teams:

<figure><img src="../../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

**Metadata Repository Consumers**

Typically, metadata is stored in a repository and presented to data consumers in the form of a data dictionary. A data dictionary helps data recipients, such as departments receiving your data, understand the meaning of individual data elements.

Once your metadata repository is populated, you will have a data dictionary for data consumers to understand the meaning of individual data elements and support the following components of BUCPs:

* The content for the Technical Fields section.
* List of governing security statutes for analysis to complete the Specialized Security and Privacy Fields.
* List of governing statutes to understand data sharing requirements and limitations.

Your metadata repository also provides direct benefits to your department that are listed below and elaborated in the Guidebook’s supplemental section _Benefits to Your Department from Executing the Plays_:

* Internal data-sharing
* System changes
* Impact assessments
* Level of effort estimates
* Internal reporting
* Verifying security controls
* API and data set reuse

We recommend launching the effort to create your metadata repository in parallel with the data prioritization effort described in _Play 4: Prioritize Your Data_. Conducting these efforts in parallel provides time for the implementation of a data catalog product or for technology teams to implement an alternate solution using an existing database.

**Describing Your Application Program Interfaces**

The techniques to improve data-sharing provided by this Guide are relevant to data stored in databases and Application Program Interfaces (API). If your data-sharing improvement effort includes API, please review the Guidebook’s supplemental section _Describing Application Program Interfaces_ for guidance on related metadata standards and practices.

### Play 5.1: Identify Metadata Requirements <a href="#play_5.1-_identify_metadata_requirements" id="play_5.1-_identify_metadata_requirements"></a>

Your first step is to identify the type of information to be captured in your dataset’s metadata. Typically, metadata is captured at the field or attribute level and includes the following types of information:

* Field Name
* Field Label
* Data Type
* Field Definition
* Valid Inputs (e.g., List of Values, Picklists)
* Source
* Security and Privacy Information (e.g., Personal Health Information (PHI) or Personally Identifiable Information (PII), Related Statutes)
* Related Governing Statutes or Codes

The attached metadata template provides an example of the types of metadata to collect. You can tailor the metadata attributes in this example spreadsheet to your department’s needs.

Collect sufficient data to convey the meaning of your data and analysis during BUCP approvals. Remove metadata attributes that are not relevant to your datasets to reduce metadata collection and maintenance efforts.

Additional examples of data dictionary templates are listed below:

* [CDT Data Dictionary Template](https://projectresources.cdt.ca.gov/wp-content/uploads/sites/50/2017/08/DataDictionaryTemplate.xlsx#a11y%3D)
* [California Open Data Publisher’s Handbook](https://docs.data.ca.gov/california-open-data-publishers-handbook/reference/data-dictionary-what-to-include)

The next step is to identify the technical platforms that store your datasets for use during your metadata repository selection process to identify technical attributes to include in your metadata repository. These are typically your department’s databases but can also include Application Program Interfaces (APIs) or datasets created by your analytics platforms. Use the dataset inventory you created in _Play 2: Identify Your Data_ to identify technology platforms.

### Play 5.2: Implement a Data Catalog and Metadata Repository <a href="#play_5.2-_implement_a_data_catalog_and_m" id="play_5.2-_implement_a_data_catalog_and_m"></a>

Depending on available resources, options to create a data catalog and metadata repository include:

* Commercially licensed software packages
* Open-source software packages
* Use a database to capture metadata
* Spreadsheets

Open-source and commercial metadata repository platforms include features for automated data element collection and web-based access. Metadata repository platforms save time in the maintenance of your data dictionary and improve access to metadata. Data catalog platforms also make it easier to manage custom metadata, including references to applicable statutes that govern data sharing. Data catalog platforms also promote the use of your data-sharing artifacts by improving access through web access and search functions.

The Guidebook supplemental section, _Example Metadata Repository Tools,_ provides examples of data catalog tools, including those available (e.g., AWS, Azure, Google) via the State of California [Off-Premises Cloud](https://cdt.ca.gov/services/off-premises-cloud/) contract vehicles.

Use the requirements you created in _Play 5.1: Identify Metadata Requirements_ to evaluate the identified options and make a platform selection. If you do not have budget or staff resources available to establish a data catalog platform, you can get started using existing tools such as your department’s databases, spreadsheets, and a collaboration platform (e.g., Microsoft Teams).

Spreadsheets avoid software license and infrastructure costs; however, they are time-intensive to maintain and use for large datasets. If funds are unavailable to support a commercial platform or host an open-source option, another strategy is to use one of your existing databases as a metadata repository. Most database platforms provide the ability to store descriptions and security classifications-based metadata. Using your database platform’s metadata features lets you:

* Integrate ongoing creation and updates of metadata into your development processes.
* Create reports for data consumers using SQL statements.
* Establish a source of metadata for Data Dictionary platforms.

Database platform metadata capabilities may only track a limited quantity of metadata fields. You will need to develop an approach to address such limitations. For example, your approach may need to combine security and legal statute references into a single field.

Later in the Play 5 vignette, we provide an example of using a database as a metadata repository.

### Play 5.3: Create a Business Glossary <a href="#play_5.3-_create_a_business_glossary" id="play_5.3-_create_a_business_glossary"></a>

Data recipients who receive your metadata may have difficulty understanding your department’s use of specific terms and specialized meanings.

A business glossary extends context and understanding of your data definitions. A business glossary defines business concepts that are required to understand your data definitions. An example of a web-based business glossary is available [here](https://www.ctc.ca.gov/commission/reports/data/data-terms-glossary/business). Your business glossary can be a worksheet in your metadata package transmitted to data recipients.

At a high level, a business glossary establishes a record of your department's or program's jargon-specific use of terms and acronyms. Some examples of items to include in your business glossary include:

* Terms specific to your department
* Specialized use of terms
* Acronyms specific to your department

You may already have the beginnings of a business glossary in your new employee onboarding library.

Spreadsheets are a simple mechanism to store your department’s business glossary if a data catalog platform is not available. A website improves accessibility if your department receives frequent data requests or actively publishes data on open data portals.

#### Play 5.3 Vignette: CDW Creates a Metadata Repository and Business Glossary

_If your department has elected to implement a metadata repository tool or you are electing to use a spreadsheet, feel free to skip this vignette._

The CDW lacks the funds to purchase a data catalog for its metadata repository tool. When the data-sharing improvement effort is successful, Sally will try to secure funding for a data cataloging tool in the next fiscal year.

Carlos’ background as a database administrator helps solve the funding problem. He suggests using tools CDW already owns, including the department’s database and collaboration platform, Microsoft Teams. First, the CDW will use a combination of spreadsheets and description fields in their databases to collect and store their metadata. These tools provide automation that help scale the effort for the rest of the department’s datasets. Carlos’ metadata management process is depicted below:

<figure><img src="../../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

#### **The CDW Creates Its Metadata Repository Technology Platform**

The high-level metadata collection and storage steps are as follows:

1. Create the Initial Data Element Inventory: Carlos runs a Structured Query Language (SQL) to extract the list of fields from the W2W database in a Comma Separated Value (CSV) format.
   1. Carlos places the file on the CDW’s collaboration platform, Microsoft Teams. The collaboration platform lets the CDW staff add metadata to a central file.
2. Collect the W2W Metadata: The CDW staff add supporting metadata, including:
   1. Program SMEs add functional descriptions to the W2W fields to describe their business meaning.
   2. The CDW security team reviews the elements and their definitions to create security classifications for the W2W data. The security team creates a set of standard classifications to help identify the security requirements for shared data, including:
      1. Personal Identifiable Information (PII)
      2. Protected Health Information (PHI)
      3. CDW Institution Codes Related to Data Security
3. Load the Metadata: The CDW database administrators create SQL-based Data Definition Language (DDL) statements that load the definitions into the W2W database. Carlos makes an Excel macro to automatically generate the DDL from the spreadsheet used to collect metadata.
4. Extract the Metadata: The W2W development team adds a step to their process to include definitions whenever they make database changes. This process keeps the W2W metadata complete and current. As the W2W database is modified, Carlos runs the SQL statement from Step 1 to extract the metadata.
5. Publish Metadata: Carlos places the resulting CSV in Microsoft Teams. The W2W database is the source of truth for metadata. The metadata spreadsheet in Teams is read-only to ensure all metadata changes are performed through the CDW development processes. He sends an email to notify data consumers that a new version of the data dictionary is available.

Carlos documents the plan for review with the W2W development and database teams. Sally schedules a meeting with the W2W development lead and its DBA to review the plan. During the meeting, Sally and Carlos use the following agenda:

* Departmental Objectives
* Executive Support
* Benefits to the W2W Technical Teams
* Metadata Repository Approach
* Support Needs During Metadata Collection

The W2W IT team lets Carlos know that they recently upgraded their database version. The new database version provides standard metadata fields for descriptions and security classifications.

Sally, Carlos, and the W2W development team agree on the approach and scope of a proof-of- concept to test its viability and gather lessons learned to improve the process. The group also agrees on how the metadata collection team will engage IT resources. The agreement helps ensure the IT staff can complete their daily job duties while supporting the metadata collection effort.

Sally decided to use a simple spreadsheet stored in Microsoft Teams for the CDW business glossary. The business glossary will be incrementally populated as the CDW data team populates the metadata repository.
