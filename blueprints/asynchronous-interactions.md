## Asynchronous interactions 
When you are looking for a more real-time streaming experience for applications, you should consider asynchronous interactions to deliver the experiences consumers expect. 

### Publish 
Asynchronous APIs enable publishing messages to a particular channel via an asynchronous connection. That provides a robust way to publish large volumes of data via messages to a channel. 

- **Protocols** - We select HTTP, HTTP/2, TCP, MQTT, or some other common protocol that is used for an application to asynchronously publish data to internal systems for wider usage. 
- **Channel** - We publish messages to a specific topic (sometimes called a channel) to provide a context for each message published as part of the application using each API. 
- **Message** - The JSON or XML message that is published submits information to a system asynchronously, making it available for consumption by other systems via asynchronous API. 
- **Schema** - The schema is the structure of the message, standardizing how data is being published to the asynchronous API and ensuring that there is a standardized schema available to validate.
 
Depending on the protocol, an application may just publish and forget after it sends its message, but in some implementations, you may also simultaneously subscribe to the channel. 
### Subscribe 
Using asynchronous APIs, applications can subscribe to a variety of channels, receiving messages as they become available within a system and ensuring data is where it is needed as actions occur. 

- **Protocols** - We select HTTP, HTTP/2, TCP, MQTT, or some other common protocol that is used for an application to asynchronously publish data to internal systems for wider usage. 
- **Channel** - We publish messages to a specific topic (sometimes called a channel) to provide a context for each message published as part of the application using each API. 
- **Message** - The JSON or XML message that is published submits information to a system asynchronously, making it available for consumption by other systems via asynchronous API. 
- **Schema** - The schema is the structure of the message, standardizing how data is being published to the asynchronous API and ensuring that there is a standardized schema available to validate.
 
Depending on the protocol, an application may just publish and forget after it sends its message, but in some implementations, you may also simultaneously subscribe to the channel. 
 
