---
name: Maximum Viable
description: A maximum viable blueprint for all of the elements.
image: https://postman-toolboxes2.s3.amazonaws.com/assets/api.png
tags:
  - OpenAPI
  - Design-First
stage: Master
type: sync
order: 1
areas:  

  - label: Define
    description: Ensuring that operations supporting an API is properly defined, as well as what is needed to properly design and bring an API to life. A little planning and organization at this step of an APIs journey can go a long way towards ensuring the overall health and velocity of an API, and the applications that depend on this internal, partner, or public API.
    elements:
      - name: Overview
        label: Overview      
      - name: Private Workspace
        label: Private Workspace
      - name: Team Workspace
        label: Team Workspace
      - name: Public Workspace
        label: Public Workspace                
      - name: Team
        label: Team  
      - name: Roles
        label: Roles               
      - name: Github Repository
        label: Github Repository
      - name: Use Cases
        label: Use Cases   
      - name: Environments
        label: Environments             
      - name: Role Based Access Control
        label: Role Based Access Control    
      - name: Schema
        label: Schema 
      - name: Examples
        label: Examples                                            
  - label: Design
    description: Having a formal process and approach to designing an API helps establish consistency and the precision of APIs in production, ensuring that APIs are developed using common patterns across an industry, and within an organization, establishing known practices for shaping the surface area and behaviors of APIs that applications are depending upon.
    elements:
      - name: Prototype Collection
        label: Prototype Collection  
      - name: Workflow Collection
        label: Workflow Collection      
      - name: OpenAPI
        label: OpenAPI
      - name: Design Patterns
        label: Design Patterns        
  - label: Mock
    description: Mocking how an API works and behaves provides an effective way for teams to collaborate, communicate, and iterate as part of the design of an API, but also is something that can be used as part of testing, or just providing a sandbox environment for API consumers to learn before they actually begin working with any API in production.
    elements:
      - name: Mock Server
        label: Mock Server
      - name: Examples
        label: Examples 
  - label: Document
    description: Having complete, accurate, and easy to follow document is essential for all APIs, helping alleviate the number one pain point for API consumers when it comes to onboarding with an API, as well as expanding the number of API paths an application puts to work, making API documentation one of the most important areas of the API lifecycle. 
    elements:
      - name: Reference Documentation
        label: Reference Documentation
      - name: Onboarding Documentation
        label: Onboarding Documentation   
      - name: Workflow Documentation
        label: Workflow Documentation           
      - name: Examples
        label: Examples              
  - label: Test
    description: A test-driven API lifecycle ensures that each API accomplishes the intended purpose it was developed for, providing manual and automated ways to ensure an API hasn't changed unexpectedly, is as performant as required, and meets the security expectations of everyone involved, helping establish a high quality of service consistently across all APIs.
    elements:
      - name: Contract Testing
        label: Contract Testing   
      - name: Performance Testing
        label: Performance Testing   
      - name: Security Testing
        label: Security Testing   
      - name: Workflow Testing
        label: Workflow Testing           
  - label: Monitor
    description: All tests applied to an API should be monitored on a logical schedule and from relevant geographic regions, monitoring that APIs aren't breaking their contract, falling below their agreed upon service level agreement (SLA), or becoming a security risk, helping automate the quality of service across APIs in a way that allows teams to be as productive as possible.
    elements:
      - name: Contract Monitor
        label: Contract Monitor   
      - name: Performance Monitor
        label: Performance Monitor   
      - name: Security Monitor
        label: Security Monitor  
      - name: Workflow Testing Monitor
        label: Workflow Testing Monitor                                  
  - label: Deploy
    description: Establishing a well defined process for deploy an API helps teams deploy new APIs, as well as each future iteration of an API in a consistent and repeatable way, making sure APIs are deployed using known development, staging, production, other agreed upon stages that actively put to work the other elements like documentation, testing, while contributing to observability.   
    elements:
      - name: Pipeline
        label: Pipeline
      - name: Gateway
        label: Gateway     
  - label: Manage
    description: APIs should be managed using a set of common, well-defined policies that define and govern how APIs are access via all stages of the lifecycle, and ensure that every API has relevant authentication, rate limits, logging, and other essential aspects of managing APIs at scale, helping strike a balance between making APIs accessible and the privacy and security concerns that exist.
    elements:
      - name: Onboarding
        label: Onboarding
      - name: Authentication
        label: Authentication   
      - name: Usage Plan
        label: Usage Plan    
      - name: Key
        label: Key       
  - label: Discover
    description: The ability to discover APIs at all stages of the API lifecycle is key to reduce redundancy across operations, helping teams find existing APIs before they develop new ones, and properly match API consumers with the right APIs, supporting documentation, relevant workflows, and the feedback loops that exist as part of the operation of APIs internally within the enterprise, or externally with 3rd party developers.
    elements:
      - name: Private Network
        label: Private Network   
      - name: Public Network
        label: Public Network   
      - name: Search
        label: Search 
  - label: Observability
    description: Providing observability across all areas.
    elements:
      - name: Activity
        label: Activity 
      - name: Reports
        label: Reports
      - name: Change Log
        label: Change Log       
      - name: Uptime Monitor Report
        label: Uptime Monitor Report   
      - name: Gateway Usage Report
        label: Gateway Usage Report  
      - name: Security Monitor Report
        label: Security Monitor Report
      - name: Contract Monitor Report
        label: Contract Monitor Report    
      - name: Performance Monitor Report
        label: Performance Monitor Report                                         
  - label: Communicate
    description: Communicate with API stakeholders.    
    elements:
      - name: Notifications
        label: Notifications  
      - name: Comments
        label: Comments                          
  - label: Retire
    description: Having a plan for the eventual retirement and ultimate deprecation of an API, or for specific paths or versions of an API should be a part of every API lifecycle, even when there is no plan for deprecation there should be a process in place for setting expectations for how long an API will be supported, as well as formal process to follow once retirement comes into view on the horizon.     
    elements:
      - name: Retire
        label: Retire  
      - name: Deprecate
        label: Deprecate    
      - name: Archive
        label: Archive      
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/20     
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/master.md      
...
<p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.</p>