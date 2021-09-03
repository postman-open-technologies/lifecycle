---
name: New API Using the OpenAPI Specification
description: A blueprint for beginning the API lifecycle by designing a new API using an OpenAPI.
image: https://postman-toolboxes2.s3.amazonaws.com/assets/api.png
tags:
  - OpenAPI
  - Design-First
stage: New
type: sync
order: 1
areas:  

  - label: Define
    description: Ensuring that operations supporting an API is properly defined, as well as what is needed to properly design and bring an API to life. A little planning and organization at this step of an APIs journey can go a long way towards ensuring the overall health and velocity of an API, and the applications that depend on this internal, partner, or public API.
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Team Workspace
        label: Team Workspace
      - name: Team Members
        label: Team Members       
      - name: Github Repository
        label: Github Repository
  - label: Design
    image: images/lifecycle-arrow-design.png
    description: Having a formal process and approach to designing an API helps establish consistency and the precision of APIs in production, ensuring that APIs are developed using common patterns across an industry, and within an organization, establishing known practices for shaping the surface area and behaviors of APIs that applications are depending upon.
    elements:
      - name: OpenAPI
        label: OpenAPI      
  - label: Mock
    image: images/lifecycle-arrow-mock.png
    description: Mocking how an API works and behaves provides an effective way for teams to collaborate, communicate, and iterate as part of the design of an API, but also is something that can be used as part of testing, or just providing a sandbox environment for API consumers to learn before they actually begin working with any API in production.
    elements:
      - name: Mock Server
        label: Mock Server
      - name: Examples
        label: Examples 
  - label: Document
    image: images/lifecycle-arrow-document.png
    description: Having complete, accurate, and easy to follow document is essential for all APIs, helping alleviate the number one pain point for API consumers when it comes to onboarding with an API, as well as expanding the number of API paths an application puts to work, making API documentation one of the most important areas of the API lifecycle.
    elements:
      - name: Reference Documentation
        label: Reference Documentation     
  - label: Test
    image: images/lifecycle-arrow-test.png
    description: A test-driven API lifecycle ensures that each API accomplishes the intended purpose it was developed for, providing manual and automated ways to ensure an API hasn't changed unexpectedly, is as performant as required, and meets the security expectations of everyone involved, helping establish a high quality of service consistently across all APIs.
    elements:
      - name: Contract Testing
        label: Contract Testing   
      - name: Performance Testing
        label: Performance Testing   
      - name: Security Testing
        label: Security Testing   
  - label: Monitor
    image: images/lifecycle-arrow-monitor.png
    description: All tests applied to an API should be monitored on a logical schedule and from relevant geographic regions, monitoring that APIs aren't breaking their contract, falling below their agreed upon service level agreement (SLA), or becoming a security risk, helping automate the quality of service across APIs in a way that allows teams to be as productive as possible.
    elements:
      - name: Contract Monitor
        label: Contract Monitor   
      - name: Performance Monitor
        label: Performance Monitor   
      - name: Security Monitor
        label: Security Monitor                          
  - label: Deploy
    image: images/lifecycle-arrow-deploy.png
    description: Establishing a well defined process for deploy an API helps teams deploy new APIs, as well as each future iteration of an API in a consistent and repeatable way, making sure APIs are deployed using known development, staging, production, other agreed upon stages that actively put to work the other elements like documentation, testing, while contributing to observability. 
    elements:
      - name: CI/CD Pipeline
        label: CI/CD Pipeline
      - name: Gateway
        label: Gateway     
  - label: Manage
    image: images/lifecycle-arrow-manage.png
    description: APIs should be managed using a set of common, well-defined policies that define and govern how APIs are access via all stages of the lifecycle, and ensure that every API has relevant authentication, rate limits, logging, and other essential aspects of managing APIs at scale, helping strike a balance between making APIs accessible and the privacy and security concerns that exist.
    elements:
      - name: Onboarding
        label: Onboarding
      - name: Usage Plan
        label: Usage Plan    
      - name: Key
        label: Key       
  - label: Discover
    image: images/lifecycle-arrow-discover.png
    description: The ability to discover APIs at all stages of the API lifecycle is key to reduce redundancy across operations, helping teams find existing APIs before they develop new ones, and properly match API consumers with the right APIs, supporting documentation, relevant workflows, and the feedback loops that exist as part of the operation of APIs internally within the enterprise, or externally with 3rd party developers.
    elements:
      - name: Search
        label: Search     
      - name: Private Network
        label: Private Network   
      - name: Public Network
        label: Public Network                    
  - label: Retire
    image: images/lifecycle-arrow-retire.png
    description: Having a plan for the eventual retirement and ultimate deprecation of an API, or for specific paths or versions of an API should be a part of every API lifecycle, even when there is no plan for deprecation there should be a process in place for setting expectations for how long an API will be supported, as well as formal process to follow once retirement comes into view on the horizon.     
    elements:
      - name: Retire
        label: Retire  
      - name: Deprecate
        label: Deprecate       
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/9
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/design-using-openapi.md
...
This blueprint enters the API lifecycle in what is widely considered to be an API design first way, ensuring that your API effort is properly defined as you leverage OpenAPI to design, mock, document, and iterate upon the design of your API before actually writing any code. This approach is desirable because it allows for API producer and even consumer stakeholders to be involved in what an API will do early on in the process, before code is actually written. This blueprint provides one of the more optimal and forward leaning approaches to embracing a standardized API lifecycle across your teams, helping ensure the lifecycle is driven by machine readable artifacts, and has clear steps moving those artifacts from design to production in a way that everyone can understand and collaborate around.