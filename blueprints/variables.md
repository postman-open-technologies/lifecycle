## Variables 
Secrets and other common data that is applied to APIs during integration and automation should always be abstracted away, centralized, and then securely managed via environments, allowing the common data applied during testing and operations to be standardized and applied consistently. 

### Variable 
These are the elements of variables and how they can be applied as part of API operations. 

- **Key** -  
- **Value** -  
 
### Scope 
Postman supports variables at different scopes, allowing you to tailor your processing to a variety of development, testing, and collaboration tasks. Scopes in Postman relate to the different contexts that your requests run in, and different variable scopes are suited to different tasks. 

- **Global Variables** - Enable you to access data between collections, requests, test scripts, and environments. Global variables are available throughout a workspace. Since global variables have the broadest scope available in Postman, they are well-suited for testing and prototyping. In later development phases, use more specific scopes. 
- **Collection Variables** - Are available throughout the requests in a collection and are independent of environments. Collection variables do not change based on the selected environment. Collection variables are suitable if you are using a single environment, for example for auth or URL details. 
- **Environment Variables** - Enable you to scope your work to different environments, for example local development versus testing or production. One environment can be active at a time. If you have a single environment, using collection variables can be more efficient, but environments enable you to specify role-based access levels. 
- **Data Variables** - Come from external CSV and JSON files to define data sets you can use when running collections with Newman or the Collection Runner. Data variables have current values, which do not persist beyond request or collection runs. 
- **Local Variables** - These are temporary variables that are accessed in your request scripts. Local variable values are scoped to a single request or collection run and are no longer available when the run is complete. Local variables are suitable if you need a value to override all other variable scopes but do not want the value to persist once execution has ended. 
If a variable with the same name is declared in two different scopes, the value stored in the variable with narrowest scope will be used. For example, if there is a global variable named username and a local variable named username, the local value will be used when the request runs. 
 
