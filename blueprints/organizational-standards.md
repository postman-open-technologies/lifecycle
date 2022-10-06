# Organizational Standards
Every enterprise organization should have a set of standards they have adopted as part of API operations. There are plenty of redundant aspects of doing APIs that are easy to make consistent across APIs, things like pagination, sorting, filtering, usage of request bodies, HTTP methods, and error handling.

- **Headers** - Key / Value pairs of data that can be passed back and forth as part of API requests, confirming to the HTTP standard, and relying on the IANA registry of headers to define and shape the routing and prioritization of requests being made to APIs when using HTTP as the transport protocol between client and server.
- **Pagination** - Providing a standardized way of navigating through large sets of data and content via an API, limiting the results that are returned with each request, but providing consumers with visibility into how to navigate results and shape their API requests to achieve the most optimum outcomes for both API producer and consumer.
- **Schema** - Establishing common schema for each domain, using Internet and industry standards when possible, but then standardizing your own schema, stabilizing common objects, versioning and evolving them for reuse, then reference them in contracts and use them validation, documentation, testing, and other parts of the API lifecycle to help stabilize how data moves inside and outside the enterprise. 
- **Variables** - Defining a consistent set of variables that can be used to abstract away common properties that need to be used across different APIs, defining things like base URL, headers, secrets, and environmental, collection, or global values that are needed across many different APIs. 

Internet, industry, and organizational standards provide the base for the consistency and interoperability enterprise organizations need across their operations, helping make APIs more intuitive and speaking a common language, reducing friction for consumers putting to work in applications and integrations.