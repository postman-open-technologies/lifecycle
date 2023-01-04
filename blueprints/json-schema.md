## JSON Schema 
The JSON Schema specification provides a machine and human-readable way for describing digital objects that are used as part of API requests and responses, as well as the messages we publish and subscribe to our more asynchronous APIs. Providing us with a way to describe the structure of our digital resources and capabilities in a way that we can validate during design, development, or while in production. 

### Purpose 
JSON Schema is ubiquitous across the enterprise API landscape, but something so common that most developers do not even see it, they often just see a configuration file for the tooling they are putting to work.  In practice JSON Schema is essential to how the enterprise works today across infrastructure and applications. 

- **Contracts** - JSON Schema provides a contract for the objects passed back and forth between APIs, helping standardize how we define the digital bits we depend on doing business. 
- **Digital Objects** - Enterprise operations is made up of digital objects and JSON Schema is how you define and make these objects discoverable and something everyone can agree upon across operations in a machine-readable way. 
 
### Elements 
The JSON Schema specification provides a machine- and human-readable way of describing digital objects used as part of API requests and responses, as well as the messages we publish and subscribe to our more asynchronous APIs. JSON Schema allows us to describe the structure of our digital resources and capabilities so that we can validate them during development and production. 

- **Objects** - Objects are a way to define digital structures, providing a machine-readable way to describe meaningful concepts exchanged online using different types of APIs and passing data in a way that makes it easy for teams to have a shared understanding. 
- **Properties** - The individual characteristics of an object, provide the details that give an object meaning and value. Properties may describe the name and email of a person object, or the name and description of a product object, providing a logical set of properties that applications can understand. 
- **Property Names** - Each property has a name, allowing each individual characteristic of an object to be described in a way that makes sense to consumers, providing a shared meaning of a specific aspect of a digital object available via an API. 
- **Property Description** - Each property can also have a description, providing much more detail about what the object property will contain. Descriptions convey the meaning and purpose behind why the property exists, and how API consumers can use it in applications. 
- **Property Type** - Allowing each property to be defined as a string, number, object, or other common or custom type, formally articulating what it can be expected to contain, helping us to be very strict or loose when it comes to making data available in objects. 
- **Property Patterns** - Patterns allow for regular expressions to be used to precisely articulate what a property should contain, providing a universal way of precisely describing the contents, ordering, and structure of the data available via each object property. 
- **Required** - Defining a list of the properties for each object is required whenever you are moving objects around synchronously or asynchronously via APIs, helping to describe the minimum amount of information needed to define an object made available. 
JSON Schema is how the digital bits we pass around the web each day get validated behind the scenes, making sure the requests we make and the response received meet the expectations of both API producers and consumers, giving us the real-time validation we need to reliably do business at scale.
Both OpenAPI and AsyncAPI use JSON Schema to model the payloads of both
our synchronous and asynchronous APIs, providing a rich way to define the digital resources and capabilities of the enterprise. JSON Schema validates that business is happening as we expand at scale across our operations. 
### Use Cases 
 

- **Validation** - JSON Schema is commonly used to validate the digital objects being passed as part of requests and responses, helping ensure objects are properly formed. 
- **Forms** - JSON Schema is often used to model forms, define the properties, and then be used to validate that the form is properly submitted, helping ensure the data is as clean and consistent as possible. 
 
 
