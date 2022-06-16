# Security Review
Injecting a required security review of an API, considering the OWASP Top 10 as the starting point, running the following checks against every API before certifying it ready for production.

## Security Fundamentals

There are many unique security considerations teams should be thinking about early on in the defining and designing of APIs, but also as teams are developing them, leaving teams with a more secure API.

- **Encryption** - Making encryption the default for all APIs, covering the transport layer, but also storage and database behind APIs, having a solid encryption plan from the start.
- **Authentication** - Leveraging common standards when it comes to authenticating API consumers for using any API, and reducing the complexity for consumers at this layer.
- **Authorization** - Considering an added authorization layer that defines what API-driven resources and capabilities each consumer has access to once they gain access to APIs.
- **Role-Based Access Control** - Applying RBAC to all of the elements of API operations, defining who can edit or just read artifacts, documentation, testing, and other elements.
- **Contracts** - Each API possess a complete contract, including full details of the authentication and authorization, providing the menu of security in place for each API.
- **Environments** - Evaluate the development, staging, sandbox, and production environments that teams have available and what they secret strategy is for their team.
- **Documentation** - Including security fundamentals as part of the documentation for each API, making sure that consumers are always fully aware of the security that is in use.
- **Tests** - Provide collection security tests, providing modular, reusable, executable, and fully documented security tests for all of the most common vulnerabilities teams face.

There is plenty more your security team will be considering when it comes to API security, but this should be the baseline for security when it comes to your operations, providing the fundamentals. 

## OWASP Top 10
Injecting a required security review of an API, considering the OWASP Top 10 as the starting point, running the following checks against every API before certifying it ready for production.

- **Broken Object Level Authorization** - APIs tend to expose endpoints that handle object identifiers, creating a wide attack surface Level Access Control issue. 
- **Broken User Authentication** - Authentication mechanisms are often implemented incorrectly, allowing attackers to compromise authentication tokens or to exploit implementation flaws to assume other user’s identities temporarily or permanently.
- **Excessive Data Exposure** - Looking forward to generic implementations, developers tend to expose all object properties without considering their individual sensitivity, relying on clients to perform the data filtering before displaying it to the user. 
- **Lack of Resources & Rate Limiting** - Quite often, APIs do not impose any restrictions on the size or number of resources that can be requested by the client/user. Not only can this impact the API server performance, leading to Denial of Service (DoS), but also leaves the door open to authentication flaws such as brute force.
- **Broken Function Level Authorization** - Complex access control policies with different hierarchies, groups, and roles, and an unclear separation between administrative and regular functions, tend to lead to authorization flaws. By exploiting these issues, attackers gain access to other users’ resources and/or administrative functions.
- **Mass Assignment** - Binding client provided data (e.g., JSON) to data models, without proper properties filtering based on an allowlist, usually leads to Mass Assignment. Either guessing objects properties, exploring other API endpoints, reading the documentation, or providing additional object properties in request payloads, allows attackers to modify object properties they are not supposed to.
- **Security Misconfiguration** - Security misconfiguration is commonly a result of unsecure default configurations, incomplete or ad-hoc configurations, open cloud storage, misconfigured HTTP headers, unnecessary HTTP methods, permissive Cross-Origin resource sharing (CORS), and verbose error messages containing sensitive information. 
- **Injection** - Injection flaws, such as SQL, NoSQL, Command Injection, etc., occur when untrusted data is sent to an interpreter as part of a command or query. The attacker’s malicious data can trick the interpreter into executing unintended commands or accessing data without proper authorization. 
- **Improper Assets Management** - APIs tend to expose more endpoints than traditional web applications, making proper and updated documentation highly important. Proper hosts and deployed API versions inventory also play an important role to mitigate issues such as deprecated API versions and exposed debug endpoints. 
- **Insufficient Logging & Monitoring** - Insufficient logging and monitoring, coupled with missing or ineffective integration with incident response, allows attackers to further attack systems, maintain persistence, pivot to more systems to tamper with, extract, or destroy data. Most breach studies demonstrate the time to detect a breach is over 200 days, typically detected by external parties rather than internal processes or monitoring. 

The OWASP Top 10 API vulnerabilities provide us with the baseline that should exist across 100% of the APIs in production, no matter whether they are for internal, partner, or public consumers.