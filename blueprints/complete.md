## Complete 
This is my master definition of the API lifecycle. 

### Define 
 

- **Domains** - The establishment of domains within the enterprise, allowing for logical separation of business concerns as dictated by the domain experts, helps prevent information overload, unnecessary dependencies, and other challenges that arise due to sprawl and complexity across the enterprise. 
- **Regions** - Identify the region(s) where an API will operate so that you can comply with regulations and other business requirements and ensure that APIs are as close to consumers as possible. 
- **Requirements** - The detailed requirements behind an API, defining the business needs of a API-driven digital product. 
- **Workspaces** - A virtual space for doing API work, providing a location that has a name, description, and private, team, partner, or public visibility, where work on APIs, collections, mock servers, environments, monitors, and other elements of API operations can exist, providing a single location for API producers and consumers to engage across the API lifecycle, and move APIs forward in a collaborative way. 
- **Source Control** - A systems responsible for managing changes to computer programs, documents, large websites, APIs and other collections of information, providing a single source of truth for the code, artifacts and other assets powering API integrations and deployments, and details about each branch, commit, and conversation involved with move each individual API forward. 
- **Teams** - The team of people who are behind API operations, providing name, role, and other relevant details about who they are and what they will be contributing to API operations, helping manage the human side of operations, allowing hundreds or thousands of team members to be organized and managed for optimal delivery and consumption of APIs across operations. 
- **Stakeholders** - Everyone who will be involved in the development and operation of an API, bringing in anyone who will have a stake or dependency when an API is supported. 
 
### Design 
 

- **Source Control** - A systems responsible for managing changes to computer programs, documents, large websites, APIs and other collections of information, providing a single source of truth for the code, artifacts and other assets powering API integrations and deployments, and details about each branch, commit, and conversation involved with move each individual API forward. 
- **Contracts** - Providing a machine-readable contract between API producer and consumer, outlining all the technical, but also business details of the relationship established when an API is published and made available for consumption. 
- **Schema** - Defining all objects use as part of API operations using JSON Schema provides for a definitions that can be used as part of modeling and the API design process, as well as for validation at development, build, or even run time. 
- **Reference Documentation** - It is helpful for API consumers to have complete documentation for the entire surface area of an API, providing a complete reference of what is possible with an API to help consumers explore every path, parameter, schema, and other details of how an API works, making the resources and capabilities available within API something consumers can find and put to use without much work. 
- **Mock Servers** - A mock server helps replicate as much of the functionality and API would have in production, before the time to actually have to write any code, making APIs be more tangible and real early on in the lifecycle, allowing teams to rapidly design an API that meets the needs of everyone involved, providing usable elements that power design, documentation, testing, and other elements of the API lifecycle. 
- **Variables** - Key / value pairs of data that can be defined independently and stored within environments, but then applied across collections, providing variables that can be used for authentication, pagination, and other common aspects of working with APIs, allowing secrets to be abstracted away from each individual collection, but also other context that has little to do with the collection, or may define a state across multiple APIs and collections. 
- **Environments** - Machine-readable environments for APIs allow for abstracting away common elements of an API environment from the definition of each API, allowing different environments to be paired with OpenAPI and collections for each API at design, development, and build time. 
 
### Develop 
 

- **Source Control** - A systems responsible for managing changes to computer programs, documents, large websites, APIs and other collections of information, providing a single source of truth for the code, artifacts and other assets powering API integrations and deployments, and details about each branch, commit, and conversation involved with move each individual API forward. 
- **Integrated Development Environment (IDE)** - Maximize productivity across teams by providing further enablement via their trusted IDE, helping to increase developer productivity. 
- **Command Line Interface (CLI)** - Needs a description for this elements 
- **Compute** - Establish a baseline for the underlying API compute, choosing among virtual servers, containers, and serverless to power each API. 
- **Storage** -  
- **Database** - Provide the data storage and querying requirements for an API, leveraging a centralized database or establishing a database for use by this single API resource. 
- **Gateway** - Provide the data storage and querying requirements for an API, leveraging a centralized database or establishing a database for use by this single API resource. 
 
### Test 
 

- **Contract Testing** - Contract tests can be derived from API artifacts like OpenAPI, JSON Schema, and GraphQL, and used to ensure there are no changes to what has been promised when an API was designed or developed, providing a repeatable test that can be run manually, on a schedule from multiple regions, or as part of a CI/CD pipeline to ensure contracts with consumers are upheld. 
- **Performance Testing** - Performance tests can be defined as individual tests using collections, pulling from one or many individual API paths and measuring the time it takes for the response to be sent, providing a test that can be run manually, scheduled across multiple geographic regions, or executed as part of a CI/CD pipeline, helping ensure an API is always meeting it~s expected performance benchmarks. 
- **Integration Testing** - Integration tests can be defined for any API using executable and shareable collections, testing integrations, as well as other more custom scenarios or business approaches, providing a single or suite of integration tests that can be manually run, scheduled across multiple regions, or executed as part of a CI/CD pipeline, automating integration testing consistently across APIs. 
- **Platform Testing** -  
- **Governance Testing** -  
- **Monitors** - Monitoring any process across API operations defined as a collection, then bundled with any environment, setting a schedule for the execution of the collection, and viewing or publishing of the results to any other location, providing a very wide definition of what monitoring can mean across API operations. 
 
### Secure 
 

- **Authentication** - The consistent application of standard authentication as part of a standardized API management layer strikes a balance between access to digital resources and ensuring that undesirable actors do not have access to valuable assets. 
- **Authorization** - Once a user is authenticated, the authorization layer will make sure they only have access to approved resources. 
- **Environments** - Machine-readable environments for APIs allow for abstracting away common elements of an API environment from the definition of each API, allowing different environments to be paired with OpenAPI and collections for each API at design, development, and build time. 
- **Role-Based Access Control (RBAC)** -  
- **Fuzzing** -  
 
### Deploy 
 

- **Source Control** - A systems responsible for managing changes to computer programs, documents, large websites, APIs and other collections of information, providing a single source of truth for the code, artifacts and other assets powering API integrations and deployments, and details about each branch, commit, and conversation involved with move each individual API forward. 
- **Artifacts** - Machine-readable artifacts create and generated as part of the design, development, deployment, operation, and deprecation of APIs to power applications and integrations, providing important metadata regarding every stop along the API lifecycle that can be used to make decisions. 
- **CI/CD** - Operating in a state of continuous integration and continuous deployment involving APIs, ensuring that the process involved with consuming and producing APIs are as reliable, high quality, and resulting in consistent outcomes that benefit everyone involved, and powers useful applications. 
- **Servers** - A piece of computer hardware or software (computer program) that provides functionality for other programs or devices, called "clients", utilizing a client?server model to provide various functionalities, often called "services", such as sharing data or resources among multiple clients, or performing computation for a client. 
- **Gateways** - API gateways provide a centralized or federated approach to the deployment and management of APIs at scale across an organization, leveraging commercial or open-source API gateways to deploy APIs into development, staging, production, or other environments, allowing for the standardization of common elements of API management, and configuring APIs using common policies. 
- **Contract Tests** -  
- **Security Tests** -  
- **Platform Tests** -  
- **Governance Tests** -  
 
### Observe 
 

- **Usage** - Once an API is implemented into production code, a developer decides whether to deepen adoption of your API. They might increase traffic or accommodate other user scenarios. This is when developers take a hard look at latency, responsiveness, flexibility, and scalability. 
- **Monitors** - Monitoring any process across API operations defined as a collection, then bundled with any environment, setting a schedule for the execution of the collection, and viewing or publishing of the results to any other location, providing a very wide definition of what monitoring can mean across API operations. 
- **Application Performance Management (APM)** - The monitoring and management of performance and availability of APIs, actively detecting and diagnosing performance problems to maintain an expected level of service, translating API operational metrics into business meaning value at scale across hundreds or thousands of internal or external APIs. 
- **Notifications** - Providing notifications about activity around the operation of any API, allowing for in-application, email, or type of message via integration with common platforms, providing real-time updates about what is happening across API operations. 
- **Reports** - Visual reports that aggregate data from across operations, making APIs and the operations around them something that team members can see activity, history, and other dimension of what is happening across API operations, allowing different views to be organized and presented via dashboards. 
- **Forks** - Making a linked copy of an API, or the mocks, documentation, tests, and other areas of the lifecycle defined as a collection to another workspace, allowing anyone to run on their own, make changes and enhancements, then if they desire, contribute back to the original and receive regular updates over time. 
- **Watches** - Keeping track of the watches on workspaces, APIs, and collections to understand who is tuned into what is happening. Use watches as a
metric for the number of consumers, contributors, and internal and external stakeholders who are tuned in. 
 
### Distribute 
 

- **Networks** -  
- **Portals** - An API deployed into production should be published to the central portal, providing centralized access for internal or external consumers through a single doorway that can be supported as part of overall API operations. 
- **Documentation** - Documentation published as human consumable HTML pages help potential API consumers learn about what an API does by describing the paths, channels, parameters, headers, schema, messages, and other building blocks of APIs, showing examples of what is possible or by providing an API client to make calls to each API as part of the documentation. 
- **SDKs** - You can generate complete software development kits, abstracting away the authentication and other complex aspects of deploying APIs. You always want to reduce the workload for consumers, easing integration of your APIs into their applications. 
- **Buttons** - The documentation, tests, and workspace behind an API should be made available via blog posts, videos, wikis, and other resources to support APIs. Use embeddable and actionable buttons that consumers can activate with one click. 
- **Blog Posts ** -  
- **Education** - The API life cycle provides a significant opportunity for making API education more modular and snackable. In addition to shifting left, you will make g API and life cycle literacy available at every stage of the process. 
 
 
