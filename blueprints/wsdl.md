# WSDL
WSDL is an XML format for describing network services as a set of endpoints operating on messages containing either document-oriented or procedure-oriented information. The operations and messages are described abstractly, and then bound to a concrete network protocol and message format to define an endpoint. While few new APIs choose to use WSDL, they are ubiqutious for web services across common enterprise systems.

## Documents

- **Types** - Defines the (XML Schema) data types used by the web service
- **Message** - Defines the data elements for each operation
- **Port Type** - Describes the operations that can be performed and the messages involved.
- **Binding** - Defines the protocol and data format for each port type

## Port Type
The port type element defines a web service, the operations that can be performed, and the messages that are involved.

- **One-Way** - The operation can receive a message but will not return a response
- **Request-Response** - The operation can receive a request and will return a response
- **Solicit-Response** - The operation can send a request and will wait for a response
- **Notification** - The operation can send a message but will not wait for a response
