---
icon: computer
---

# Application Program Interfaces

## Describing Application Program Interfaces

Technology standards for metadata differ between Application Program Interfaces (API's) and data stored in databases or files. The techniques provided in the Guide to identify and describe data elements are pertinent to describing your APIs. If your data-sharing improvement effort is API- focused, reference this section during the execution of Play 5: Establish Your Metadata Repository to establish a repository compatible with API metadata standards.

### API Description Standards <a href="#api_description_standards" id="api_description_standards"></a>

Industry standards and best practices will evolve with the field. Currently, there are two widely adopted API description standards:

* [OpenAPI Specification](https://www.openapis.org/) (OAS) is a broadly recognized metadata specification for API descriptions.
* [RESTful API Modeling Language](https://raml.org/) (RAML) is an API modeling language for developing and publishing API descriptions.

Which one should you use? Each option has its considerations.

If your application development team has already adopted an API description standard, leverage their work and adopt the same standard. If your API descriptions are not current, execute Plays 2 through 6 to make them current.

If an API specification standard is not already in place, you need to work with your application development and enterprise architecture teams to jointly select a standard.

A primary consideration is which standards are supported by your API Gateway/Management platform. Review your platform’s documentation to identify supported standards. Converters are available to change formats between OAS and RAML; however, this adds an additional step to your deployment process.

Another critical factor is each standard's approach to capturing custom metadata that is beneficial for data sharing, such as security classifications and statute citations. OAS 3.x provides [custom extensions](https://swagger.io/docs/specification/openapi-extensions/) embedded in the description file. RAML extends its base metadata elements with [overlay files.](https://raml.org/developers/whats-new-raml-10) Your development team should evaluate each option to determine which platform’s approach to custom metadata best aligns with their processes.

### Publishing Your API Descriptors

For your API descriptors to be useful, they must be easily accessible by API consumers. Check if your API Gateway/Management platform provides an API catalog to publish your APIs. If this feature is available, it is the best option as it easily integrates publishing your API descriptors into your development and deployment processes.

If your platform does not provide an API catalog, you can make your API descriptors accessible using a web server or an object store (e.g., AWS S3, Azure Blob Storage). OAS and RAML publish descriptors as JSON files that are viewable using a web browser. Your team will need to create and maintain an index webpage that contains links to your API descriptions. Be sure to include steps to publish the API descriptor and update the index webpage in your development processes.

Many data catalog platforms maintain the JSON-based formats used by both OAS and RAML, creating an option for publishing your APIs for data consumers. Using a data catalog also allows custom metadata to be captured if using extensions/overlays is not an option. Using a data catalog also provides the benefit of establishing data lineage from APIs to backend databases.

### Keeping Your API Descriptors Current

The approach described in Play 6.3: Keep Your Metadata Repository Current that integrates metadata maintenance into your development process applies to maintaining your API descriptions. RAML combines the creation of API descriptions with modeling and development. OAS generates descriptions from the underlying application code used to develop the API. Both options create a closed loop between development and descriptors to keep your API catalog current.
