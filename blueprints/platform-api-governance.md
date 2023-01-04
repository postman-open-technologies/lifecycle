## Platform API Governance 
Leveraging a common platform workspace blueprint to define, develop, manage, observe and govern each API, providing the consistency needed to properly govern each individual API at scale across operations. 

### API Definition (DISCOVERY) 
One reason we see enterprise organizations struggle with their API governance is the lack of discovery that exists across not just APIs, but also artifacts, documentation, and all the other work occurring around each API. You simply cannot govern what you can’t find, and the more visible APIs and the operations are behind them are, the more likely you will be able to make API governance take root.  

- **Workspace** - Ensure that every API has a private, partner, or public workspace to access the operations surrounding each API. 
- **OpenAPI** - Ensure there is always a human and machine-readable API artifact available as the source of truth for each API. 
- **Repository** - Establish a Git repository for each API, syncing OpenAPI and collections to the repository as part of the lifecycle. 
- **Environment** - Provide development, staging production, and other environments available to apply manually or automatically.
 
- **Documentation Examples** - Requiring that all APIs have complete and up-to-date documentation available to demonstrate what is possible. 
- **Team** - Having the team behind each API available as a list, providing name, and contact information for consumers to use. 
This is the foundation for your API governance. Every API should possess these elements, and there should be a blueprint for teams to follow when it comes to setting up new APIs and bringing existing APIs up to current standards. Investment in these areas will make API governance possible in the area of design and other aspects of API operations. Once you get a handle in these areas and realize that each has APIs of its own, you’ll see entirely new ways you can elevate API governance efforts across your teams. 
### API Instance (RELIABILITY) 
The next area we are looking to include as part of API governance is the overall reliability of each instance of an API. We want to provide a baseline set of tests across all APIs. This ensures that the business purpose for each API is being realized, but also that it is done in a way that meets service level agreements (SLA) and doesn’t introduce any vulnerabilities or security issues into operations. It’s key to establish common ways in which teams can confidently deliver and operate reliable API instructors behind our applications and integrations. 

- **Contract Testing** - Contract tests can be derived from API artifacts like OpenAPI, JSON Schema, and GraphQL, and used to ensure there are no changes to what has been promised when an API was designed or developed, providing a repeatable test that can be run manually, on a schedule from multiple regions, or as part of a CI/CD pipeline to ensure contracts with consumers are upheld. 
- **Performance Testing** - Performance tests can be defined as individual tests using collections, pulling from one or many individual API paths and measuring the time it takes for the response to be sent, providing a test that can be run manually, scheduled across multiple geographic regions, or executed as part of a CI/CD pipeline, helping ensure an API is always meeting it~s expected performance benchmarks. 
- **Security Testing** - Security tests can be defined for any API using executable and shareable collections, testing for common OWASP vulnerabilities, as well as other more custom scenarios or business approaches, providing a single or suite of security tests that can be manually run, scheduled across multiple regions, or executed as part of a CI/CD pipeline, automating security consistently across APIs. 
This dimension of API governance historically lives under quality, testing, and other areas of operations, but it makes a lot of sense to consider this as part of the API governance stack. This places reliability as part of governance and allows us to use the same artifacts and tooling we are using for testing to govern our APIs and the API operations around them. We can test the instances of our APIs, the surface area of those APIs, and the operations and infrastructure that move those APIs forward across a well-known API lifecycle. 
### API Design (CONSISTENCY) 
Now we get to the portion of platform governance that people usually talk about when it comes to API governance—governing the design of your API. API design governance is about making sure the technical details of the surface area of your API are as consistent as possible, no matter which team designed and developed the API. This is an area of API governance that we feel is important. Still, it is also one that becomes more difficult without a single source of truth (OpenAPI) in a known workspace. It can quickly become a rabbit hole when it comes to thinking about all the different ways you can lint the OpenAPI for your API—so we recommend starting small. 

- **Info** - Ensure that there are title, description, and other essential information properties. 
- **Versioning** - Require a standard semantic or date-based versioning applied to each API. 
- **Operations** - Make sure each individual operation has a summary, description, and id. 
- **Parameters** - Standardize the format of parameter names, and all have descriptions. 
- **Responses** - Push for a common set of status codes, media types, and schema responses. 
- **Schema** - Standardize all request and response schema using JSON Schema components. 
There are plenty of other governance rules that can be applied at this level, but this provides an introductory set of concerns that should be addressed early on as part of API governance efforts. Teams will learn a lot by ensuring that these simple rules are consistently applied across API operations, enabling all teams to apply governance manually using collection runners, scheduling using monitors, or baked into CI/CD pipelines. We’re able to use the same infrastructure we are using to test each API instance to test the surface area of the API for consistent design across any team.
 
### API Operations (DELIVERY) 
API governance isn’t something you do once and step away from. It’s something that is ongoing and should be wired up to your existing software development lifecycle and monitored in real time. Operational governance allows us to automate the reliability and consistency portions of our governance, but through additional PlatformOps collection integrations, we can configure, optimize, and automate our gateway, portals, documentation, and other building blocks of API operations. We then leverage the same infrastructure we are using to test individual APIs to also “test” the surface area of our APIs and the operations that surround them. 

- **Monitors** - Ensure you are monitoring operations and paying attention even when the team is off doing other things. 
- **Pipeline** - Ensure you are applying governance at the CI/CD pipeline layer, running the contract, security, and governance tests with each build. 
- **Gateway** - Govern the deployment of APIs via gateways, allowing for manual and automated configuration and observability to occur. 
The governance of operations doesn’t stop at just monitoring our testing, security, and design governance. Baking it into our CI/CD pipeline, we can extend this to other operational areas. The same collection-based approach we are using to test each instance of API and to govern API design can be used to validate that documentation is complete and updated, possesses examples, and always has SDKs and code snippets automatically generated. When you realize that your API operations themselves have APIs, your approach to API governance becomes much broader than just the design of your APIs. Your teams can become more productive and realize higher levels of quality—all while fulfilling governance at scale.
 
### API Reporting (OBSERVABILITY) 
The final and essential area of API governance needed to achieve the best results at scale across business domains and teams: make sure everything is as observable as possible. Provide real-time reporting and activity visibility for each API, but also take more advantage of platform integrations to feed everything into existing API infrastructure. Operations around APIs then have the necessary observability, and governance itself becomes as observable as possible in real time. 

- **Reporting** -  Leverage native reporting to understand what is happening with each API in use as part of API operations. 
- **APM** - Use monitors to pipe the results of collection runs into DataDog to make the API observable. 
- **Activity** - Understand how the workspace, APIs, collections, monitors, and other elements are being configured as part of your work. 
Collections provide connections to APIs and can be monitored on a schedule, integrated into CI/CD pipelines, and can make the API lifecycle and governance more observable. Collections are the gears of our API operations: use them to define, automate, and make everything observable via native integrations and PlatformOps collections in service of platform API governance.   
null 
