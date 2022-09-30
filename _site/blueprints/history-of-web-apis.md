# History of Web APIs
While taking shape for several decades, modern web APIs began to take their current form during the e-commerce and social networking evolution of the early 21st century. Pushing what was possible when it comes to buying and selling in a digital work, but then also realizing that consumers are a very social creature, and we’d want to bring our friends, family, and followers along for the ride.

## Commerce

In the early days of the Internet, many companies used the service-oriented architecture (SOA) model to deploy their systems.
This model includes components and services that are self-contained and reusable across a deployment.

Early web APIs escaped from the controlled SOA experiment that was occurring within the enterprise and began to be applied to sales, products, affiliates, auctions, and the other expanding areas of the e-commerce shift that was occurring online.

- **Salesforce**: In the late 1990s, Salesforce developed a web-based sales automation tool, which was formatted in Extensible Markup Language (XML) and used a remote procedure call (RPC) to communicate over HTTP. This tool is considered to be the first software as a service (SaaS).
- Amazon
- eBay

## Social
The digital experience was rapidly becoming a social affair, with images, links, and other digital resources become more sharable via APIs, but also by expanding the use of APIs to define our profiles, connections, and networks where we are sharing these images and links.

- Flickr
- Facebook
- Twitter

## Web 1.0

The first implementation of the World Wide Web, between the years 1989 and 2005, is known as Web 1.0.
During this era, the web was made up of static HTML and XML sites.

- **XML-RPC**: Early web APIs, including the tool that Salesforce built, communicated by sending XML-formatted documents over HTTP using an RPC, known as the XML-RPC protocol. The XML-RPC protocol evolved into the Simple Object Access Protocol (SOAP).
- **SOAP**: Like the earlier XML-RPC protocol, SOAP sends XML data over HTTP, and it adds standards and specifications for message formats, encoding rules for API requests and responses, as well as structured data in XML. SOAP supports sending either `GET` or `POST` requests, but it does not support other HTTP methods like `PUT`, `DELETE`, `HEAD`, or `OPTIONS`. In Web 1.0, SOAP requests were primarily used for machine-to-machine interaction, but occasionally used for web-server and web-client interactions as well. SOAP was the foundation of the broader concept of web services.

## Web 2.0

The Web 2.0 era began around 2005.

- **REST**: In 2000, Roy T. Fielding introduced the Representational State Transfer (REST) framework. This architectural style rejected the RPC-style approach and proposed guidelines for defining API interfaces. REST introduced new ways for web application APIs to exchange information, making use of resource identifiers, standard media types, and standard HTTP status codes. Unlike SOAP, the REST style supports the use of all HTTP methods. The concept of open, publicly-hosted APIs is based on the REST framework, and many current web APIs are considered RESTful.
- **AJAX**: In 2005, the Asynchronous JavaScript and XML (AJAX) technique was introduced. Using the lightweight AJAX approach, developers created websites that were more complex and dynamic. AJAX allows a web client to request content from a server asynchronously. Over time, developers using AJAX started moving away from XML to JavaScript Object Notation (JSON).
- **jQuery**: jQuery, along with other JavaScript libraries, grew in popularity as developers adopted the AJAX technique. Developers using AJAX and jQuery began to use web application APIs that communicated between the server and the browser, rather than between the server and client.

## Web 3.0

Web 3.0 has been talked about since 2014, but it is still under development.
This era of the web involves a broader range of internet-connected machines, distributed architecture, and a faster and more interactive experience. The technologies that make these things possible include IoT, AI, ML, and Blockchain.

- **IoT**: The Internet of things (IoT) includes physical devices and sensors that communicate with other devices over the Internet. For example, home automation devices such as smart thermostats, remote monitoring systems, and app-controlled lights are IoT devices.
- **AI**: Artificial intelligence (AI) applications are programmed to perceive their environment and take actions based on those perceptions. AI applications are designed to mimic human intelligence and simulate the way humans learn and solve problems. For example, video streaming sites can use AI to observe what content the viewer is watching and make recommendations for similar content that they might want to watch next.
- **ML**: Machine learning (ML) applications are designed to collect and learn from a set of data. While other types of AI applications must be explicitly programmed to make certain decisions, ML applications gain the ability over time to make predictions based on the data they've analyzed, and they can answer questions that are not specifically defined in their programming. ML applications are often used to classify information based on large amounts of historical data, such as speech or handwriting recognition, credit card fraud detection, and natural language processing.
- **Blockchain**: A blockchain is a linked list of transaction records, where each record block contains a cryptographic hash of the previous block. The blocks are linked together, forming a chain. If a block is altered, the rest of the chain is altered as well. Blockchain databases are often public and hosted on a peer-to-peer network, which makes their architecture highly distributed. 
