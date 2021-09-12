---
name: New API Using the OpenAPI Specification
description: This provides a blueprint for beginning the API lifecycle by designing a new API using an OpenAPI, showing one possible lifecycle from end to end. Approaching the API lifecycle in a design-first way, while ensuring all the other essential areas of the API lifecycle are present.
conclusion: This blueprint intends to provide a high level walk through of one possible way of defining a standardized API lifecycle which is centered around an API design-first approach to delivering an API with OpenAPI at the center. This view of the API lifecycle will not work for all teams and for all APIs, but it does provide one possible overview that may work for many situations. Each element within this blueprint works to provide a simple overview of what is involved across the entire life of an API, with more detail present on the detail page for each element (if you are viewing this on the API lifecycle project site). If you are reading this via a PDF or printed version you can visit the landing page for this blueprint to access more information and view specific actions you might possibly consider taking as part of applying each element of this proposed lifecycle within your own operations. This blueprint is a living document and will continue to evolve and be added to over time based upon feedback from readers. If you have any questions, feedback, or feel like there is more information you need, feel free to jump on the Github discussion for this blueprint, or any of the individual elements present--the value this blueprint provides is actively defined by the feedback community members like you.
image: openapi.png
tags:
  - OpenAPI
  - Design-First
stage: New
type: sync
order: 1
maturity: stable
version: 2021-09-11
areas:  

  - label: Define
    description: The most important first step of any API lifecycle is to make sure the operations around an API are properly defined, laying the foundation for being able to effectively design and bring an API to life, while also establishing a known place, or places to go to get all the information you need regarding each individual API, or groups of APIs. A little planning and organization at this early step of the API journey can go a long way towards ensuring the overall health and velocity of an API, and the applications and integrations that will depend on each internal, partner, or public API being delivered.
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Team Workspace
        label: Team Workspace
        context: 1
      - name: Team Members
        label: Team Members   
        context: 1    
      - name: Github Repository
        label: Github Repository
        context: 1
  - label: Design
    image: images/lifecycle-arrow-design.png
    description: Having a formal process and approach to designing an API helps establish consistency and the precision of each API that ends up in production, ensuring that APIs are developed using common patterns across an industry, and within an organization, establishing known practices for shaping the surface area and behaviors of APIs that applications are depending upon. API design is something that just doesn’t impact the way an API is used, it is something that impacts almost every stop along the API lifecycle, and will reduce friction and increase velocity throughout the evolution of each API, and the applications and integrations that depend upon them.
    elements:
      - name: OpenAPI
        label: OpenAPI      
        context: 1
  - label: Mock
    image: images/lifecycle-arrow-mock.png
    description: Mocking how an API works and behaves provides an effective way for teams to collaborate, communicate, and iterate as part of the design of an API, but it also is something that can be used as part of testing, or just providing a sandbox environment for API consumers to learn before they actually begin working with any API in production. Effectively mocking an API takes a little time to set up and configure properly, but once available it will help reduce friction across the entire API lifecycle, helping teams more effectively communicate around an API throughout its journey.
    elements:
      - name: Mock Server
        label: Mock Server
        context: 1
      - name: Examples
        label: Examples 
        context: 1
  - label: Document
    image: images/lifecycle-arrow-document.png
    description: Having complete, accurate, and easy to follow documentation is essential for all APIs, and is something that  alleviates the number one pain point for API consumers when it comes to onboarding with any API, expanding the number of API paths an application puts to work. Modern approaches to producing API documentation have moved beyond a single static version of documentation simply published to a portal, as well as there being potentially multiple forms of documentation for any single API. Helping API producers onboard consumers easier, reduce the cognitive load when understanding what an API does, and properly define specific business use cases of an API being put to work in an application or as part of an integration.
    elements:
      - name: Reference Documentation
        label: Reference Documentation 
        context: 1  
  - label: Deploy
    image: images/lifecycle-arrow-deploy.png
    description: Establishing a well defined process to deploy an API helps teams bring new APIs to life, as well as assists them in more efficiently delivering each future iteration of an API in a consistent and repeatable way. Making sure APIs are deployed using known development, staging, production, and other agreed upon stages that actively apply other elements like documentation, testing, while natively contributing to observability. API deployment practices will likely have been well established as part of an organization’s traditional software development lifecycle, but is something that should be open to defining, standardizing, and making more repeatable and observable as part of the API lifecycle. The API deployment portion of the API lifecycle will be the most difficult for teams to properly define, articulate, and standardize across teams, but it will continue to be one of the most critical areas of the API lifecycle to do this for, otherwise it will be guaranteed to be a repeated source of friction across API operations.
    elements:
      - name: CI/CD Pipeline
        label: CI/CD Pipeline
        context: 1
      - name: Gateway
        label: Gateway     
        context: 1   
  - label: Manage
    image: images/lifecycle-arrow-manage.png
    description: APIs should always be managed using a set of common, well-defined set of policies that define and govern how APIs are accessed via all stages of the API lifecycle, ensuring that every API has appropriate authentication, rate limits, logging, and other essential requirements of managing APIs at scale, helping strike a balance between making APIs accessible and the privacy and security concerns that exist. As API gateways and management solutions have been commoditized, many of the essential elements like documentation and testing have expanded into their own areas of the API lifecycle, leaving us with a core set of elements that can be applied by teams to help manage how APIs are put to work in applications and as part of system to system integrations.
    elements:
      - name: Onboarding
        label: Onboarding
        context: 1
      - name: Usage Plan
        label: Usage Plan    
        context: 1
      - name: Key
        label: Key       
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
  - label: End of Life
    image: images/lifecycle-arrow-retire.png
    description: Having a plan for the eventual retirement and ultimate deprecation of an API, or for specific paths or versions of an API should be a part of every API lifecycle, and even when there is no plan for deprecation there should be a process in place for setting consumer expectations for how long an API will be supported, as well as formal process to follow once retirement comes into view on the horizon. Planning for the end of life of each API will be commonplace, but only becomes a problem when there is no plan, or no communication with consumers.
    elements:
      - name: Retire
        label: Retire  
        context: 1
      - name: Deprecate
        label: Deprecate       
        context: 1
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/9
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/new-api-using-the-openapi-specification.md
...
This API lifecycle blueprint introduces the API lifecycle in what is widely considered to be an API design-first way, ensuring that each API is adequately defined by and leveraging the OpenAPI specification to design, mock, document, and iterate upon the design of each API before actually writing any code, or publishing an API to a gateway. This approach is widely considered to be desirable because it allows for API producers and even consumer stakeholders to be more closely involved in what an API will do as early on in the process as possible. This blueprint looks to provide you with a walkthrough of one of the more optimal and forward leaning approaches for establishing a standardized API lifecycle across your teams, helping ensure that the API lifecycle is driven by machine readable artifacts, and possesses clear steps for moving API artifacts from design to production in a way that everyone can understand while incentivizing collaboration at each stop along the way.