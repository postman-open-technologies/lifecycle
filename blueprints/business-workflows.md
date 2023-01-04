## Business Workflows 
This API lifecycle blueprint focuses on defining common business workflows, then automating around these well-defined scenarios. Defining collections across multiple APIs, including authentication, scripting, data, Environment, then automating using monitors and pipelines. 

### Define 
Ensuring that operations supporting an API are properly defined, as well as what is needed to properly design and bring an API to life. A little planning and organization at this step of an APIs journey can go a long way towards ensuring the overall health and velocity of an API, and the applications that depend on this internal, partner, or public API. 

- **APIs** - Defining the APIs that are used as part of the business workflow, allowing multiple APIs to be used in a single workflow. 
- **Authentication** - Defining what authentication is in use across multiple APIs, and how the authentication will be handled as part of the workflow. 
- **Requests** - Which individual requests are needed to satisfy a specific set of business outcomes, providing the raw resources and capabilities needed. 
null 
### Design 
Having a formal process and approach to designing an API helps establish consistency and the precision of APIs in production, ensuring that APIs are developed using common patterns across an industry, and within an organization, establishing known practices for shaping the surface area and behaviors of APIs that applications are depending upon. 

- **Folders** - Logical separators within a collection for organizing and sequencing API requests for browsing by humans, but also automating with a runner or as part of a CI/CD pipeline, helping organize reference API collections, choreograph automation, and orchestrations across many different APIs as part of a single collection. 
- **Order** - Shaping the order in which each request is made, providing a logical framework for the business workflow to be executed, automated, and potentially reported upon, testing the business outcomes. 
null 
### Document 
Having complete, accurate, and easy to follow document is essential for all APIs, helping alleviate the number one pain point for API consumers when it comes to onboarding with an API, as well as expanding the number of API paths an application puts to work, making API documentation one of the most important areas of the API lifecycle. 

- **Workflow Documentation** - Documenting the workflow, as well as individual requests being made, ensuring that the end to end business workflow is well documented for anyone who is putting to work. 
null 
### Testing 
A test-driven API lifecycle ensures that each API accomplishes the intended purpose it was developed for, providing manual and automated ways to ensure an API hasn~t changed unexpectedly, is as performant as required, and meets the security expectations of everyone involved, helping establish a high quality of service consistently across all APIs. 

- **Workflow Testing** - Ensuring that every request in a workflow has the proper testing, making sure at a minimum a successful status code is being returned. 
null 
### Monitor 
All tests applied to an API should be monitored on a logical schedule and from relevant geographic regions, monitoring that APIs aren~t breaking their contract, falling below their agreed-upon service level agreement (SLA), or becoming a security risk, helping automate the quality of service across APIs in a way that allows teams to be as productive as possible. 

- **Workflow Testing Monitor** - Running each workflow using a scheduled monitor, either ensuring the business workflow is executed on a regular basis, or at least being tested for a successful outcome. 
- **Workflow Testing Monitor Results** - Ensuring that the results of each test run are being published somewhere, piped into APM, available via reporting, or pushed to a CDN, or other systems for aggregation and reporting. 
null 
 
