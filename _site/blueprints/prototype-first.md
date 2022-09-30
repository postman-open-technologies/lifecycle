# Prototype-First
An approach to delivering APIs that involves building of a prototype of an API, opting to not build a contract first, but mock and document the desired functionality using a collection. Producing as much of the functionality as you can, iterating upon the design of the API amongst stakeholders, before producing a machine readable contract, as well as the tests that will be needed to verify an API behaves as expected when it is production–arriving at the same place you would through design-first, but beginning with the prototype instead of the actual contract.

- **Workspace** - Whether this is a new API, or work to an existing API, a workspace is always the place to begin work, ensuring there is a single location to find all of the work happening.
- **Collection** - We will be hand-crafting a collection to describe the surface area of the API, defining the requests, and example responses, making our API as real as possible.
- **Mocks** - The contract for an API is perpetually used to generate mock servers helping make the design of the API as realistic as possible, matching specific use cases with examples.
- **Document** - Generating human readable documentation from an APIs contract, ensuring there is accurate and up-to-date documentation for each API as it is being designed.
- **Feedback** - Providing a feedback mechanism for all stakeholders to use when it comes to providing feedback on the current design of an API, helping guide producers froward.
- **Iterate** - Aggregate feedback from consumers and other stakeholders, identify the sensible changes to the API, then iterate on the contract, updating mocks and the documentation.
- **Test** - Once the contract for an API has been established, and there will be no more iterations to this version, then contract tests can be produced to validate in production.
- **Contract** - Once we’ve effectively prototyped our API, iterate upon the design usign the prototype, then we can choose to generate a contract from our collection prototype used.

