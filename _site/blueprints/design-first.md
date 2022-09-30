# Design First
The practice of properly defining and designing your API before you begin writing any code, using an API specification to develop an API contract, mocking and documenting the contract, then iterating upon the design of the resources and capability with stakeholders. Once you are ready, and have reached an agreed upon state of what an API should do, you can then develop tests that help verify what was agreed upon during the design-first process is actually what ends up being in production.

- **Workspace** - Work on a new API always begins in a dedicated workspace, making sure that there is a single place to find artifacts, team, and the work that exists behind each API.
- **Contract** - Every API has a machine readable contract that describes the surface area of the API, providing an understanding between API producer and consume to guide operation.
- **Mocks** - The contract for an API is perpetually used to generate mock servers helping make the design of the API as realistic as possible, matching specific use cases with examples.
- **Document** - Generating human readable documentation from an APIs contract, ensuring there is accurate and up-to-date documentation for each API as it is being designed.
- **Feedback** - Providing a feedback mechanism for all stakeholders to use when it comes to providing feedback on the current design of an API, helping guide producers froward.
- **Iterate** - Aggregate feedback from consumers and other stakeholders, identify the sensible changes to the API, then iterate on the contract, updating mocks and the documentation.
- **Test** - Once the contract for an API has been established, and there will be no more iterations to this version, then contract tests can be produced to validate in production.
- **Develop** - Hand off the API contract,  providing teams with what they need to bring an API to life in development, moving to staging and running tests before it is put into production.

