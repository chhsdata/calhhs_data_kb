---
icon: circle-8
---

# Play 8

## Play 8: Prepare to Receive Data

The previous Plays provided guidance to improve data-sharing between programs within your department and other organizations. It is equally important to take measures to improve your department’s ability to request and receive data. This Play helps you receive shared data by:

* Establishing an environment or shared service to store and consume shared data.
* Demonstrate and document security controls when requesting data.
* Identify available options to transfer shared data.

This Play can be executed in parallel with other Plays to simultaneously improve your department’s ability to share and receive data. Completing the following Plays helps you develop a business case to secure resources or funding to improve your department’s ability to receive shared data:

* **Play 1: Establish Data-Sharing Metrics and BUCP Tracking**
* **Play 3: Create a Business Case**

_This Play does not have a supporting vignette._

### Play 8.1: Assess Your Shared Data Environment <a href="#play_8.1-_assess_your_shared_data_enviro" id="play_8.1-_assess_your_shared_data_enviro"></a>

A ready-to-use data-sharing environment is a critical technical component of receiving shared data. Identifying gaps in your shared data environment late in a BUCP approval or data fulfillment creates delays. Proactively identifying gaps in your shared data environment provides time to address them ahead of received data.

Some questions to address during your shared data environment assessment include:

* Does the environment have sufficient capacity to store shared data?
* Is the environment accessible to your department’s staff who will use shared data?
* Is the environment sufficiently secure to receive shared data?
* Are there any funding restrictions that would restrict the environment’s use?

Create a list of any gaps identified during your shared data environment assessment. Use the list of gaps to work with relevant teams, such as enterprise architecture and information security, to determine resolutions. Since resources to support data sharing are likely limited, create a resolution plan that implements mitigations in the short term (e.g., manual processes) with a plan for full resolution over time.

Use the guidance from _Play 3: Create a Business Case_ to create a business case combined with shared data impacts from the BUCP repository created in _Play 2: Identify Your Datasets_ to identify past data-sharing business results and secure needed resources.

The Center for Data Insights and Innovation (CDII) Agency Data Hub (Data Hub) is an agency- level data-sharing service provider. The Data Hub may be an option that leads to a faster path to receiving shared data than resolving gaps in your internal environment.

The Agency Data Hub is a secure cloud-based data-sharing ecosystem built on a modern platform for data science and analytics. The Agency Data Hub is a collaborative platform that is non-specific to any program or department, where staff across Agency departments and researchers can work together on focused efforts.

For more information on the Agency Data Hub, please contact the Center for Data Insights and Innovation (CDII) at [cdii@chhs.ca.gov.](mailto:cdii@chhs.ca.gov)

### Play 8.2: Identify Data Transfer Platforms <a href="#play_8.2-_identify_data_transfer_platfor" id="play_8.2-_identify_data_transfer_platfor"></a>

Data transfer platforms are used to deliver data from providers to recipients. Delays due to data transfer capabilities were cited in several instances during the discovery sessions used to create this Guidebook. Some examples of data transfer technologies include:

* Secure File Transfer Protocol (SFTP) for file-based data sharing.
* Representational State Transfer (REST) Application Program Interfaces (API) for ongoing data interfaces
* Data streaming (e.g., Apache Kafka) for continuous data transfer.

Work with your department’s information technology team to identify data transfer platforms that are available for data-sharing. While creating your BUCP, evaluate your data transfer platforms to verify the following:

* Is the platform compatible across data provider(s) and recipient(s)? For example, does the data recipient have the technical capabilities to access shared data via an API?
* Does the data transfer platform have network connectivity between the data provider and recipient?
* Are there any restrictions (e.g., funding) that prohibit using the data platform technology?
* Does the data transfer platform meet information security requirements?

If a suitable data transfer platform is unavailable, consider using shared services including:

* The California Department of Technology [Secure Automated File Exchange](https://cdt.ca.gov/services/safe/) (SAFE) service is an option. The SAFE service allows for the secure transfer of files over public and private networks using encrypted file transfer protocols (FTPS, SFTP/SSH, and HTTPS).
* Although not a data transfer service, the CalHHS Agency Data Hub (Agency Data Hub) is another option to provide data access.
* Another option for small-volume datasets with limited security controls is to leverage the State of California Office 365 to use Microsoft Teams for data transfer.

### Play 8.3: Demonstrate Security Controls to Data Providers <a href="#play_8.3-_demonstrate_security_controls" id="play_8.3-_demonstrate_security_controls"></a>

A data provider’s Information Security team may require a review of the controls used to secure sensitive shared data. Creating an inventory of security controls is time-consuming and can create data-sharing approval delays. You can ready your department to receive shared data by proactively documenting the security controls of technical environments that contain shared data. In addition to improving data sharing, this exercise improves your system’s information security posture by:

* Establishing alignment with the State of California Statewide Information Management Manual (SIMM) 5300.5.
* Identify areas to improve security controls and funding needs.
* Providing input to a security roadmap or Plan of Action and Milestones (POAM).

One option is to document the security controls using the National Institute of [Standards Special](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final) [Publication 800-53](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final) (NIST SP 800-53) controls. Documenting your security controls using NIST 800-53 provides a commonly accepted set of controls for evaluation by the department providing data. This effort can also improve your data security outside data sharing by identifying needed security control improvements.

For security approvals of “Commercial off the Shelf” (COTS) platforms, such as Office 365 (O365), you can use the NIST Cyber Security Framework (CSFG) 2.0, which is a simplified, summarized control assessment model. The NIST CSF aligns with NIST SP 800-53 and the State of California SIMM.

If you want to provide additional demonstration of your security controls to data providers, your department can engage a third-party assessor to evaluate your security. The California Military Department provides independent [security assessment services](https://cdt.ca.gov/security/independent-security-assessments-services/).
