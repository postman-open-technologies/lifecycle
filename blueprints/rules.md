## Rules 
Machine-readable rules in YAML or JSON can be used to lint or validate any other YAML or JSON artifact. Rules allow for common or specialized procedures to be established to help check for consistency in the design, development, deployment, and management of APIs. Rules help codify standards and health practices for delivering APIs into the API life cycle across domains and teams. 

### Elements 
 

- **Name** - “Name” here means the name of the linting rule, describing what it applies to and how it makes the design of an API or the operation around it more consistent. 
- **Description** - A verbose description states what a rule does, providing as much detail as possible about how the rule standardizes one small part of operations, helping to stabilize teams. 
- **Given** - A given is the property being targeted for linting, identifying a specific aspect of a contract that needs attention and focusing the attention of linters on this particular part of each API. 
- **Then** - “Then” is the criteria for evaluating the contract being limited. It provides the logic for the rule being applied. 
- **Formats** - Rules are designed to be applied to different types of contract formats, including Swagger, OpenAPI, AsyncAPI, and others. 
- **Documentation URL** - An external URL can be used for documentation and educational resources associated with a specific rule, turning every rule into a potentially teachable moment. 
- **Rulesets** - Organizing multiple rules into sets enables you to apply them all at once, organized by domain or other bounded context. Rulesets make rules easier to apply. 
- **JSONPath** - JSONPath is the specification used as part of the “given” and “then” properties to target specific sections of a JSON contract, providing any level of scope when linting contracts. 
 
Rules help us distill all the things we need for usability, consistency, and stability into modular procedures that can be applied as sets or individually during design–and more importantly, throughout the API life cycle. In some cases we can gate rules at the pipeline level, ensuring we are always producing the best APIs we can, no matter what team produces them.
The leading approach for defining and executing rules is Spectral, an open source solution developed by an API service provider named Stoplight. It is common today to define Spectral rules to apply as part of the API design process, linting or validating the OpenAPI contract for an API. However, Spectral can be applied to any JSON object, making it easy to apply rules to any part of the API life cycle. 
