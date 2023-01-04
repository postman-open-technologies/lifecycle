## Producer - Secure 
This stage is about securing the access and operations surrounding each API, ensuring only those who should have access are able to make requests and publish messages. Security is about establishing an organization-wide approach to how API authentication works and how encryption is applied, as well as secrets, roles, and the way APIs are fuzzed and scanned for vulnerabilities. You must provide teams with everything they need to secure each API and the operations around it, consistently securing the expanding API landscape. 

### Elements 
 

- **Authentication** - Authentication helps ensure APIs are accessed only by those who should have access, allowing API producers and consumers to easily apply rules consistently. 
- **Authorization** - Once a user is authenticated, the authorization layer will make sure they only have access to approved resources. 
- **Role Based Access Control** - Role-based access controls should be applied at the authorization layer of an API and to the API operations around it, helping govern who has access to operations. 
- **Encryption** - Ensure that all API requests are encrypted, and make reading encrypted messages as easy as possible.
 
- **Environments** - Have a solid map of the development, staging, and production environments across all APIs in operation. That will help you manage API deployment more consistently. 
- **Variables** - Provide a well-defined vocabulary of variables that abstract away the common aspects of authentication and authorization, standardizing the way teams engage with APIs. 
- **Secrets** - Add a layer on top of environmental variables specifically for managing secrets, making sure you have clear visibility and control of secrets and tokens being applied. 
- **OWASP Top 10** - The OWASP Top 10 is a standard for API producers, covering a broad consensus about the most critical security risks for web APIs and providing a consistent checklist for teams to follow. 
 
There are many layers of security for producing and consuming APIs. Organizations are increasingly making security a priority earlier on in the API life cycle instead of after an API goes live. This evolution is often described as shifting left, or investing in security earlier in the life cycle and equipping API teams with proven approaches to delivering more secure APIs.

API security doesn’t stop at the authentication and authorization of each API. It should include data in transport, the operations around each API, and security concerns for both producers and consumers. A known API life cycle, combined with well-defined security practices, gets teams up to speed with what matters most for securing APIs. 
