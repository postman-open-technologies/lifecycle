---
name: Creating a New GraphQL API
description: This is a blueprint for pushing this API lifecycle blueprint to also work for new GraphQL APIs, identifying the steps needed to define and stand up a new GraphQL API, but then apply a consistent well defined lifecycle to how the API is moved forward and supported in production.
image: graphql.png
tags:
  - GrappQL
  - SOAP
  - Web Service
stage: New
type: sync
order: 7
maturity: draft
version: 2021-09-11
areas:

  - label: Define
    image: images/lifecycle-arrow-define.png
    description: GraphQL provides a rich set of solutions for defining the base of an API that will expose the entire surface area of one or many data sources, providing API producers with the ability to define data sources and the resolvers that route API requests to each data source, and the schema that will define how API consumers can craft queries for getting at exactly the data they need. Each of these elements help define the base for a GraphQL API, bypassing the work that is required to design a more RESTful approach to delivering APIs, putting more control into the hands of API consumers. Providing a solid approach to defining access to essential and complex backend data using an increasingly common API pattern.
    elements:
      - name: Schema
        label: Schema   
      - name: Data Sources
        label: Data Sources   
      - name: Resolvers
        label: Resolvers                           
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
      - name: Public Network
        label: Public Network                    
        context: 1  
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/28      
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/creating-a-new-graphql-api.md     
roles:
  - Advocate
  - Architect
  - Backend
  - DevOps
  - Engineering
  - Frontend
  - Mobile
  - Product
  - Support
  - Writers  
...
GraphQL has emerged as an optimal way to expose databases as a robust API which can support the needs of modern web and mobile applications. Providing an approach to delivering a single API path that provides access to an entire data graph, allowing consumers to define their own queries, and receive exactly the response they need for whatever need they have in their particular application. This is a blueprint to walk through creating a new GraphQL API, while also establishing a well-defined lifecycle around the API, ensuring that it is well documented, tested, and provides a level of service that meets the business objectives of an organization.