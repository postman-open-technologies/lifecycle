## Contract Testing 
Contract testing takes the machine-readable contract for an API and then tests each instance of that contract, ensuring the requests and responses, messages, and other details match the contract defined. Providing an executable set of tests that will validate the contract for each API manually as part of producing or consuming the API, enforced as part of the CI/CD pipeline, or scheduled to run from different regions via the monitor.  

### Contracts 
These are the contracts that are often used as part of testing APIs. 

- **OpenAPI** - The OpenAPI specification provides a common vocabulary for describing the surface area of request and response APIs, as well as webhooks, ensuring that API producers and consumers are on the same page when it comes to integration, but also helps stabilize multiple areas of the API lifecycle providing a contract that can be used for delivering documentation, mocks, testing, and more. 
- **JSON Schema** - JSON Schema is a vocabulary that allows you to annotate and validate JSON documents., allowing you to model objects and then validate those objects as part of the design, delivery, and operation of APIs, providing a way to describe and validate the digital payload behind applications and integrations. 
- **Collections** - A machine-readable artifact that acts as a container for storing and organizing multiple API requests, providing an executable, self-documented reference for a complete API, a subset of an API, as well as workflows containing multiple requests from across many different APIs in a specific order, with a precise business function. 
 
### Testing 
The testing portion of the equation. 

- **Scripts** - Lightweight scripts that can be run as part of each API request, providing pre-request scripting, or post-request scripting that help appy business logic at either end of the request, helping transform, test, and automate with each API request. 
- **AJV** -  
 
### Automation 
How are you automating contract tests. 

- **Runners** - Acknowledge that some collection applications will be manually
run by different team members using runners, organizing different types of integrations and applications by workspaces and letting different stakeholders manually put them to work. 
- **Monitors** - Monitoring any process across API operations defined as a collection, then bundled with any environment, setting a schedule for the execution of the collection, and viewing or publishing of the results to any other location, providing a very wide definition of what monitoring can mean across API operations. 
- **CI/CD** - Operating in a state of continuous integration and continuous deployment involving APIs, ensuring that the process involved with consuming and producing APIs are as reliable, high quality, and resulting in consistent outcomes that benefit everyone involved, and powers useful applications. 
 
### Results 
What are you doing with the results. 

- **APM** -  
- **Reports** - Visual reports that aggregate data from across operations, making APIs and the operations around them something that team members can see activity, history, and other dimension of what is happening across API operations, allowing different views to be organized and presented via dashboards. 
 
Contract testing is a great place to start when it comes to testing, because it helps set the low bar for what is testing across all teams, and introduces and stabilizes the concept of contracts while making a tangible difference in quality across operations. 
