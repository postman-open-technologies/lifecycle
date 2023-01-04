## Performance Testing 
Performance testing checks the availability and response time of each individual API, often selecting specific paths of an API, and testing how long it takes to make a request and receive a response, or publish and subscribe to messages. Considering the responsiveness of the API, but also potentially the network in between consumers and the API, gateway, and other influencing aspects of how APIs operate. Helping understand over time how performant each API is, keeping a record of the uptime and availability, but also making sure the API meets the expected SLA from the regions that matter most to consumers. 

### Elements 
These are the elements of API performance. 

- **Testing** - Developing Individual tests using scripts that evaluate and attempt to make specific assertions about responses returned from APIs, or the operations surrounding APIs, providing very modular tests for specific outcomes or series of outcomes, then manually executing, or automating using monitors and CI/CD pipelines, evaluating and storing the individual results, but also using in aggregate to understand the productivity, quality, and overall governance of a system. 
- **Collections** - A machine-readable artifact that acts as a container for storing and organizing multiple API requests, providing an executable, self-documented reference for a complete API, a subset of an API, as well as workflows containing multiple requests from across many different APIs in a specific order, with a precise business function. 
- **Authentication** - The consistent application of standard authentication as part of a standardized API management layer strikes a balance between access to digital resources and ensuring that undesirable actors do not have access to valuable assets. 
- **Scripts** - Lightweight scripts that can be run as part of each API request, providing pre-request scripting, or post-request scripting that help appy business logic at either end of the request, helping transform, test, and automate with each API request. 
- **Environments** - Machine-readable environments for APIs allow for abstracting away common elements of an API environment from the definition of each API, allowing different environments to be paired with OpenAPI and collections for each API at design, development, and build time. 
- **Regions** - Identify the region(s) where an API will operate so that you can comply with regulations and other business requirements and ensure that APIs are as close to consumers as possible. 
 
### Automation 
These are the ways that API performance testing can be automated. 

- **Runners** - Acknowledge that some collection applications will be manually
run by different team members using runners, organizing different types of integrations and applications by workspaces and letting different stakeholders manually put them to work. 
- **Monitors** - Monitoring any process across API operations defined as a collection, then bundled with any environment, setting a schedule for the execution of the collection, and viewing or publishing of the results to any other location, providing a very wide definition of what monitoring can mean across API operations. 
- **Pipelines** -  
 
null 
