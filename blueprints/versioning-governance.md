## Versioning Governance 
Kicking off API governance efforts by starting with versioning across APIs. Adopting a specific pattern to version all APIs, then work to govern that it is applied during the design, development, and delivery of APIs. Starting simple with API governance, establish a pattern and process, then expand API governance efforts once you have your legs under you. 

### Definitions 
You cannot govern APIs that do not have a definition, and OpenAPI is the preferred specification for defining the surface area of APIs. Any API being developed must have an OpenAPI available, either hand-crafted as part of a design-first approach, or generated from a gateway or code-first approach. With this definition, you will then be able to begin applying a consistent versioning approach, and then begin assessing whether or not versioning is being consistently applied across teams. 

- **OpenAPI** - The OpenAPI specification provides a common vocabulary for describing the surface area of request and response APIs, as well as webhooks, ensuring that API producers and consumers are on the same page when it comes to integration, but also helps stabilize multiple areas of the API lifecycle providing a contract that can be used for delivering documentation, mocks, testing, and more. 
null 
### Versioning 
Before you can govern the versioning of each API you have to have a formal approach for how you will apply versioning across APIs. Picking one of the most common approaches to version each API, working out the implementation details of the chosen pattern, and providing guidance for teams around why versioning is important, and how to implement it. There are two primary approaches to versioning that are adopted across leading APIs, making it an easy choice to find the patterns you need. 

- **Semantic Versioning** - Applying a dotted notion for defining major, minor, and patch versions of an API, articulating the different between a breaking change, and non-breaking or fixes to an API for errors that may have be introduced via previous versions. Providing a very structured way for defining, but also communicating change occurring with each individual API. 
- **Date-Based Versioning** - Applying a date to each version of an API, marking each change of an API with a date, allowing consumers to adopt an API on a specific date, integrate with it, and choose if they want to upgrade to the next version based upon the release date. Providing a simple way for defining change, and then communicating it with consumers. 
null 
### Linting 
With an OpenAPI for each API, and a versioning pattern adopted, you can lint for this pattern across each API using a rules-based approach to governance. Leveraging the open-source tool Spectral to define a machine-readable rule that matches the versioning pattern adopted, and then ensuring the OpenAPI for each API possesses the pattern during design, development, and build time. Codifying governance rules, and then automating how they are applied to ensure that versioning is consistently applied across operations. 

- **Rules** - Machine readable rules in YAML or JSON that can be used to lint any other YAML or JSON artifact, allowing for common or specialized rules to be established to help check for consistency in the design, development, deployment, and management of APIs, helping codify standards and health practices for delivering APIs into the API lifecycle across domains and teams. 
null 
### Automation 
With API versioning governance in place, it can now be automated as part of operations, ensuring the coverage of governance across teams. Providing the ability to lint for version governance rules, but eventually many other rules at the various stages of the lifecycle. Defining API governance in a centralized way, but then equipping development teams to apply it as part of their regular workflows, automating how governance is implemented, and pushing for 100% coverage of API versioning governance across operations. 

- **Design-Time Governance** -  
- **Runner Governance** -  
- **Command Line Interface (CLI) Governance** -  
- **IDE Governance** - Governance can be applied at the integrated development environment (IDE) level, enforcing API governance locally during development, ensuring that APIs are 100% compliant with rules, contract, and script-based API governance established centrally as part of broader governance efforts. 
- **CI/CD Governance** -  
null 
 
