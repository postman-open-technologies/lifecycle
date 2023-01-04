## Organizing Your Standards 
Every organization should have a set of standards for API operations. There are plenty of redundant aspects of doing APIs that are easy to make consistent–things like vocabulary, pagination, sorting, filtering, usage of request bodies, HTTP methods, and error handling. A little standardization in these areas can go a long way towards stabilizing the development and delivery of r your APIs, making your consumers’ lives easier along the way. 

### Elements 
 

- **Vocabulary** - Establish a common vocabulary for naming things, then sharei that vocabulary across teams to standardize and optimize the way you talk about APIs. Getting teams to use the same language throughout their work will help reduce the friction associated with forward motion.
 
- **Headers** - Headers are key-value pairs of data that can be passed back and forth as part of API requests. They conform to the HTTP standard and rely on the IANA registry of headers to define the routing and prioritization of requests made to APIs when using HTTP as the transport protocol between client and server. 
- **Pagination** - Pagination provides a standardized way of navigating large sets of data and content via an API. It limits the results returned with each request, but provides consumers with visibility for navigating i results and shaping their API requests to achieve optimum outcomes for API producers and consumers. 
- **Schema** - Establish a common schema for each domain, using internet and industry standards when possible, but then standardize your own schema, stabilizing common objects and versioning and evolving them for reuse.Then reference them in contracts and use them for validation, documentation, testing, and other parts of the API life cycle to stabilize how data moves inside and outside the enterprise. 
- **Variables** - Define a consistent set of variables that can be used to abstract away common properties for use across different APIs. You can define things like base URL, headers, secrets, and environmental, collection, or global values that are needed across many different APIs. 
 
Internet, industry, and organizational standards provide the base for the consistency and interoperability across enterprise operations. These standards make APIs more intuitive and help them speak a common language, reducing friction for consumers who put them to work in applications and integrations.
This is by no means meant to be a complete list of things you should be standardizing in your organization. This blueprint is just designed to remind you that you need to be standardizing as part of your regular operations. The items listed here reflect the most common areas I see among API-aware and API-first organizations that are finding success. By employing some simple standardization measures, they are accelerating the velocity of their API-first transformation. 
