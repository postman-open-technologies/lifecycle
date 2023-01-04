## OWASP Top 10 
When you’re injecting a required security review of an API, consider the OWASP Top 10 as the starting point, running the following checks against every API before certifying it ready for production. 

### Elements 
 

- **Broken Object Level Authorization** - APIs tend to expose endpoints that handle object identifiers, creating a wide attack surface level access control issue via specific objects. 
- **Broken User Authentication** - Authentication mechanisms are often implemented incorrectly, allowing attackers to compromise authentication tokens to gain access. 
- **Excessive Data Exposure** - Developers tend to expose all object properties without considering their individual sensitivity, relying on clients to perform the data filtering. 
- **Lack of Resources & Rate Limiting** - Too many developers fail to impose any restrictions on the size or number of resources that can be requested by the consumer in any given time period. 
- **Broken Function Level Authorization** - Access control policies may be too complex with different hierarchies, groups, roles, and an unclear separation of resources. 
- **Mass Assignment** - If you bind client-provided data to data models without proper properties filtering, it could allow attackers to traverse and explore by guessing your structure. 
- **Security Misconfiguration** - Security misconfiguration is commonly a result of insecure default configurations, or incomplete or ad-hoc configurations by teams. 
- **Injection** - Injection flaws, such as SQL, NoSQL, and command injection, occur when untrusted data is sent to an interpreter as part of a command or query with a request. 
- **Improper Asset Management** - APIs tend to expose more endpoints than traditional web applications, making proper and updated documentation extremely important. 
- **Insufficient Logging & Monitoring** - Insufficient logging and monitoring, coupled with missing or ineffective integration with incident response, opens doors for attackers. 
 
The OWASP Top 10 API vulnerabilities provide us with a baseline that should exist across 100% of the APIs in production, whether they are for internal, partner, or public consumers. There will be other security concerns as well, but if you make this list the default across your operations, you will significantly improve the reliability of your APIs.
This stage of the life cycle tends to get the most attention in technical conversations about delivering APIs–doing the work to bring each API to life. A well-defined API life cycle makes the development stage as efficient as possible, with developers doing what they do best. 
