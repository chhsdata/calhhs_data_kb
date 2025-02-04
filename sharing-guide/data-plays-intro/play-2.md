---
icon: circle-2
---

# Play 2: Identify

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

## Play 2: Identify Your Datasets

This Play lays the groundwork for the subsequent Plays by creating an inventory of your department’s datasets. Your data inventory is a core component of data sharing that provides data consumers with a list of datasets. The [CalHHS data catalog of open data sets](https://data.chhs.ca.gov/dataset/dataset-catalog) provides an example of this concept. In this Play, you will:

* Create a repository for your data inventory.
* Create a complete list of datasets.
* Review datasets for deprecation, archival, or purging.

Even if you already have a dataset inventory, it is a good practice to periodically audit your inventory to ensure your inventory is complete and accurate.

A bonus from creating your data inventory is that it establishes compliance with SAM (State Administrative Manual) [5160.1](https://www.dgs.ca.gov/Resources/SAM/TOC/5100/5160-1) Item 4, requirements for Agencies to maintain an enterprise data inventory.

Creating your data inventory is foundational for later Plays. For example, your data inventory is used in Play 4: Prioritize Your Data, is used to prioritize your datasets.

The Guide provides a distilled set of steps to create your department’s data inventory. Further instruction on creating a data inventory is available from the Centre for Agriculture and Bioscience International (CABI) [data-sharing toolkit.](https://www.datasharingtoolkit.org/wp-content/uploads/2021/03/CABI-Mod7-3-01-Checklist.pdf) The data-sharing toolkit’s metadata template is applicable across business domains.

### Play 2.1: Create Your Data Inventory Repository <a href="#play_2.1-_create_your_data_inventory_rep" id="play_2.1-_create_your_data_inventory_rep"></a>

You can capture your data inventory using a data catalog tool or a spreadsheet stored in a collaboration platform (e.g., Microsoft Teams). A spreadsheet stored on a collaboration platform (e.g., Teams) is a quick way to launch your data inventory effort. You can always start creating your data catalog with a spreadsheet and migrate to a cataloging application later.

Once you have your platform established, configure it to capture fields that describe dataset (e.g., Database) key characteristics including:

* Title
* Program Name
* Description
* Tags
* Topic
* Security Classification(s)
* Data Update Frequency
* Related IT Systems
* Database Platforms
* Program(s)
* Program Point(s) of Contact
* Relationship to Other Programs

The Data Sharing Toolkit _How to Create a Data Inventory_ provides additional guidance on characteristics and a sample data inventory format.

#### Play 2.1 Vignette: Sally and Carlos Create the Department’s Data Inventory Repository

Sally and Carlos meet to create the repository to store the California Department of Wellness (CDW) datasets. The CDW doesn’t have a data catalog platform to store the department’s dataset inventory. They decide to start the effort by using the Data Sharing Toolkit _How to Create a Data Inventory_ to create a spreadsheet to store the department’s dataset inventory. They create a new “Teams Site” in Microsoft Teams to store the data inventory spreadsheet and to provide access to the department’s staff once the inventory is complete.

Once the CDW’s data-sharing improvement initiative receives executive approval, they will create a business case to deploy a data cataloging platform to better collect detailed metadata.

### Play 2.2: Identify Your Department's Datasets <a href="#play_2.2-_identify_your_departments_dat" id="play_2.2-_identify_your_departments_dat"></a>

It's a challenge to identify all the data that exists in your department. Even if your department has a data catalog, it may not be up to date. Your department likely produces data from different systems and in various formats. Your datasets may also come from different sources including:

* Database/Datastores
* Report Result Sets
* Data Extracts
* Application Program Interfaces (API)

The knowledge of your department’s data may be distributed across multiple teams including:

* Information technology staff (e.g., Database Administrators) that manage your department's databases.
* Analytics staff that create reports and tailored datasets.
* Data management staff that create curated data sets.
* Program-level staff who created datasets on their own.

These roles may not be represented in your department, but staff who perform these functions can be interviewed to discover your department’s data.

Combining a list of your department’s programs and their corresponding technology platforms creates a comprehensive starting point to inventory your datasets. Although your information technology department likely has a broad view of data sources, they may not have visibility of systems developed by lines of business. Creating the inventory from both the program and technology aspects ensures your dataset list is complete and captures the information needed for your data-sharing efforts. The diagram below depicts the process of collecting your dataset inventory:

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

**Identify and Describe Your Datasets**

Later in _Play 4: Prioritize Your Data_, your team will prioritize datasets based on their relevance to department objectives and cross-program relationships. While creating an inventory, your interactions with other teams allow you to gather information on the department’s datasets to prioritize data-sharing efforts. Execute the steps below to establish your list of datasets and capture their characteristics:

1. Create a consolidated list by combining your department’s programs with your inventory of supporting IT systems.
2. Reach out to your IT staff to identify the program owners and points of contact for your systems. Once the points of contact are identified, interview them to gather and enhance the level of detail in your data inventory.
3. Review available materials (e.g., Description of Programs) to establish context for conducting interviews and discovery sessions effectively.
4. Conduct discovery sessions or interviews with program teams and data analysts to capture the following:
   1. A business-level description of the dataset.
   2. Relevant points of contact.
   3. Cross-program relationships.
   4. Relationship to department and agency objectives.

Populate your data inventory as you capture each dataset’s information to incrementally complete your department’s dataset inventory.

#### Play 2.2 Vignette: Sally and Carlos Inventory the CDW Datasets

Sally sets out to create a current inventory of the CDW datasets. Sally and Carlos’ effort to inventory the CDW data is depicted in the graphic on the following page:

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

**Creating the CDW Dataset Inventory**

After looking through the CDW, she finds an inventory of datasets. The file was last modified ten years ago. To ensure the inventory is current, Sally decides to use the previous inventory as a starting point and update it with the changes that have occurred over the past decade. Her approach is to first get an inventory of datasets known to the CDW Information Technology (IT) team and reconcile this inventory with the list of CDW programs.

Since Carlos recently joined the department, he has not yet learned about all the CDW systems. Carlos asks Andrea, the CDW IT Manager, for a list of the various databases and extracts maintained by CDW. The list from IT has high-level technical information on the datasets and some high-level description of the content but needs additional information from program teams to establish business context.

Sally retrieves a list of the programs (e.g., Healthy Habits) run by the CDW. She added the related programs to the list of systems she received from IT. Sally adds the lists of the CDW programs to verify that the list is complete. She finds that the IT department’s list does not include a system used by the Healthy Habits program. She takes a note to find out more about where the Healthy Habits data is stored.

Before contacting the various programs, Sally prepares discovery session questions to gather the information she needs to complete the data inventory. Sally reads _Play 4: Prioritize Your Data_ to develop questions to gather some initial information that will be later used to prioritize the CDW data-sharing improvement efforts.

The discovery sessions with the departments provide Sally and Carlos with the following:

* Business context to enrich the descriptions of the CDW datasets.
* The business point of contact for the dataset.
* Relationships to other CDW and CalHHS programs.
* General information to support the prioritization of data-sharing improvements.

Sally and Carlos also learn some unanticipated information through follow-up questions during the discovery sessions, including:

* In the meeting with the Healthy Habits team, Carlos and Sally learned that the program’s IT system is maintained by a vendor. Since the Healthy Habits program directly manages the vendor contract, it is not listed in the inventory from IT. They add the Healthy Habits to the list of datasets to get a complete picture of in-house and vendor- managed data.
* The Walk 2 Work program has a forthcoming modernization project. The data-sharing improvement effort includes planning, new system design, and data conversion for the modernization project. During the discovery session, Carlos and Sally learned that the program has created some datasets on their own without assistance from IT. They add these datasets to the inventory.
* The Your Environment team was unaware they could request data from other departments using a BUCP data-sharing agreement. This awareness increased interest in supporting Sally and Carlos’ efforts to improve data-sharing. Sally and Carlos scheduled a follow-up with Pankaj to provide an overview of data-sharing.

Sally and Carlos have created the complete inventory of the CDW datasets. The effort also made important new contacts with program and technology staff. Carlos interacted with various programs and staff to build his knowledge of the CDW programs.

After looking at many datasets, they realize this will be a significant effort, and focusing on priority data sets is the best approach.

### Play 2.3: Create a Data Lifecycle Process <a href="#play_2.3-_create_a_data_lifecycle_proces" id="play_2.3-_create_a_data_lifecycle_proces"></a>

Your dataset inventory established in this Play is an input to data lifecycle management. The dataset prioritization effort in _Play 4: Prioritize Your Data_ is an opportunity to identify datasets that are candidates for archival or disposal once your department has its data lifecycle processes in place.

It is important to periodically review your list of data for archival and purge. Datasets that are outdated, inaccurate, or no longer in use negatively impact your department by:

* Increase risk exposure and potential for data breaches.
* Unnecessarily incurring infrastructure costs and using of department technology staff resources.
* Inadvertent use of inaccurate or outdated dataset.
* Non-compliance with data retention and disposal statutory requirements.

Establishing data archiving and disposal processes and technical capabilities also support BUCP requirements for data disposal after the approvals data use authorization period ends.

***

## Where to Find Your Data

The final step of the planning process is also the most important and crucial to successful execution of your project: determining what data you need and where you will find it. This step can be time-consuming and frustrating, but the effort you put in will pay itself back ten-fold when you find yourself sitting down to start data analysis. Accurate, validated, and comprehensive data is the cornerstone to any data-driven initiative. It is critical to prioritize reliability and integrity of the data in order to ensure the legitimacy of your findings. In most data-driven companies, the “80/20 Rule” applies to data projects: 80 percent of your work will be spent finding, retrieving, cleaning, and organizing your data, and only 20 percent spent on actual data analysis. So don’t be surprised if this process seems daunting, and don’t rush through it. In this section, you’ll find information on accessing Internal Data (both within your department and in others) as well as External Data (data owned by some outside agency/organization, and typically publicly available). Use the Process Flow Chart on the following page to choose which resource — the Data Sharing Agreement, the Open Data Portal, your department’s stored data, or publicly available data— is appropriate for each of your data sources.

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

### Option 1: Program Data

In most cases, you’ll be working with your Program Data — data that is owned by your department and collected by or for your program. This data resides within your department, and is easily accessible through your department’s Data Coordinator, who is your first resource to seek out when you need help thinking of what data to source for your project or where to find it. Please email CHHS@osi.ca.gov for help with contacting your department’s data coordinator.

### Option 2: Data in Other Departments

In a few cases, you may find that your department does not have enough data for you to proceed with data analysis. To ensure you have a sufficient amount of data to begin your analysis, you are encouraged to look to other departments’ data assets and determine if they’d be appropriate for your project. Your first step to finding data in other departments is to check the CHHS Open Data Portal, our database for all CHHS data that is publicly-available.

Data Sharing Agreement: Accessing private data in other departments is dictated by the CHHS Data Sharing Agreement, a legal document that entitles the departments under CHHS to access the other CHHS department’s data assets through a Business Use Case Proposal. Only proceed with this section if you’ve (1) decided that some of the data you need is not already available through your department and (2) is NOT found on the Open Data Portal, then this is your next step.

{% hint style="info" %}
Note: Read the Data De-Identification Guidelines (in Section 2, Part 1: Cleaning/De-Identifying your Dataset) before sharing any data from your department.
{% endhint %}

The goals of the Data Sharing Agreement are the following:

Establish a legal framework for data initiatives Maximize appropriate sharing to increase positive outcomes and customer service Ensure privacy and security protections Reduce risk and use of duplicative resources Standardize data use agreements among CHHS Departments and offices Reduce contracting and data use agreement redundancies Track activity for better understanding of common data sharing needs between CHHS departments To get data via the Data Sharing Agreement, you must contact your department’s Data Coordinator and submit a Business Use Case Proposal; this ensures proper documentation of what data you need, why you need it, and your commitment to several requirements, such as preserving the shared dataset in the form it was given to you. For more detailed instructions, visit the Business Use Case instructions or view the FAQ.

<figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

### Option 3: Externally (Publicly-Available Data)

In the past decade, public interest in big data and data-driven projects has skyrocketed. As a result, there is a wealth of data available for free that may help you contextualize your results, find baseline measurements, or contribute to your findings. This section showcases some of our favorite sources of publicly available data.

* USAFacts.org — A data-driven portrait of the American population, our government’s finances, and government’s impact on society that uses federal, state, and local data from over 70 sources.
* datacatalogs.org — DataCatalogs.org aims to be the most comprehensive list of open data catalogs in the world. It is curated by a group of leading open data experts from around the world - including representatives from local, regional and national governments, international organizations such as the World Bank, and numerous NGOs.
* HealthData.gov — Dedicated to making high value health data more accessible to entrepreneurs, researchers, and policy makers in the hopes of better health outcomes for all.
* LOGD Dataset Catalog — The Linking Open Government Data (LOGD) project investigates opening and linking government data using Semantic web technologies. We are translating government-related datasets into RDF, linking them to the Web of Data and providing demos and tutorials on mashing up and consuming linked government data. CIA World Fact Book — Provides information on the history, people, government, economy, geography, communications, transportation, military, and transnational issues for 267 world entities. openFDA — Makes it easier to get access to publicly available FDA data. FDA’s goal is to make it simple for an application, mobile device, web developer, or researcher to use data from the FDA.
* Census Reporter — A Knight News Challenge-funded project to make it easier for journalists to write stories using information from the U.S. Census bureau. Place profiles and comparison pages provide a friendly interface for navigating data, including visualizations for a more useful first look.
* CalEnviro Screen — A mapping tool that helps identify California communities that are most affected by many sources of pollution, and where people are often especially vulnerable to pollution’s effects. California Healthy Places Index — A tool to explore community conditions that predict life expectancy. It contains user-friendly mapping and data resources at the census tract level across California.
* CHHS Open Data Portal — Offers access to standardized data that can be easily retrieved, combined, downloaded, sorted, searched, analyzed, redistributed and re-used by individuals, business, researchers, journalists, developers, and government to process, trend, and innovate.
