## AsyncAPI Contracts 
The AsyncAPI specification provides the ability to describe the surface area of your multi-protocol APIs using JSON or YAML. The open source specification provides a robust way to describe what is possible with each API, defining the surface area messages and channels, which can then be used as the source of truth for what is possible when publishing and subscribing to each asynchronous API. 

### Purpose 
This is the description 

- **Contracts** - Providing a machine-readable contract between API producer and consumer, outlining all the technical, but also business details of the relationship established when an API is published and made available for consumption. 
 
### Objects 
The AsyncAPI specification provides the ability to describe the surface area of your multi-protocol APIs using JSON or YAML. The open source specification provides
a robust way to describe what is possible with each API, defining the surface area messages and channels. It can then be used as the source of truth, showing what is possible when publishing and subscribing to each asynchronous API. 

- **Info** - Provides a place to define common metadata for an API, such as a name, description, licensing, terms of service, or contact information, helping to ensure all APIs have enough metadata available to articulate a purpose across the API life cycle. 
- **Applications** - An application is any kind of computer program or group of programs, allows for the view of a producer or a consumer, a microservice, an IoT device (sensor), or possibly a mainframe process that will be publishing and subscribing to messages. 
- **Producers** - A producer is a type of application connected to a server that creates messages and addresses them to a channel or publishes them to multiple channels, depending on the server, protocol, and use-case pattern applied as part of an API implementation. 
- **Consumers** - A consumer is a type of application connected to a server via a supported protocol that consumes messages from a channel or multiple channels, depending on the server, protocol, and use-case pattern in an API implementation. 
- **Message** - A message is a mechanism by which information is exchanged via a channel between servers and applications. The payload containing the data, defined by the application, MUST be serialized into JSON, XML, Avro, binary, or another format. 
- **Channel** - A channel is an addressable component made available by the server for the organization of messages, enabling producer applications to send messages to channels and consumer applications to consume messages from channels. 
- **Protocols** - A protocol is a mechanism (wireline protocol OR API) by which messages are exchanged between the application and the channel. Example protocols include, but are not limited to, AMQP, HTTP, JMS, Kafka, MQTT, STOMP, WebSocket. 
AsyncAPI provides business contracts for the many different channels you can publish or subscribe to across the enterprise, defining the events that matter to operations while also helping to ensure that the events and the messages passed along are well- defined and make sense to consumers.
As the API landscape has expanded across multiple protocols, AsyncAPI has emerged to quantify the landscape, helping us document, mock, test, and manage this growing layer that is a part of how we run our business. It ensures that the enterprise is delivering and responding to the most meaningful events. 
### Use Cases 
This is the description 

- **Documentation** - Documentation published as human consumable HTML pages help potential API consumers learn about what an API does by describing the paths, channels, parameters, headers, schema, messages, and other building blocks of APIs, showing examples of what is possible or by providing an API client to make calls to each API as part of the documentation. 
- **Code Generation** - With gRPC, you get a variety of client code out of the box in all of the top languages, providing high-quality code for developers to use in developing their applications using the industrial-grade API pattern. 
- **Type** -  
- **Approach** -  
- **Visiblity** -  
- **Maturity** - You should have a clear definition of what constitutes API maturity, while allowing for different levels of maturity to coexist with a balanced set of expectations. 
 
 
