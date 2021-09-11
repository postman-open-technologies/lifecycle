---
name: Manually Define Collection for Existing API
description: A blueprint for beginning the API lifecycle by manually defining a collection.
conclusion: This blueprint intends to provide a high level walk through of one possible way of defining a standardized API lifecycle beginning with the manual creation of a Postman collection that describes how an existing API should work. Each element within this blueprint works to provide a simple overview of what is involved across the entire life of an API, with more detail present on the detail page for each element (if you are viewing this on the API lifecycle project site). If you are reading this via a PDF or printed version you can visit the landing page for this blueprint to access more information and view specific actions you might possibly consider taking as part of applying each element of this proposed lifecycle within your own operations. This blueprint is a living document and will continue to evolve and be added to over time based upon feedback from readers. If you have any questions, feedback, or feel like there is more information you need, feel free to jump on the Github discussion for this blueprint, or any of the individual elements present--the value this blueprint provides is actively defined by the feedback community members like you.
image: collection.png
tags:
  - OpenAPI
  - Prototype-First
stage: Existing
type: sync
order: 4
maturity: stable
areas:

  - label: Define
    image: images/lifecycle-arrow-define.png
    description: The Postman collection has become a proven solution for defining and troubleshooting existing APIs over the last five years. Providing a machine readable representation of the details of each API request and response that can then be used as an API client, to power documentation and testing. Postman collections provide an ideal foundation for defining what an API can do, then using that collection to power other stops along the API lifecycle, be shared internally via other workspaces, and externally via workspaces, URL, or an embeddable Run in Postman button. Providing an industrial strength approach to laying a foundation for a repeatable and well known API lifecycle for an existing API that is already in production.
    elements:
      - name: Collection
        label: Collection    
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
      - name: Public Network
        label: Public Network                    
        context: 1  
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/13      
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/manually-define-collection-for-an-existing-api.md    
...
When it comes to defining the API lifecycle for an existing API, sometimes you just need to roll up your sleeves and begin crafting a Postman collection from existing documentation that exists. Adding each individual request, parameters, and other details, while abstracting away authentication details using an environment and variables. Manually defining a collection for an existing API helps establish a cornerstone for an API that is already in production, but could use more investment in documentation, testing, and other areas of a modern API lifecycle. Preparing an API to possibly be iterated upon for a future version, or simply just make sure it is operating and being managed in a well defined away as part of overall API operations. This API blueprint enters the API lifecycle using the proven approach to defining a Postman collection, but then guides you through some of the most comment elements of an API lifecycle that are needed to get an API up to acceptable levels, in alignment with the rest of API operations. 