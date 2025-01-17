---
icon: chalkboard-user
---

# Data Plays

## Data Sharing Plays

The Data-Sharing Plays (Plays) improves data data-sharing by:

* Improving understanding of your data by external departments and internal data consumers.
* Mitigating late detection of security, privacy, and statutes during Business Use Case Proposal (BUCP) approvals.
* Providing a detailed description of your data to facilitate data requestors properly scoping datasets.
* Automating inventory of data fields to complete the BUCP Technical Fields.
* Implementing technical and security capabilities to receive shared data from other programs.
* Establishing BUCP metric tracking to optimize processes and data-sharing planning.

The Plays can be executed proactively before data-sharing requests or in parallel with a BUCP approval. Completing the Plays requires resource investment by your department but will provide benefits for data sharing with other organizations and direct benefits to your department. One of the participants in the Guidebook discovery sessions summarized the investment of time and future benefits as follows:

> _“We are willing to invest time upfront to save time in the future.”_
>
> – Discovery Session Participant from a CalHHS Department.

The Plays contain data architecture practices (the What) that support data-sharing and guidance to implement them (the How). A series of vignettes that depict a fictional department’s journey to improve its data-sharing capabilities are used to provide further context and implementation guidance. Not all Plays may be pertinent to your organization, depending on your existing data-sharing capabilities. We recommend reviewing the Guide in its entirety and leveraging concepts that benefit your department.

### Technical Context <a href="#technical_context" id="technical_context"></a>

The examples and vignettes are based on extracting data from a database to address a common source of shared data. The Data-Sharing Plays are adaptable to data exchanges that use Application Program Interfaces (APIs) or other data integration architectures.

### Data-Sharing Vignettes <a href="#data-sharing_vignettes" id="data-sharing_vignettes"></a>

The Plays include a series of vignettes featuring a fictional CalHHS department (California Department of Wellness) to provide context for each Play. The vignettes further elaborate each Play by telling a story that demonstrates how to its guidance into action. Reading the vignettes is optional but recommended as they offer valuable context and practical examples of the data- sharing plays in action.

The personas and their roles depicted in the vignettes are examples to illustrate the concepts described in the Plays. The roles and responsibilities of the vignette’s personas may be different from your department’s structure.

#### Vignette Context <a href="#vignette_context" id="vignette_context"></a>

The California Department of Wellness (CDW) was established in 1997 to improve the health and well-being of Californians. The CDW focuses on various aspects of wellness, like physical health, mental health, and social engagement. The CDW’s programs are interrelated with those managed by other departments under CalHHS. Although CDW is a small department, it manages over a dozen programs and supporting systems developed independently in response to various legislation over the past 20 years. Some primary CDW programs include:

* Healthy Habits is a CDW program that raises awareness about healthy lifestyle habits through various marketing campaigns, collaborations with Community-Based Organizations (CBO), and healthcare providers.
* Walk2Work (W2W) encourages people to engage in additional physical activity to improve their overall wellness and to facilitate social interaction between commuters. The Healthy Habits program collaborates with the W2W program to promote physical activity initiatives.
* Your Environment program aims to educate Californians about the significance and advantages of engaging with their communities and enjoying the beautiful spaces within the state. The program conducts outreach activities through marketing campaigns and works with community-based organizations. Your Environment also collaborates frequently with the Department of Volunteer Services and the Department of Outdoor Recreation to achieve its goals.

Other CalHHS departments utilize program data from the CDW to understand the impact of wellness on their program outcomes.

Meet the core team that is working on the CDW data-sharing improvement effort:

* Sally is the CDW Data Coordinator (DC). Prior to joining the CDW, she worked at a local government social services department that utilized data-driven practices. Sally leads the data-sharing improvement effort and coordinates with participating staff.
* Carlos recently joined the CDW 6 months ago as the Data Architect and Lead Database Administrator. He previously worked at another department outside of CalHHS as a database administrator and is learning about the CDW environment. Carlos is helping Sally with the technical aspects of data-sharing.
* Andrea is the manager of CDW Information Technology Services (ITS). Her team includes the application and data support teams that will provide information to enhance the CDW data architecture. The ITS team has minimal resource capacity for anything beyond regular system support.
* Ann is the Healthy Habits program manager. She started as a student assistant at the CDW 20 years ago and has been a staff member for all the department’s major programs. Ann has strong relationships with department leadership and is an advocate of data-sharing to achieve department objectives.
* Samantha is the business analyst for the W2W program. She is knowledgeable about the program but has not worked directly with the W2W data. Samantha is a vital part of the effort by creating business definitions to improve understanding of data meaning.
* Linda is a member of the CDW data analysis unit. She works with Samantha to create business definitions, interpret security-related data classifications, and references to statutes that govern data-sharing.
* Angelica is the W2W program specialist. She assists Samantha and Linda with creating business definitions when additional program background is required. She also is the primary coordinator with the CDW legal department.

Other CDW staff that will help improve data sharing are introduced as they appear in Play- specific vignettes.

<figure><img src="../../.gitbook/assets/image%20(6).png" alt=""><figcaption><p>Data-Sharing Vignette Personas</p></figcaption></figure>

Sally recently facilitated a team retrospective after providing data under a BUCP to share a portion of the Healthy Habits program data. Common themes from the team’s feedback include:

* We are sharing the same data; it would be helpful to have some reusable materials to reduce the time necessary to establish a BUCP and provide data.
* A statute governing data-sharing was identified late in the BUCP approval and created delays.
* Determining what data can be shared is labor intensive, as is identifying data elements, metadata, and their security classifications.
* After providing data, CDW staff are spending time answering data-related questions from departments receiving CDW data.

Based on these findings, Sally is launching an effort to improve CDW’s ability to share data using the Data-Sharing Plays.

## Data-Sharing Plays Summary <a href="#data-sharing_plays_summary" id="data-sharing_plays_summary"></a>

This Guidebook comprises eight Data-Sharing Plays that aim to improve your ability to share and receive data. The roadmap below depicts the relationships of the Plays and their suggested order of execution:

<figure><img src="../../.gitbook/assets/image%20(1).png" alt=""><figcaption><p>Data-Sharing Plays Roadmap</p></figcaption></figure>

The tables below summarize the Plays and their primary objectives:

### Objective: Launch Your Data-Sharing Improvement Effort

<table><thead><tr><th width="100">Play</th><th>Summary and Benefits</th></tr></thead><tbody><tr><td>1</td><td>Establish Data-Sharing Metrics, and BUCP Tracking establishes a mechanism for your department to track metrics related to data-sharing for process improvements and planning.</td></tr><tr><td>2</td><td>Identify Your Datasets promotes awareness of your datasets and is a component of downstream Plays.</td></tr><tr><td>3</td><td>Create a Business Case provides general pointers to secure support from executive approvers and departmental teams needed to execute the Plays.</td></tr></tbody></table>

### Objective: Improve Your Ability to Provide Data

<table><thead><tr><th width="100">Play</th><th>Summary and Benefits</th></tr></thead><tbody><tr><td>4</td><td>Prioritize Your Data ranks the priority of your datasets to guide investment in data-sharing improvement efforts to focus on datasets that provide the department the most return on their investment.</td></tr><tr><td>5</td><td>Establish Your Metadata Repository creates a technology platform to house detailed information that describes your data. The repository supports creating the BUCP Technical Fields and provides information for security and statute reviews. After data fulfillment, the repository is used by data consumers to understand shared data.</td></tr><tr><td>6</td><td>Describe Your Data provides a high-level process to create business definitions, security classifications, and references to governing statutes. This is the core Play that improves data understanding and supporting content for BUCP Technical fields and input for security analysis.</td></tr><tr><td>7</td><td>Promote Data Awareness suggests ways to build awareness of your data internally and with other CalHHS departments to realize benefits from your investment in data-sharing.</td></tr></tbody></table>

### Objective: Improve Your Ability to Provide Data

<table><thead><tr><th width="100">Play</th><th>Summary and Benefits</th></tr></thead><tbody><tr><td>8</td><td>Prepare to Receive Data includes proactive efforts you can take to address data-sharing security requirements and infrastructure.</td></tr></tbody></table>
