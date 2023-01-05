## Gateway Patterns 
this is an overview of the different ways you can deploy an API 

### Types 
The different ways in which a gateway is deployed. 

- **Centralized edge gateway** - An API gateway is typically deployed at the edge of a system, but the definition of “system” in this case can be quite flexible. For startups and many small-medium businesses, an API gateway will often be deployed at the edge of the data center or the cloud. In these situations, there may only be a single API gateway (deployed and running via multiple instances for high availability) that acts as the front door for the entire backend estate, and the API gateway will provide all of the edge functionality. 
- **Two-tier gateway** - For large organizations and enterprises, an API gateway will typically be deployed in multiple locations, often as part of the initial edge stack at the perimeter of a data center, and additional gateways may be deployed as part of each product, line of business, or organizational department. In this context, these gateways would more typically be separate implementations and may offer different functionality depending on geographical location (required governance) or infrastructure capabilities (running on low-powered edge compute resources). 
- **Microgateway** - Microgateways are designed entirely for internal communication between microservices. Each individual microgateway may have a different set of policies, and security rules, and require aggregation of monitoring and metrics from multiple services. 
- **Sidecar API gateway** - Sidecar implements an API gateway as a container attached to a service in an independent runtime, such as Kubernetes. Sidecar is a pattern that corresponds to a sidecar attached to a motorcycle, similarly, it is attached to a parent application (a software component called service mesh) and provides supporting features for the application. The sidecar also shares the same lifecycle as the parent application, is created and retired alongside the parent, and introduces additional features such as monitoring, logging, configuration, and networking services. 
 
null 
