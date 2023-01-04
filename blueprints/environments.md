## Environments 
Every development, staging, or production environment used as part of API operations should be well-defined and possess a machine-readable artifact that codifies common variables including secrets, URLs, and other configuration that can be applied at build and runtime for each API. 

### Elements 
These are the elements of an environment, providing details needed to automate the execution of collections. 

- **Variables** - Key / value pairs of data that can be defined independently and stored within environments, but then applied across collections, providing variables that can be used for authentication, pagination, and other common aspects of working with APIs, allowing secrets to be abstracted away from each individual collection, but also other context that has little to do with the collection, or may define a state across multiple APIs and collections. 
- **Types** - Defines the XML Schema data types used by the web service, specifying a specific, existing, and well-known schema that provides a shared understanding. 
- **Initial Values** -  
- **Current Values** -  
 
### Engagement 
Environments provide a rich way of abstracting away and reusing common information and secrets across many different APIs. 

- **Fork** -  
- **Share** -  
- **Expore** -  
 
### Security 
Environments provide several beneficial security characteristics that are essential to stabilizing and securing API operations. 

- **Secrets** - Add a layer on top of environmental variables specifically for managing secrets, making sure you have clear visibility and control of secrets and tokens being applied. 
- **Roles** - Identifying the roles of each team member working on an API helps establish clear directives for who can make changes to an API, something that can drive and configure other elements applying to an API across the lifecycle. 
 
 
