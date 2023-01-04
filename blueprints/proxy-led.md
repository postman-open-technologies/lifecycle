## Proxy-Led 
Proxy-led is the process of reverse engineering of an existing API by proxying the requests and responses sent, or the published and subscribed messages delivered. That generates a collection from actual behavior within a desktop, web, mobile, or device application. The intent of proxy-led is to produce a collection that describes the surface area of an API, then mock and document this behavior before you produce a machine-readable contract and tests to validate behavior moving forward. 

### Elements 
 

- **Workspaces** - Whether you’re creating a new AP or enhancing an existing one, a workspace is always the place to begin, ensuring there is a single location where teams can find all of the ongoing work. 
- **Proxy** - Run the traffic for a desktop, mobile, or device application through a proxy to reverse engineer the traffic, mapping out the surface area of the APIs behind them. 
- **Application Performance Management (APM)** - Pull the traffic logged in of APM solutions as evidence of API paths, parameters, and headers, as well as request and response bodies, or the messages being published as part of event-driven APIs. 
- **Collections** - We hand-craft a collection to describe the surface area of the API, defining the requests and example responses to make our API as real as possible. 
- **Mocks** - The contract for an API is perpetually used to generate mock servers, making the design of the API as realistic as possible by matching specific use cases with examples. 
- **Document** - Generating human-readable documentation from an APIs contract ensures you have accurate and up-to-date documentation for each API as it is being designed. 
- **Tests** - Once the contract for an API has been established, and there will be no more iterations to this version, you can produce contract tests to validate in production, helping ensure the quality of APIs. 
- **Contract** - Once you’ve effectively prototyped your API, iterate upon the design using the prototype. Then you can choose to generate a contract from the collection prototype, taking the evidence gathered to produce the API contract needed over time. 
- **Gateways** - A gateway can be used to generate API evidence that can be used to reverse engineer a contract from an API already in production. 
 
A proxy-led approach allows you to define the API landscape and contracts that already exist and automate the way you determine the “diff” between your contracts and what exists in production. A proxy-led approach helps your API catalogs, portals, and network keep pace with what is happening on the ground across operations, perpetually synchronizing hundreds of thousands of API contracts with the reality in production. 
