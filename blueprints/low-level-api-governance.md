## Low Level API Governance 
A blueprint for approaching the governance of APIs beginning with each individual API by individual developers, setting API governance into motion at the lowest level by a single or group of developers, acknowledging that governance will only get you so far at this level, but in many organizations, it might sense to start at this level. 

### Definition 
You can~t govern what you don~t have defined, and to be able to begin governing the design of your APIs you will need to have machine-readable artifacts that you can lint as part of the design, development, or build process. Establishing a set of artifacts that help drive the API lifecycle, but also make it something that can be measured and reported upon as part of governance activities. 

- **OpenAPI** - The OpenAPI specification provides a common vocabulary for describing the surface area of request and response APIs, as well as webhooks, ensuring that API producers and consumers are on the same page when it comes to integration, but also helps stabilize multiple areas of the API lifecycle providing a contract that can be used for delivering documentation, mocks, testing, and more. 
- **AsyncAPI** - AsyncAPI is a machine-readable specification for describing the surface area of your asynchronous APIs. OpenAPI is meant for describing synchronous APIs like REST using HTTP, and AsymcAPI is for describing WebSockets, MQTT, Kafka, NATS, and other synchronous, event-driven, and message APIs. 
null 
### Rules 
API governance rules codify what API governance is as it is applied as part of the design, development, and build process on the ground floor of API operations. Rules provide the benchmark for what governance is across teams, and provide an artifact that can be applied across the API lifecycle by individual designers and developers, and eventually baked into the pipelines that move API infrastructure forward. Rules should reflect what is happening on the ground today, but apply enforcement as part of a forward motion, acknowledging that legacy APIs may not always rise to the level of governance and organization is moving towards. 

- **Design Rules** - Machine-readable rules that can be applied at design, development, or build time to govern the design of each API, evaluating artifacts to ensure that specific design patterns are followed when crafting each API, helping make sure that APIs follow common API patterns within an industry, or as defined by the enterprise organization. 
- **Documentation Rules** - Machine-readable or codified rules that govern whether or not documentation exists for each API, making sure there is accessible HTML documentation available for API consumers, and even validating there are examples and other specific parts of API documentation present. 
- **Testing Rules** - Having machine readable or codified rules that ensure there is required testing in place for all APIs helps make sure that a baseline set of tests exist across all APIs, ensuring that contracts are upheld, integrations are maintained, performance is at acceptable levels, and there are not security vulnerabilities present in any API in production. 
null 
### Automation 
To realize governance across operations it is important that governance is applied in automated ways at different areas of the API lifecycle, helping ensure API governance can be applied early on in the lifecycle but is also available throughout the development and delivery of APIs, and when it makes sense bake it into the build process ensuring that governance is applied by default as every API moves into production. Helping ensure that teams aren~t doing extra work to realize governance across operations, and it is just at their fingertips as they are designed, developing, and building APIs as part of their regular day. 

- **Design Time Governance** - Governance can be applied and automated at design time, providing real-time or manually triggered application of governance rules, contracts, and scripts, providing a tighter feedback loop with API designers in regards to the guidance around what is expected of the design of each API. 
- **Collection Governance** - A Postman collection for applying governance provides a flexible way to apply rules, schema, or script-based governance, allowing governance to be defined as modular collections which can be manually run by developers, scheduled using a monitor, or easily dropped into a CI/CD pipeline. 
- **CLI Governance** - Governance can be applied at the command line interface (CLI) level, enforcing API governance locally during development, ensuring that APIs are 100% compliant with rules, contract, and script-based API governance established centrally as part of broader governance efforts. 
- **IDE Governance** - Governance can be applied at the integrated development environment (IDE) level, enforcing API governance locally during development, ensuring that APIs are 100% compliant with rules, contract, and script-based API governance established centrally as part of broader governance efforts. 
- **Pipeline Governance** - Governance can be applied at the pipeline level, enforcing API governance at build time, ensuring that APIs are 100% compliant with rules, contract, and script-based API governance established centrally as part of broader governance efforts, working to automate the testing of the surface area of APIs, and other parts of operations in service of platform-wide API governance efforts. 
null 
### Reports 
Reporting on the realities and outcomes of API governance across the API lifecycle is needed to make it more visual and tangible for everyone involved. Reporting across governance being applied to individual APIs, groups of APIs, and overall operations can be realized as part of native platform reporting, customized, localized, or in aggregate with Postman Visualizer, or made seamless with existing operations by piping data into APM and other systems to make available for reporting and visualizations via dashboards. 

- **APM** -  
- **Reports** - Visual reports that aggregate data from across operations, making APIs and the operations around them something that team members can see activity, history, and other dimension of what is happening across API operations, allowing different views to be organized and presented via dashboards. 
null 
 
