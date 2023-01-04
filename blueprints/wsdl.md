## WSDL 
WSDL is an XML format for describing network services as a set of endpoints operating on messages that contain either document-oriented or procedure-oriented information. The operations and messages are described abstractly, then bound to a concrete network protocol and message format to define an endpoint. While few new APIs use WSDL, they are ubiquitous for web services across common enterprise systems. 

### Documents 
WSDL contracts are defined as documents, giving flexibility for the type of document and the message, as well as the port type, and binding defining access and communication. 

- **Types** - Defines the XML Schema data types used by the web service, specifying a specific, existing, and well-known schema that provides a shared understanding. 
- **Message** - Defines the data elements for each operation, allowing just the contents of the API request to be accessed, focusing on only the payload, not transport. 
- **Port Type** - Describes the operations that can be performed and the messages involved, shaping what type of communication is used for communicating. 
- **Binding** - Defines the protocol and data format for each port type, setting the stage for how API communication will occur, with the desired protocol and port. 
 
### Port type 
The port type element defines a web service, the operations that can be performed, and the messages involved, providing for a very versatile way of delivering upon WSDL contracts.
 

- **One-Way** - The operation can receive a message but will not return a response. 
- **Request-Response** - The operation can receive a request and will return a response. 
- **Solicit-Response** - The operation can send a request and will wait for a response. 
- **Notifications** - The operation can send a message but will not wait for a response. 
 
While most greenfield APIs will not be using SOAP as a pattern, it is likely we will still see web services that use SOAP and expose a WSDL contract for the next fifty years. This longevity will make it an essential part of the API-first transformation occurring across our organizations and the industries we operate in. WSDL will always describe our legacy infrastructure, but it is also an important part of our transformation, something we’ll be emulating and learning from for years to come.
 
