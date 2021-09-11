---
name: Generate OpenAPI a New API Using Code Annotations
description: A blueprint for beginning the API lifecycle by automatically generating an OpenAPI.
image: https://postman-toolboxes2.s3.amazonaws.com/assets/api.png
tags:
  - OpenAPI
  - Prototype-First
stage: Existing
type: sync
order: 5
maturity: stable
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
  - label: Deploy
    image: images/lifecycle-arrow-deploy.png
    description: The road to setting a new code-first or existing API on a road to a standardized API lifecycle often times begins with the generation of an OpenAPI from annotations in the code as part of a build process. Relying on annotations for each code method to produce an API for the surface area of the API, updating the OpenAPI, and other supporting documentation and tests using a CI/CD pipeline. Bypassing the API design process and going with a code-first approach to delivering an API, and relying on the pipeline for the existing software development lifecycle to generate the OpenAPI, and set in motion the delivery of documentation, testing, and other elements of the API lifecycle.
    elements:
      - name: CI/CD Pipeline
        label: CI/CD Pipeline
        context: 1
      - name: Code Annotations
        label: Code Annotations  
        context: 1
      - name: OpenAPI
        label: OpenAPI                  
        context: 1
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
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/15 
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/generate-openapi-from-code-annotations.md 
...
Not all APIs and the teams developing them are able to embrace a design first approach to delivering APIs and sometimes it makes more sense for developers to write the code first, then provide annotations within the code that can be used to generate OpenAPI definitions for each API as part of the regular build process. It is important that there is an OpenAPI contract for each API, so that documentation, mocks, testing, and other elements can be generated, but not all teams will be able to hand-craft the OpenAPI from scratch. Making code annotations a valid approach to developing an API using a code-first approach, but still realizing the benefits of having an up to date machine readable contract present for each API as it evolves throughout the lifecycle.