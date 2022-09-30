# Proxy-First
The process of reverse engineering of an existing API by proxying the requests and responses sent, or the published and subscribed messages delivered, generating a collection from actual behavior that occurs within a desktop, web, mobile, or device application. Producing a collection that describes the surface area of an API, then mocking and documenting this behavior, before you produce a machine readable contract for the API, and provide tests that validate behavior moving forward.

- **Workspace** - Whether this is a new API, or work to an existing API, a workspace is always the place to begin work, ensuring there is a single location to find all of the work happening.
- **Proxy** - Running the traffic for a desktop, mobile, or device application through a proxy to reverse engineer the traffic, mapping out the surface area of the APIs behind them.
- **Collection** - We will be hand-crafting a collection to describe the surface area of the API, defining the requests, and example responses, making our API as real as possible.
- **Mocks** - The contract for an API is perpetually used to generate mock servers helping make the design of the API as realistic as possible, matching specific use cases with examples.
- **Document** - Generating human readable documentation from an APIs contract, ensuring there is accurate and up-to-date documentation for each API as it is being designed.
- **Test** - Once the contract for an API has been established, and there will be no more iterations to this version, then contract tests can be produced to validate in production.
- **Contract** - Once we’ve effectively prototyped our API, iterate upon the design usign the prototype, then we can choose to generate a contract from our collection prototype used.

