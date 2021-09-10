---
name: Everything but the Kitchen Sink
description: Contains all of the elements grouped by some of the common areas of the API lifecycle.
image: https://postman-toolboxes2.s3.amazonaws.com/assets/api.png
tags:
  - Default
stage: Master
type: sync
order: 1
maturity: draft
areas:  

  - label: Define
    description: Ensuring that operations supporting an API is properly defined, as well as what is needed to properly design and bring an API to life. A little planning and organization at this step of an APIs journey can go a long way towards ensuring the overall health and velocity of an API, and the applications that depend on this internal, partner, or public API.
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Overview
        label: Overview      
      - name: Private Workspace
        label: Private Workspace
      - name: Team Workspace
        label: Team Workspace
      - name: Partner Workspace
        label: Partner Workspace          
      - name: Public Workspace
        label: Public Workspace                
      - name: Team
        label: Team  
      - name: Roles
        label: Roles               
      - name: Github Repository
        label: Github Repository
      - name: Bitbucket Repository
        label: Bitbucket Repository
      - name: Gitlab Repository
        label: Gitlab Repository                
      - name: Use Cases
        label: Use Cases  
      - name: Goals
        label: Goals    
      - name: Relationships
        label: Relationships     
      - name: Environments
        label: Environments              
      - name: Schema
        label: Schema 
      - name: Examples
        label: Examples   
      - name: Data Sources
        label: Data Sources  
      - name: Role Based Access Control
        label: Role Based Access Control    
      - name: OpenAPI
        label: OpenAPI     
      - name: WSDL
        label: WSDL  
      - name: Scripts
        label: Scripts                                                                          
  - label: Design
    description: Having a formal process and approach to designing an API helps establish consistency and the precision of APIs in production, ensuring that APIs are developed using common patterns across an industry, and within an organization, establishing known practices for shaping the surface area and behaviors of APIs that applications are depending upon.
    image: images/lifecycle-arrow-design.png
    elements:
      - name: Prototype Collection
        label: Prototype Collection  
      - name: Workflow Collection
        label: Workflow Collection      
      - name: OpenAPI
        label: OpenAPI     
      - name: WSDL
        label: WSDL   
      - name: Design Patterns
        label: Design Patterns        
  - label: Mock
    description: Mocking how an API works and behaves provides an effective way for teams to collaborate, communicate, and iterate as part of the design of an API, but also is something that can be used as part of testing, or just providing a sandbox environment for API consumers to learn before they actually begin working with any API in production.
    image: images/lifecycle-arrow-mock.png
    elements:
      - name: Mock Server
        label: Mock Server
      - name: Examples
        label: Examples 
  - label: Document
    description: Having complete, accurate, and easy to follow document is essential for all APIs, helping alleviate the number one pain point for API consumers when it comes to onboarding with an API, as well as expanding the number of API paths an application puts to work, making API documentation one of the most important areas of the API lifecycle. 
    image: images/lifecycle-arrow-document.png
    elements:
      - name: Reference Documentation
        label: Reference Documentation
      - name: Onboarding Documentation
        label: Onboarding Documentation   
      - name: Workflow Documentation
        label: Workflow Documentation           
      - name: Examples
        label: Examples   
      - name: Code Annotations
        label: Code Annotations    
      - name: Interceptor
        label: Interceptor  
      - name: Proxy
        label: Proxy                               
  - label: Test
    description: A test-driven API lifecycle ensures that each API accomplishes the intended purpose it was developed for, providing manual and automated ways to ensure an API hasn't changed unexpectedly, is as performant as required, and meets the security expectations of everyone involved, helping establish a high quality of service consistently across all APIs.
    image: images/lifecycle-arrow-test.png
    elements:
      - name: Contract Testing
        label: Contract Testing   
      - name: Performance Testing
        label: Performance Testing   
      - name: Security Testing
        label: Security Testing   
      - name: Workflow Testing
        label: Workflow Testing    
      - name: Uptime Testing
        label: Uptime Testing       
      - name: Integration Testing
        label: Integration Testing   
      - name: Linting
        label: Linting   
      - name: Scripts
        label: Scripts                                                                         
  - label: Deploy
    description: Establishing a well defined process for deploy an API helps teams deploy new APIs, as well as each future iteration of an API in a consistent and repeatable way, making sure APIs are deployed using known development, staging, production, other agreed upon stages that actively put to work the other elements like documentation, testing, while contributing to observability.   
    image: images/lifecycle-arrow-deploy.png
    elements:
      - name: Pipeline
        label: Pipeline
      - name: Gateway
        label: Gateway   
      - name: Business Logic
        label: Business Logic    
      - name: Resolvers
        label: Resolvers        
  - label: Code
    description: Providing either server or client side code that helps make it easier to produce, consume, and integrate with APIs, helping reduce friction and increase velocity of teams by providing many of the common needs developers will need to put APIs to work across operations.
    image: images/lifecycle-arrow-code.png
    elements:   
      - name: Code
        label: Code       
      - name: Client SDKs
        label: Client SDKs   
      - name: Client Snippets
        label: Client Snippets                  
  - label: Manage
    description: APIs should be managed using a set of common, well-defined policies that define and govern how APIs are access via all stages of the lifecycle, and ensure that every API has relevant authentication, rate limits, logging, and other essential aspects of managing APIs at scale, helping strike a balance between making APIs accessible and the privacy and security concerns that exist.
    image: images/lifecycle-arrow-manage.png
    elements:
      - name: Onboarding
        label: Onboarding
      - name: Authentication
        label: Authentication   
      - name: Usage Plan
        label: Usage Plan    
      - name: Key
        label: Key  
      - name: Applications
        label: Applications  
      - name: Automation
        label: Automation  
      - name: Client
        label: Client   
  - label: Monitor
    description: All tests applied to an API should be monitored on a logical schedule and from relevant geographic regions, monitoring that APIs aren't breaking their contract, falling below their agreed upon service level agreement (SLA), or becoming a security risk, helping automate the quality of service across APIs in a way that allows teams to be as productive as possible.
    image: images/lifecycle-arrow-monitor.png
    elements:
      - name: Monitor
        label: Monitor
      - name: Contract Testing Monitor
        label: Contract Testing Monitor  
      - name: Contract Testing Monitor Results
        label: Contract Testing Monitor Results           
      - name: Performance Testing Monitor
        label: Performance Testing Monitor  
      - name: Performance Testing Monitor Results   
        label: Performance Testing Monitor Results           
      - name: Security Testing Monitor
        label: Security Testing Monitor  
      - name: Security Testing Monitor Results   
        label: Security Testing Monitor Results           
      - name: Workflow Testing Monitor
        label: Workflow Testing Monitor    
      - name: Workflow Testing Monitor Results
        label: Workflow Testing Monitor Results            
      - name: Integration Testing Monitor
        label: Integration Testing Monitor   
      - name: Integration Testing Monitor Results
        label: Integration Testing Monitor Results   
      - name: Uptime Testing Monitor Results
        label: Uptime Testing Monitor Results                                                  
  - label: Automation
    description: Automating producing or consumption of API resources and capabilities, allowing for repeatable API-driven process to be triggered, scheduled, or respond to events, allowing for teams to properly define and set into motions certain aspects of operations while they focus on the more manual, creative, and human aspects of doing APIs. 
    image: images/lifecycle-arrow-security.png
    elements:
      - name: Monitor
        label: Monitor   
      - name: Scripts
        label: Scripts         
      - name: Newman
        label: Newman                 
  - label: Discover
    description: The ability to discover APIs at all stages of the API lifecycle is key to reduce redundancy across operations, helping teams find existing APIs before they develop new ones, and properly match API consumers with the right APIs, supporting documentation, relevant workflows, and the feedback loops that exist as part of the operation of APIs internally within the enterprise, or externally with 3rd party developers.
    image: images/lifecycle-arrow-discover.png
    elements:
      - name: Private Network
        label: Private Network   
      - name: Public Network
        label: Public Network   
      - name: Search
        label: Search 
  - label: Security
    description: Ensuring that all digital resources and capabilities are properly secured from end to end, making sure proper identity and access management, vulnerability scanning, and other common approaches to securing infrastructure on the Internet is in place and properly maintained.
    image: images/lifecycle-arrow-security.png
    elements:
      - name: Secure
        label: Secure
      - name: Role Based Access Control
        label: Role Based Access Control
      - name: Authentication
        label: Authentication
      - name: Security Testing
        label: Security Testing
  - label: Observability
    description: Tapping into the outputs available across API operations to understand what is happening with individual APIs throughout their lifecycle, but also in aggregate for domains, teams, and other logical groups, helping make API operations more visible in real time.
    image: images/lifecycle-arrow-observability.png
    elements:
      - name: Activity
        label: Activity 
      - name: Reports
        label: Reports
      - name: Change Log
        label: Change Log   
      - name: Audit
        label: Audit     
      - name: Uptime Monitor Report
        label: Uptime Monitor Report   
      - name: Gateway Usage Report
        label: Gateway Usage Report  
      - name: Security Monitor Report
        label: Security Monitor Report
      - name: Contract Testing Monitor Report
        label: Contract Testing Monitor Report    
      - name: Performance Monitor Report
        label: Performance Monitor Report   
      - name: Integration Monitor Report
        label: Integration Monitor Report           
      - name: Application Performance Management (APM)  
        label: Application Performance Management (APM)  
      - name: Workflow Monitor Report
        label: Workflow Monitor Report            
      - name: Intelligence
        label: Intelligence                                      
  - label: Communicate
    description: Communicate with API stakeholders syncronously and asyncronously across the API lifecycle, localizing the conversation around what is happening around each API, while also allowing for seamless integration with exiting communication channels, allowing teams to efficiently share knowledge in the moment.  
    image: images/lifecycle-arrow-communications.png
    elements:
      - name: Notifications
        label: Notifications  
      - name: Comments
        label: Comments  
      - name: Inform
        label: Inform    
  - label: Collaborate
    description: Collaborating across teams and lines of business to securely share artifacts from across API operations, providing more visibility across the workspaces where developers are already producing and consuming APIs, while providing many different types of collaboration opportunities as they work.  
    image: images/lifecycle-arrow-collaborate.png
    elements:
      - name: Sharing
        label: Sharing      
      - name: Watching
        label: Watching 
      - name: Forking
        label: Forking   
      - name: Inviting
        label: Inviting   
      - name: Mentions
        label: Mentions                                            
  - label: Governance
    description: Defining all the practices and process across the organization for delivering APIs, establishing well known and communicated areas, elements, and actions that shape how API operations function, providing all teams with what they need to effectively deliver API infrastructure from start to finish.
    image: images/lifecycle-arrow-governance.png
    elements:
      - name: Design Patterns
        label: Design Patterns  
      - name: Documentation Rules
        label: Documentation Rules 
      - name: Management Rules
        label: Management Rules         
      - name: Linting
        label: Linting                                        
  - label: Retire
    description: Having a plan for the eventual retirement and ultimate deprecation of an API, or for specific paths or versions of an API should be a part of every API lifecycle, even when there is no plan for deprecation there should be a process in place for setting expectations for how long an API will be supported, as well as formal process to follow once retirement comes into view on the horizon.    
    image: images/lifecycle-arrow-retire.png 
    elements:
      - name: Retire
        label: Retire  
      - name: Deprecate
        label: Deprecate    
      - name: Archive
        label: Archive      
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/20     
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/everything.md      
...
<p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.</p>