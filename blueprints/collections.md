## Collections 
This is a blueprint for how to manually create a collection for an existing API, transfer details of each request from documentation to a collection, apply authentication, then continue to explore and troubleshoot until you have a complete and documented collection for an API. 

### Folders 
The folder layers of a collection, allow individual requests to be organized and grouped logically into a single bounded context that will be meaningful to put an API to work. 

- **Manufacturing** - APIs are reshaping the manufacturing supply chain, linking the physical world with the digital world and moving the factory floor into the clouds. Processes are becoming more elastic, helping manufacturers keep up s online and offline, no matter where business is happening. 
- **Transportation** - Our cars, roads, and transit systems are being transformed through APIs, changing our experience as we commute to work and take trips with the family. Our lives have become more connected, no matter where we are. 
- **Energy** - APIs are modernizing our energy grid, digitizing monitoring and other processes to deliver the energy we need to live to our homes and businesses. 
- **Retail** - Commerce has moved online in the last 20 years, and the internet has crept into the physical, point-of-sale retail experience. Now the physical experience is becoming embedded with digital signage, sensors, cameras, and other connected devices to help shoppers find what they want and allow retailers to track their habits and purchases. 
- **Cities** - Our cities are being connected to the internet, bringing streets, parks, and public spaces online. Services can be improved by connecting the physical world to the cyber world, thanks to the APIs that stitch everything together. 
- **Healthcare** - Healthcare interoperability is a priority for hospitals, and public health agencies depend on APIs to bring the patient experience into the modern age, making sure healthcare records are available wherever they are needed. 
- **Agriculture** - As we work to feed growing populations, the agriculture industry is undergoing a wave of digitization. Whether they are used by drones, sensors, tractors, or the food distribution network, APIs are being applied in new and compelling ways to change how we grow and supply food.
 
Folders help keep collections structured and easily navigated, but then when also rendered as documentation it provides for a logical wrapper to each section of the documentation, testing, and other ways a colleciton gets applied. 
### Requests 
Postman collections are a machine-readable specification for saving API requests in a portable, executable, and documented way, allowing one or many API requests to be organized by folder, then shared or published for use by others. Collections provide an executable unit of value as defined by each API’s source of truth. They are made available in a format that can be used to document, mock, test, secure, and automate many different APIs. 

- **Folders** - Logical separators within a collection for organizing and sequencing API requests for browsing by humans, but also automating with a runner or as part of a CI/CD pipeline, helping organize reference API collections, choreograph automation, and orchestrations across many different APIs as part of a single collection. 
- **Authentication** - Defining the access and authentication for each individual API request, utilizing many of the leading standards for how you secure individual requests. 
- **Documentation** - Provides inline documentation for each layer of a collection, allowing information to be provided for however a collection is being applied across the API lifecycle. 
- **Parameters** - Provide a defined set of parameters that can be used to change the state of API responses. Provide key/value pairs for common things like pagination or search, but be specific, depending on the objects returned with API responses. 
- **Headers** - Key / Value pairs of data that can be passed back and forth as part of API requests, confirming to the HTTP standard, and relying on the IANA registry of headers to define and shape the routing and prioritization of requests being made to APIs when using HTTP as the transport protocol between client and server. 
- **Body** - Enabling the ability to add JSON, XML, Text, and other types of data payloads as a body of the request, securely sending data (when encrypted) as part of a request. 
- **Pre-Request Script** - A script that executes when a request is initiated, allowing business logic to be injected into the request process, setting the stage for each individual request being made. 
OpenAPI and AsyncAPI provide a source of truth for each API. A collection provides
a derivative of that truth for a specific stop along the API lifecycle. This relationship provides a versatile way of generating documentation, mock servers, tests, and other essential building blocks.
Collections can be combined with CSV or JSON sets of data to represent specific business use cases and outcomes. Pairing collections with data helps to ensure that each individual API contract accurately reflects each and every possible business outcome associated with the contract. It allows for new levels of reliable automation across enterprise API operations.
Using collections to automate the API lifecycle is the only way we will be able to properly scale our operations from the hundreds or thousands of APIs we depend on today to what we will need tomorrow. 
 
