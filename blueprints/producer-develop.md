## Producer - Develop 
This stage is about bringing an API to life. That means assembling all the infrastructure needed and generating any skeletons, using frameworks, assembling, and hardening an APIs functionality. The Development might take a design-led approach or a code-led approach. Either way, as long as it follows a common life cycle, it can benefit operations. 

### Elements 
 

- **Compute** - Establish a baseline for the underlying API compute, choosing among virtual servers, containers, and serverless to power each API. 
- **Database** - Provide the data storage and querying requirements for an API, leveraging a centralized database or establishing a database for use by this single API resource. 
- **DNS** - Apply a consistent approach to using DNS for each API, following a larger domain strategy but allowing for flexibility and redundancy in accessing each API.
 
- **Encryption** - Ensure that encryption is the default in transport and storage, and make sure each individual API applies these security controls from the beginning, not as an afterthought. 
- **Frameworks** - Generate frameworks as the scaffolding for each API, leveraging consistent approaches, avoiding redundant work and using the API contract to produce as much code as possible. 
- **Gateways** - Set up the gateway to prepare for an API deployment. Do the initial work to set up everything needed at the gateway layer, shifting as much of this work as far to the left in the life cycle as possible. 
- **Annotations** - Use code annotations to auto-generate the contracts you need to document, test, secure, and govern the API, leaning on a code-led approach to APIs. 
- **Integrated Development Environment (IDE)** - Maximize productivity across teams by providing further enablement via their trusted IDE, helping to increase developer productivity. 
- **Source Control** - Establish a Git repository for managing all the code and artifacts for an API. That will help you establish source control for each API early in the API life cycle. 
 
This stage of the life cycle tends to get the most attention in technical conversations about delivering APIs–doing the work to bring each API to life. A well-defined API life cycle makes the development stage as efficient as possible, with developers doing what they do best. 
