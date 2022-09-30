# Rules
Machine readable rules in YAML or JSON that can be used to lint any other YAML or JSON artifact, allowing for common or specialized rules to be established to help check for consistency in the design, development, deployment, and management of APIs, helping codify standards and health practices for delivering APIs into the API lifecycle across domains and teams.

- **Name** - The name of the linting rule, describing what it applies to and how it benefits in making the design of an API more consistent, or also possibly the operation around it.
- **NDescription** - A verbose description of what a rule does, providing as much detail about how the rule helps standardize one small part of operations, helping stabilize teams.
- **NGiven** - The property being targeted for linting, identifying a specific aspect of a contract needing attention, focus the attention of linters on this particular part of each API.
- **NThen** - The criteria for evaluating the contract being linted, providing the logic for the rule being applied, being precise or more loose in how each contract is being scrutinized.
- **NFormats** - Identifying the different types of contract formats that rules are design to be applied to, organizing Swagger, OpenAPI, AsyncAPI, and other formats together.
- **NDocumentation URL** - An external URL for documentation and educational resources associated with a specific rule, turning every rule into a potentially teachable moment.
- **NRulesets** - Organizing multiple rules into sets so that they can all be applied at once, and organized by domain, or other bounded context, keeping rules easier to apply.
- **NJSONPath** - The specification used as part of the “given” and “then” properties to target specific sections of a JSON contract, providing any level of scope when linting contracts.

Rules help us distill down all the things we need for usability, consistency, and stability down into modular rules that can be applied as sets or individually during design time, or more importantly throughout the API lifecycle, and in some cases gated at the pipeline level, ensuring we are always producing the best API we possibly can, no matter what team produce it.
