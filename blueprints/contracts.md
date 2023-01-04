## Contracts 
A handful of specifications have emerged that help us describe the surface area of our synchronous and asynchronous APIs. These specifications employ a mix of protocols, patterns, styles, and formats in the machine- and human-readable formats, which we can use to define the contracts available between producer and consumer. 

### Types 
These are the common types of contracts in use to define APIs. 

- **OpenAPI** - The OpenAPI specification, formerly known as Swagger, provides a machine- and human-readable format often used for describing HTTP 1.1, web, or REST APIs. It provides a contract for describing the relationship between API producer and consumer.
 
- **AsyncAPI** - The AsyncAPI specification is a sister specification to OpenAPI, but focused on event-driven APIs across HTTP, TCP, MQTT, and potentially HTTP/2 and HTTP/3. It provides a contract for describing the relationship between publishers, subscribers, and brokers. 
- **JSON Schema** - The JSON Schema specification is used for validating the models of data sent and received from APIs. It is also used by OpenAPI and AsyncAPI as vocabularies for modeling and validating the objects available via different types of APIs. 
- **Protocol Buffers** - Protocol buffers are Google’s language-neutral, platform- neutral, extensible mechanism for serializing structured data–think XML, but smaller, faster, and simpler. They are often used for high-speed internal APIs or B2B APIs for partners. 
- **Collections** - Collections are a machine-readable format from Postman for describing the surface area of APIs, then executing in service of the API lifecycle, providing mock servers, documentation, testing, and other developer needs across enterprise API operations. 
- **GraphQL** - GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data. GraphQL provides a complete and understandable description of the data in your API, giving clients the power to ask for exactly what they need and nothing more. 
- **WSDL** - Web Services Description Language, or WSDL, is an XML-based interface description language used for describing the functionality a web service offers. It provides a machine-readable description of how a service can be called and what kind of data it returns. 
 
API contracts provide both the technical and the business details of the relationship between API producer and consumer, moving everyone to a shared understanding of what can be expected with each version of an API. That includes the quality of service and the digital resources and capabilities that will be made available. The success of each API will depend heavily upon the balance between producer and consumer but also upon the business and technical aspects of conducting commerce online. 
