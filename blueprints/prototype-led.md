## Prototype-Led 
This approach to delivering APIs involves building a prototype of an API, opting to not build a contract first, but mocking and documenting the desired functionality using a collection. With a prototype-led approach, you produce as much of the functionality as you can, iterating upon the design of the API with stakeholders before producing a machine-readable contract, as well as the tests you’ll need to verify that your API behaves as expected in production. A prototype-led approach will appeal to some teams as the quickest way to move from idea to development once everyone is ready. 

### Elements 
 

- **Workspaces** - Whether you’re creating a new API or enhancing an existing one, a workspace is always the place to begin, ensuring there is a single location where teams can find all ongoing work.
 
- **Collections** - We hand-craft a collection to describe the surface area of the API, defining the requests and example responses to make our API as real as possible. 
- **Mocks** - The contract for an API is perpetually used to generate mock servers, making the design of the API as realistic as possible by matching specific use cases with examples.
 
- **Document** - Generating human-readable documentation from an APIs contract is important. It ensures you have accurate and up-to-date information about each API as it is being designed. 
- **Feedback** - Provide a feedback mechanism for all stakeholders for the current design of an API, helping guide producers forward. 
- **Iterate** - Aggregate feedback from consumers and other stakeholders.Identify sensible changes to the API, then iterate on the contract, updating mocks and documentation. 
- **Tests** - Once the contract for an API has been established, and there will be no more iterations to this version, you can produce contract tests to validate in production, ensuring that the original intent of the API is accomplished. 
- **Contract** - Once you’ve effectively prototyped your API, iterate upon the design using the prototype. Then you can choose to generate a contract from the collection prototype, getting to the same place where you would be with a design-led approach. 
 
API contracts are an essential part of API operations, but sometimes it makes sense
to produce a contract only after you have iterated upon an API with a prototype. Not every team will be proficient in crafting an API contract to use for mocking. Sometimes it makes more sense to produce a collection, and iterate upon the API first. Then when they’re ready, teams can use the collection to generate a machine-readable contract that can be used throughout the rest of the API lifecycle. 
