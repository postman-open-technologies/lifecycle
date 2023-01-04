## Reference Collections 
Every API needs to have a complete reference collection available for consumers. Providing an always up-to-date reference of every detail of an API, what it does, and how developers can put it to use. Ensuring there is a detailed record that can be used for the documentation but then also producing other types of onboarding, capability, workflow, and other types of collections that will be needed. 

### Purpose 
The most common type of collection you see emerge from API producers is what is called a reference collection. An approach that reflects most OpenAPI powered documentation you come across, but is available in a more portable, shareable, and forkable format. Reference API collections provide a complete catalog of paths available as part of the operation of an API, providing the full menu of what is possible for consumers. Providing a central source of truth that can be used for documentation, but also used to produce other types of collections for onboarding, workflows, and other use cases. The purpose of a reference collection is to provide a single comprehensive look at an API, which can then be commented upon, watched, and forked by consumers, providing them with the complete reference of what is possible with an API. 

- **Secrets** - Add a layer on top of environmental variables specifically for managing secrets, making sure you have clear visibility and control of secrets and tokens being applied. 
- **Variables** - Key / value pairs of data that can be defined independently and stored within environments, but then applied across collections, providing variables that can be used for authentication, pagination, and other common aspects of working with APIs, allowing secrets to be abstracted away from each individual collection, but also other context that has little to do with the collection, or may define a state across multiple APIs and collections. 
null 
### Structure 
If you have ever generated a reference collection from an OpenAPI you know there are several ways in which you can dictate the structure of the collections. Collections are intended to be a more executable representation of an API, providing an accounting of all paths, parameters, and other technical details, but organized in a way that allows for actual use within a specific environment. Reference collections provide authentication details and organize requests by logical folders that speak to how consumers will be needing to learn about what an API does. Ensuring there are always examples for every request and response, allowing consumers to fork the reference collection, generate a mock server, and play with each individual API without having to actually make live calls to the API, helping make onboarding and exploration a more hands-on experience. 

- **Folders** - The ability to organize API requests into folders, nesting and organizing them, helps reduce the cognitive load when it comes to getting up and running with an API. 
- **Methods** -  Being able to define GET, POST, PUT, PATCH, and DELETE HTTP verbs specifies the vocabulary nuance of different API paths, allowing each resource to be properly understood and executed as part of a collection. 
- **Path Parameters** - Defining the parameters that are used in the path of each API request provides a dynamic element to returning the results users are looking to receive. 
- **Query Parameters** - Being able to define each of the individual query parameters that can be passed as part of each API request allows users to shape requests to get the data and content they need. 
- **Authorization** - The ability to authenticate with APIs using any of the common patterns, including, but not limited to API keys, OAuth, Basic Auth, AWS Auth, and more keeps API access from collections secure. 
- **Headers** - Allowing API collection creators and users to add and manage the headers that are passed in with each request controls structure and routing, determining how an API is engaged with. 
- **Body** - Providing full control over the body for each request allows the collection creator or user to maximize the ways in which POST and PUT requests are put to use in a collection. 
- **Cookies** - Mimicking the behavior across websites by allowing cookies to be included along with each request acknowledges that APIs are an evolution of the web, and that JSON, XML, CSV, and HTML are relevant responses. 
- **Examples** - Each API request and response can be accompanied by examples which can be used in documentation or mock APIs.
 
null 
### Environment 
Text 

- **Secrets** - Add a layer on top of environmental variables specifically for managing secrets, making sure you have clear visibility and control of secrets and tokens being applied. 
- **Variables** - Key / value pairs of data that can be defined independently and stored within environments, but then applied across collections, providing variables that can be used for authentication, pagination, and other common aspects of working with APIs, allowing secrets to be abstracted away from each individual collection, but also other context that has little to do with the collection, or may define a state across multiple APIs and collections. 
null 
### Engagement 
Reference collections provide us with a tremendous opportunity for engagement between API producers and consumers. Moving beyond historic approaches to publishing static or even dynamic documentation to a developer portal, reference collections provide you with all the information you need, but in a much more collaborative and portable format. Reference collections can be quickly shared via URL, published to a website, blog, and other locations using a Run in Postman button. These collections can also be watched, forked, and have pull requests submitted, allowing API producers to potentially merge changes and updates made by consumers into the central set of API references. All of this is changing how we engage around our APIs, but also documentation, making it much more hands-on and accommodating to the distributed and fast-moving API world we all live in. 

- **Watches** - Keeping track of the watches on workspaces, APIs, and collections to understand who is tuned into what is happening. Use watches as a
metric for the number of consumers, contributors, and internal and external stakeholders who are tuned in. 
- **Forks** - Making a linked copy of an API, or the mocks, documentation, tests, and other areas of the lifecycle defined as a collection to another workspace, allowing anyone to run on their own, make changes and enhancements, then if they desire, contribute back to the original and receive regular updates over time. 
- **Comments** - Comments on APIs, collections and other elements of API operations allow for more tightly coupled and inline conversations to occur around entire elements or specific parts and pieces of elements, allowing teams to collaborate and communicate across the API lifecycle. 
null 
 
