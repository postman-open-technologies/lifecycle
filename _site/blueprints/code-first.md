# Code-First
The development of a new API, or adding functionality to an existing API by writing code to shape how an API will work. Producing the desired behavior by writing code in a local or shared development environment, but then once the agreed upon shape and behavior of the API is achieved, you produce a machine readable contract, and provide a set of tests that will automate the validation of assertions made by all stakeholders throughout the development process.

- **Workspaces** - Even when an API is already existing or being developed in a code-first manner, a dedicated workspace should be setup to provide a single place to find all work.
- **Annotations** - Using programming language annotations to add the necessary metadata to the code behind an API that can be used to generate a machine readable contract for APIs.
- **CI/CD Pipeline ** - Using your CI/CD pipeline to turn annotations into machine readable contracts, translating your code into a contract to power documentation, and much more.
- **Contract** - Producing a a machine readable contract for your API, leveraging code and your existing software development lifecycle to produce the contract needd to govern each API.
- **Document** - Generating human readable documentation from an APIs contract, ensuring there is accurate and up-to-date documentation for each API as it is being designed.
- **Feedback** - Gathering feedback on the design of an API, tapping into existing channels to understand what consumers and other stakeholders are needing from the API being built.
- **Iterate** - Update the code base based upon feedback adding capabilities to the API, building and updating the machine readable contract, which then updates of elements downstream.
- **Test** - Produce contract tests for APIs, adding tests to your CI/CD pipeline to ensure each API continues to relect the agreed upon contract, with no surprises pushed to production.

