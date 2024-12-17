---
icon: list-radio
---

# Supplemental: Definitions

## Creating Effective Data Element Definitions

This section explains the characteristics of effective data definitions and an approach to developing data definition skills across your team. Even if you have experience in this area, this guide helps develop data definition skills for the team members participating in the metadata collection effort.

The incentive to create effective definitions is that your staff spends less time fielding questions from data recipients. Additionally, an accurate understanding of data translates to more precise analytics that inform program, department, and agency-level decisions.

Some data element meanings are apparent and straightforward to define. Others have a very specific meaning in the context of your department's business and can be more difficult to define.

Creating effective data definitions may sound intimidating, but creating effective definitions just takes practice. Building any new skill takes a few rounds of _focused practice._ After some practice, creating accurate definitions will become natural to you and your team.

The steps to create effective data definitions are summarized below:

1. Incrementally create a list of your department's business terms (i.e., Business Glossary).
2. Select a sample of data elements with meaning that is contextually specific.
3. Use the sample to create a set of practice definitions and review them with a team member.
4. Incorporate the reviewer's feedback and practice again until you feel comfortable with the practice of creating definitions.

The examples in this guide depict creating database field definitions but apply to creating Application Program Interface (API) attribute definitions.

### Creating Effective Data Definitions

There is no specific or "right" format for a data definition; the measure of success for a data definition is whether it can be easily and quickly understood. To this end, _George Washington University’s (GWU) Business Intelligence Services_ provides actionable guidance on creating effective data definitions in "[Creating Good Data Definitions](https://businessintelligence.gwu.edu/creating-good-data-definitions)." We recommend reading this information and saving it as a reference for use during your metadata collection and data definition effort.

### Practice Your Data Definition Creation Skills

The steps in this section provide a suggested approach to practicing your data definition skills. This approach is adaptable to your learning style. The main point is to practice and validate your definitions until you feel comfortable moving forward. Inaccurate or incomplete data definitions limit the effectiveness of your data. Some _focused practice_ up front pays dividends in the future.

Here are the steps to develop practical data definition skills:

***

### 1. Select a Practice Set of Data Elements

Start your practice by selecting two data element sets to practice your definition skills.

We recommend that the first set of data elements have an apparent definition to establish base skills and expand those skills. This set is used to practice foundational aspects of creating definitions and build confidence in your abilities.

Identify a second set of data elements that will be more challenging to define. Some characteristics that make a definition more challenging include:

* Expansive meaning of the data elements
* Inclusion of units of measure (e.g., Time)
* Description that is specific to your department

***

### 2. Create Practice Definitions for Your Sample Set of Data Elements

For each of your sample data elements, create a definition that is:

* Clear: precise, concise, and unambiguous. Allows only one possible interpretation
* Specific Concept: includes the essential meaning or primary characteristics of the concept
* Primary Definition: Does not contain any embedded definitions or underlying concepts of other data elements
* Defined without Circular Reasoning: Is not defined in terms of another data element
* Expressed without Rationale, Functional Usage, Domain Information, or Procedural Information: Does not include statements about why and how a data element is used.

***

### 3.    Assess Your Practice Data Definitions

After you create your practice definitions, take a step back and assess each of them by asking yourself the questions below:

* Would I understand this definition if I were a new team member unfamiliar with our department's terms, program names, and other peculiarities?
* Is the subject of the definition clear and specific?
* Is the definition concise? Can I quickly understand the data's meaning?
* Can I use this definition for data analysis? Does it specify the required units of measurement, if applicable?

Based on your self-assessment, make needed adjustments, and ask these questions again. Once your definitions have passed a self-assessment, it's time to get feedback from a peer.

***

### **4.    Conduct a Peer Review and Integrate Feedback**

A definition may be clear to you, but ambiguous to others. Peer reviews capture others' interpretations to ensure the data definitions are understandable for as many data consumers as possible.

Schedule a meeting with a team member to review your practice definitions. After they have reviewed your practice definitions, ask them to state their understanding of the data elements. If the meaning wasn't clear to your team member, adjust and present it again in the same session. Iteratively capturing feedback for adjustments builds your data definition skills and improves understanding.

When possible, conducting this exercise with another team member is an informal training opportunity to enhance their familiarity with data definitions and authorship.

Peer reviews inevitably add time to the effort, but as your data definition skills improve, they may only be needed when you are unsure of the clarity of a data definition.

***

### Enable Your Team

Encourage the team members who create data definitions to use this guide to refine their skills in defining and refining data definitions iteratively. A collaborative workshop allows team members to learn and practice new skills together and develop confidence. A sample workshop agenda is presented below:

* Inform your team of the characteristics of effective data definitions.
* Review the techniques to practice data definition skills.
* Conduct a collaboration session where attendees develop definitions, review them with other attendees, and iteratively incorporate improvements.

Feel free to adapt this agenda and skill-building approach to the needs of your team.

### Example Data Definitions and Vignette

This vignette describes the process of creating initial data definitions and refining them to maximize their clarity. The examples are based on the department, the California Department of Wellness (CDW), and the Walk 2 Work (W2W) program. The vignette finds Sally practicing her data definition skills and coaching her team during the CDW’s effort to enrich the W2W dataset metadata (Play 4: Describe Your Data, Vignette).

Sally reads George Washington University’s “[Creating Good Data Definitions](https://businessintelligence.gwu.edu/creating-good-data-definitions)” to understand the characteristics of effective data definitions. She prints the summary of data definition key characteristics and hangs it in her working area as a quick reference.

Sally creates a template for the business glossary in Microsoft Teams, the CDW’s collaboration platform. The business glossary is a tab in the data dictionary that defines the terms specific to the W2W program.

To practice her skills, Sally selects a small set of data elements to create definitions. The data elements relate to the business term of a “Stop” on a W2W participant’s commute. Sally selects the following data elements to practice her definition skills:

1. Geocode: Sally selects this element because existing industry standards for geolocation data partially define its meaning.
2. Location: She selects this data element because its meaning is expansive, and it is a critical data element for many program data analysis efforts.
3. Address: Sally selects this data element for her practice efforts because its meaning is apparent, but it is a good starting point for building foundation skills for definition structure.
4. Duration: Sally selects this data element because it contains a time-based unit of measure and is vital for W2W case processing Key Performance Indicators (KPIs).

| Field    | Friendly Name          | Definition                                       | Open Question                                                                                                                                                        |
| -------- | ---------------------- | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Geocode  | Stop Geocode           | The geocode of the stop.                         | The definition is missing the geocode format.                                                                                                                        |
| Location | Location Where Stopped | A Location that is part of the commuter’s route. | Is this a business, cross- street, etc., during the walk to work?                                                                                                    |
| Address  | Address                | The address associated with the Location.        | Is this a portion of the address or the complete address?                                                                                                            |
| Duration | Duration in Minutes    | The duration in minutes.                         | It’s not clear to the data consumer what the duration refers to. Is this the time used for the walk to work? Is this the duration of a stop during the walk to work? |

&#x20;Sally then adds the business term “Stop” to the CDW business glossary.

| Business Term |                                                                                                                            Business Definition                                                                                                                            |
| :-----------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|      Stop     | A planned stop on a participant's commute, such as visiting a business, park, or time spent transitioning between modes of transportation (e.g., Light Rail Station). A stop does not include unplanned stopping points, such as waiting at a traffic light or crosswalk. |

&#x20;The new term in the business glossary provides additional context for the data element definitions related to this business term.

The business glossary helps inexperienced staff and external data recipients understand the W2W business. It also allows for re-using the business term across multiple data elements.

Next, Sally updates the data definitions for these three data elements. She performs a self-assessment of the definitions and makes some adjustments to improve the specificity of Location and Duration.

|   Field  |      Friendly Name     |                                                     Definition                                                    |
| :------: | :--------------------: | :---------------------------------------------------------------------------------------------------------------: |
|  Geocode |      Stop Geocode      |                                 The geocode of the stop in decimal- degree format.                                |
| Location | Location Where Stopped |                  A Location (e.g., Business) where the participant stopped during their commute.                  |
|  Address |         Address        |                                         The street address of a Location.                                         |
| Duration |   Duration in Minutes  | This field captures the duration the W2W participant remained at a Location (e.g., Stopped) during their commute. |

After improving the definitions, Sally schedules a peer review with Claudia, a business analyst who recently joined the W2W team. Claudia will be helping the team define the business aspects of the W2W metadata. Working with Claudia allows Sally to get feedback and build another team member’s understanding of the W2W data.

Claudia’s understanding of Location and Duration was mostly but not entirely correct. Sally adjusts the definition and asks Claudia to provide her understanding based on the new definition. With the new definition, Claudia now has a complete understanding of the data element.

The updated definitions are entered into the data dictionary:

|   Field  |      Friendly Name     |                                                             Definition                                                             |
| :------: | :--------------------: | :--------------------------------------------------------------------------------------------------------------------------------: |
|  Geocode |      Stop Geocode      |                                         The geocode of the stop in decimal- degree format.                                         |
| Location | Location Where Stopped |   A Location with a registered USPS address (e.g., Business, Residence, Park) where the participant stopped during their commute.  |
|  Address |         Address        |       The street address of a Location composed of address number, street name, and street type (e.g., Street Road, Avenue).       |
| Duration |   Duration in Minutes  | This field captures the duration in whole minutes the W2W participant remained at a Location (e.g., Stopped) during their commute. |

Sally schedules a data definition training workshop with the team conducting the metadata collection effort. The workshop helps spread data definition skills across the team. She reviews the characteristics of effective data elements with the team. Sally has pre-selected a set of simple and challenging-to-define data elements for each workshop participant. As a group, they create definitions and perform a peer review with another participant.

Sally encourages the team to practice on their own before the kickoff of the metadata collection effort.
