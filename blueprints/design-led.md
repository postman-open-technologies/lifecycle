## Design-Led 
Using a design-led approach means you define and design your API before you begin writing any code. You use an API specification to develop an API contract, mock and document the contract, then iterate with stakeholders upon the design of the resources and capability. Once you have reached agreement about what the API should do, you can develop tests to verify that the specifications you desired are in fact in production. 

### Elements 
 

- **Workspaces** - Work on a new API always begins in a dedicated workspace. Make sure there is a single place where teams can find artifacts and the work that exists behind each API. 
- **Contract** - Every API has a machine-readable contract describing the surface area of the API, providing an understanding between API producer and consumer to guide operation. 
- **Mocks** - The contract for an API is perpetually used to generate mock servers, helping make the API design as realistic as possible by matching specific use cases with examples. 
- **Document** - Documenting means generating human-readable documentation from an APIs contract, ensuring that it is accurate and uptodate for each API as it is being designed. 
- **Feedback** - Provide a feedback mechanism for all stakeholders to use with the current design of an API, helping guide teams to add new features, capabilities, and experiences. 
- **Iterate** - Aggregate feedback from consumers and other stakeholders.Identify sensible changes to the API, then iterate on the contract, updating mocks and documentation. 
- **Tests** - Once the contract for an API has been established, and there will be no more iterations to this version, you can produce contract tests to validate that an API delivers upon the original intent when in production. 
- **Develop** - Hand off the API contract, providing teams what they need to bring an API to life in development. Move to staging and tests before it goes into production. 
 
A design-led approach helps produce artifacts and gets all stakeholders and teams on the same page for what is needed to produce an API. It saves time by allowing teams to iterate upon an API without having to produce code. While design-led can get a bad reputation for creating more work than code-led, in reality it saves a significant amount of time throughout the life cycle.
 
