## Schema Registry 
A schema defines the structure and format of a data record. When different software or services use the same schema, they are able to communicate more effectively. API schemas like JSON Schema and OpenAPI are both human-readable and machine-readable, which makes them friendly to both developers and software. A schema registry serves as a central repository for storing and retrieving schemas. 

### Elements 
In order for applications to communicate with one another across your platform, you need a schema registry. Having a schema registry is especially important in event-driven architecture and streaming applications. 

- **Data sharing** - Multiple applications or services often use some of the same data. If you want applications to share data, they need to use the same schema. In an event-driven system, event publishers and consumers need to use the same schema. Every consumer of the shared data needs to understand the metadata, including field names and types. 
- **Data governance and validation** - The data format is a contract between API producers and API consumers, and using a schema registry helps maintain this contract. If a producer sends data that does not conform to the contract, consumers cannot interpret the event correctly. This can have major consequences if a producer pushes a breaking change that consumers are not prepared to handle. With a schema registry in place, changes that do not conform to the contract are not published. 
- **Backward and forward compatibility** - A schema registry maintains a versioned history, which makes schema evolution safer and allows producers and consumers to evolve at different times. When a schema evolves, there is a chance of breaking compatibility for consumers. A schema registry can allow older versions of the schema to be consumed, which maintains backward compatibility. 
- **Stream Processing** - When you configure stream processing, stream messages are not sent in containers. The consumer needs to know which schema the incoming data uses, but including the schema with every message adds overhead. By using a schema registry, messages can use a standardized schema and send only the relevant data in a smaller payload. 
- **Security** - You can use a schema registry to secure data by setting up access control. You can control access to the event producers as well as the schema registry itself. 
 
### How a schema registry works 
The schema registry defines the object schema for events, property names, and values. 

- **Event-driven Architecture** - In event-driven architecture, events are a data representation of actions taken within an application or by an external producer. Producers generate events, and consumers subscribe to these events so that they can receive updates and take action based on the new data. An event bus can be used to connect the events to the consumers. 
- **Schema registration** - A producer can register schemas using the schema registry API. Every registered schema gets a unique ID, and the schema registry maintains version history. When a new version of the same schema is registered, the original schema can still be used by any consumers that need it. 
- **Serialization and deserialization** - When a producer sends a message, it includes the schema ID of the schema that was used to serialize the message. When the consumer receives a message, it uses the schema registry to deserialize the message based on the schema ID it contains. 
 
### How to implement a schema registry 
There are a few different data sharing models you can use when implementing a schema registry. 

- **Hub to spoke** - In the hub-to-spoke model, a single schema registry is shared across an organization. Users throughout the organization can write to the main schema registry hub, and the hub replicates data to read-only spokes. Each different business units can use a spoke that serves only the schemas that they need. This model works well if the entire organization needs to reference shared data as it offers a single source of truth and a global data contract. 
- **Spoke to hub** - In the spoke-to-hub model, each business unit can read and write to their own schema registry spoke. The spokes replicate to a read-only schema registry hub. This allows each business unit to create and enforce their own data contracts and choose which schemas are shared with the rest of the organization. 
 
 
