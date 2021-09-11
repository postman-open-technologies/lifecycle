---
name: Import WSDL for an Existing SOAP Web Service
description: A blueprint for beginning the API lifecycle by importing a WSDL for an existing SOAP web service.
conclusion: This blueprint intends to provide a high level walk through of one possible way of defining a standardized API lifecycle which is centered around an existing SOAP web service. Each element within this blueprint works to provide a simple overview of what is involved across the entire life of an API, with more detail present on the detail page for each element (if you are viewing this on the API lifecycle project site). If you are reading this via a PDF or printed version you can visit the landing page for this blueprint to access more information and view specific actions you might possibly consider taking as part of applying each element of this proposed lifecycle within your own operations. This blueprint is a living document and will continue to evolve and be added to over time based upon feedback from readers. If you have any questions, feedback, or feel like there is more information you need, feel free to jump on the Github discussion for this blueprint, or any of the individual elements present--the value this blueprint provides is actively defined by the feedback community members like you.
image: wsdl.png
tags:
  - WSDL
  - SOAP
  - Web Service
stage: Existing
type: sync
order: 7
maturity: stable
areas:

  - label: Define
    image: images/lifecycle-arrow-define.png
    description: For traditional web services the web services description language (WSDL) is the key to defining and understanding what each API is capable of. Similar to an OpenAPI, the WSDL describes the surface area of a SOAP web service, defining the available methods and payload structure. Upon import or creation of a new API using WSDL, a modern API lifecycle can be set into motion through the generation of collections for documenting and testing of web services. Helping modernize existing web services by applying some of the common elements of modern API lifecycle to existing WSDL services.
    elements:
      - name: Team Workspace
        label: Team Workspace
        context: 1
      - name: Team Members
        label: Team Members   
        context: 1      
      - name: WSDL
        label: WSDL    
  - label: Document
    image: images/lifecycle-arrow-document.png
    description: Having complete, accurate, and easy to follow documentation is essential for all APIs, and is something that  alleviates the number one pain point for API consumers when it comes to onboarding with any API, expanding the number of API paths an application puts to work. Modern approaches to producing API documentation have moved beyond a single static version of documentation simply published to a portal, as well as there being potentially multiple forms of documentation for any single API. Helping API producers onboard consumers easier, reduce the cognitive load when understanding what an API does, and properly define specific business use cases of an API being put to work in an application or as part of an integration.
    elements:
      - name: Reference Documentation
        label: Reference Documentation 
        context: 1     
  - label: Test
    image: images/lifecycle-arrow-test.png
    description: A test-driven API lifecycle ensures that each API delivers the intended outcomes it was developed for in the first place, providing manual as well as automated ways to ensure an API hasn't changed unexpectedly and is as performant as required, helping establish a high quality of service consistently across all APIs. API testing should not be an afterthought and should be a default aspect of the API lifecycle for any API being put into production. API testing takes a solid investment in establishing proper testing practices across teams, but once you do the work to establish a baseline of testing, properly train teams on the process and tooling involved, the investment will pay off down the road.
    elements:
      - name: Contract Testing
        label: Contract Testing  
        context: 1 
      - name: Performance Testing
        label: Performance Testing   
        context: 1
  - label: Secure
    image: images/lifecycle-arrow-test.png
    description: Security must be its own area of the API lifecycle, but it is something that should span testing, authentication, and potentially other areas of the API lifecycle. Over the last five years the world of API security has expanded, while also moving further left in the API lifecycle as part of a devops shift in how APIs are delivered. There are a number of elements present when it comes to security, but depending on the overall maturity of API operations the available resources and prioritization available to adequately realize these elements vary.
    elements:
      - name: Authentication
        label: Authentication
        context: 1         
      - name: Security Testing
        label: Security Testing   
        context: 1        
  - label: Monitor
    image: images/lifecycle-arrow-monitor.png
    description: Monitors can be used to execute any Postman collection applied to any environment. Due to the versatility of what a Postman collection can define, collections turn monitors into a powerful API automation and orchestration tool. Beginning with the ability to schedule contract, performance, and other types of tests, but then also allowing for automating specific workflows across many different APIs. Since collections can be used to define anything that can be defined via an API, monitors can be used to schedule the running of each capability from multiple cloud regions, applying many different environmental variables. Making monitors an essential, versatile, and executable part of defining how the API lifecycle works.
    elements:
      - name: Contract Testing Monitor
        label: Contract Testing Monitor  
        context: 1 
      - name: Performance Testing Monitor
        label: Performance Testing Monitor   
        context: 1
      - name: Security Testing Monitor
        label: Security Testing Monitor                          
        context: 1
  - label: Discover
    image: images/lifecycle-arrow-discover.png
    description: The ability to discover APIs at all stages of the API lifecycle is essential for reducing redundancy across operations, helping teams find existing APIs before they develop new ones, properly matching API consumers with the right APIs, while supporting documentation, relevant workflows, and the feedback loops that exist as part of the operation of APIs internally within the enterprise, or externally with 3rd party developers. API discovery does not live at the beginning or the end of the API lifecycle, but should be considered across all areas of the API lifecycle, ensuring that APIs, as well as the operations around them are as discoverable as possible, but well informed when it comes to privacy, security, and terms of service.
    elements:
      - name: Search
        label: Search     
        context: 1
      - name: Private Network
        label: Private Network   
        context: 1  
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/32      
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/import-wsdl-for-an-existing-soap-web-service.md       
...
Modern APIs and microservices is primarily delivered as RESTful, RPC, and GraphQL APIs using HTTP, but as the result of the widespread adoption of services oriented architecture (SOA) in the early 2000s, there are still many web services in production. SOAP is rarely used to deliver new APIs, but because of the ubiquitous nature of the approach within long living enterprise infrastructure, SOAP web services continue to play a significant role as part of API operations. This lifecycle blueprint acknowledges that existing SOAP web services have a place in the modern enterprise, and can benefit from some of the other healthy elements present across the API lifecycle for other types of APIs and microservices, ensuring they are well documented, have testing in place, as well as being monitored and discoverable just like the rest of API operations. This blueprint provides one possible path to consider as teams look to modernize their API infrastructure.