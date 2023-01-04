## SOAP 
 This is a blueprint for entering a standardized API lifecycle using a WSDL for an existing web service, acknowledging that SOAP still has its place in many enterprise Environment, but a common API lifecycle including documentation, testing, and other elements is still needed. 

### Define 
For traditional web services, the web services description language (WSDL) is the key to defining and understanding what each API is capable of. Similar to an OpenAPI, the WSDL describes the surface area of a SOAP web service, defining the available methods and payload structure. Upon import or creation of a new API using WSDL, a modern API lifecycle can be set into motion through the generation of collections for documenting and testing web services. Helping modernize existing web services by applying some of the common elements of modern API lifecycle to existing WSDL services. 

- **WSDL** - WSDL is an XML format for describing network services as a set of endpoints operating on messages containing either document-oriented or procedure-oriented information, providing the operations and messages are described abstractly, and then bound to a concrete network protocol and message format to define an endpoint. 
null 
### Document 
Having complete, accurate, and easy-to-follow documentation is essential for all APIs and is something that alleviates the number one pain point for API consumers when it comes to onboarding with any API, expanding the number of API paths an application puts to work. Modern approaches to producing API documentation have moved beyond a single static version of documentation simply published to a portal, as well as there being potentially multiple forms of documentation for any single API. Helping API producers onboard consumers easier, reducing the cognitive load when understanding what an API does, and properly defining specific business use cases of an API being put to work in an application or as part of an integration. 

- **Reference Documentation** - It is helpful for API consumers to have complete documentation for the entire surface area of an API, providing a complete reference of what is possible with an API to help consumers explore every path, parameter, schema, and other details of how an API works, making the resources and capabilities available within API something consumers can find and put to use without much work. 
null 
### Testing 
A test-driven API lifecycle ensures that each API delivers the intended outcomes it was developed for in the first place, providing manual as well as automated ways to ensure an API hasn~t changed unexpectedly and is as performant as required, helping establish a high quality of service consistently across all APIs. API testing should not be an afterthought and should be a default aspect of the API lifecycle for any API being put into production. API testing takes a solid investment in establishing proper testing practices across teams, but once you do the work to establish a baseline of testing, properly train teams on the process and tooling involved, the investment will pay off down the road. 

- **Contract Testing** - Contract tests can be derived from API artifacts like OpenAPI, JSON Schema, and GraphQL, and used to ensure there are no changes to what has been promised when an API was designed or developed, providing a repeatable test that can be run manually, on a schedule from multiple regions, or as part of a CI/CD pipeline to ensure contracts with consumers are upheld. 
- **Performance Testing** - Performance tests can be defined as individual tests using collections, pulling from one or many individual API paths and measuring the time it takes for the response to be sent, providing a test that can be run manually, scheduled across multiple geographic regions, or executed as part of a CI/CD pipeline, helping ensure an API is always meeting it~s expected performance benchmarks. 
null 
### Secure 
Security must be its own area of the API lifecycle, but it is something that should span testing, authentication, and potentially other areas of the API lifecycle. Over the last five years, the world of API security has expanded, while also moving further left in the API lifecycle as part of an oerations shift in how APIs are delivered. There are a number of elements present when it comes to security, but depending on the overall maturity of API operations the available resources and prioritization available to adequately realize these elements vary. 

- **Security Testing** - Security tests can be defined for any API using executable and shareable collections, testing for common OWASP vulnerabilities, as well as other more custom scenarios or business approaches, providing a single or suite of security tests that can be manually run, scheduled across multiple regions, or executed as part of a CI/CD pipeline, automating security consistently across APIs. 
null 
### Monitor 
Monitors can be used to execute any Postman collection applied to any environment. Due to the versatility of what a Postman collection can define, collections turn monitors into powerful API automation and orchestration tool. Beginning with the ability to schedule contract, performance, and other types of tests, but then also allowing for automating specific workflows across many different APIs. Since collections can be used to define anything that can be defined via an API, monitors can be used to schedule the running of each capability from multiple cloud regions, applying many different environmental variables. Making monitors an essential, versatile, and executable part of defining how the API lifecycle works. 

- **Uptime Monitoring** -  
- **Contract Testing Monitoring** -  
null 
### Discovery 
The ability to discover APIs at all states of the API lifecycle is essential for reducing redundancy across operations, helping teams find existing APIs before they develop new ones, properly matching API consumers with the right APIs, while supporting documentation, relevant workflows, and the feedback loops that exist as part of the operation of APIs internally within the enterprise, or externally with 3rd party developers. API discovery does not live at the beginning of the end of the API lifecycle, but should be considered across all areas of the API lifecycle, ensuring that APIs, as well as the operations around them, are as discoverable as possible, but well informed when it comes to privacy, security, and terms of service. 

- **Search** - Ensuring APIs are always available via search helps make sure that APIs can be found by consumers, but also by other producers who are looking to develop similar APIs, making search for APIs, as well as the operations around each API a critical aspect of the API lifecycle that should be considered as early on in the design and development of an API, but at least as it is deployed into production. 
- **Networks** -  
null 
null 
