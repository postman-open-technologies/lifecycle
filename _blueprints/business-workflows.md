---
name: Build a Business Workflow
description: A blueprint for beginning the API lifecycle by designing a new API using an OpenAPI.
image: https://postman-toolboxes2.s3.amazonaws.com/assets/api.png
tags:
  - OpenAPI
  - Design-First
stage: Automation
type: sync
order: 1
areas:  

  - label: Define
    description: Ensuring that operations supporting an API is properly defined, as well as what is needed to properly design and bring an API to life. A little planning and organization at this step of an APIs journey can go a long way towards ensuring the overall health and velocity of an API, and the applications that depend on this internal, partner, or public API.
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Team Workspace
        label: Team Workspace
  - label: Design
    image: images/lifecycle-arrow-design.png
    description: Having a formal process and approach to designing an API helps establish consistency and the precision of APIs in production, ensuring that APIs are developed using common patterns across an industry, and within an organization, establishing known practices for shaping the surface area and behaviors of APIs that applications are depending upon.
    elements:
      - name: Workflow Collection
        label: Workflow Collection       
  - label: Document
    image: images/lifecycle-arrow-document.png
    description: Having complete, accurate, and easy to follow document is essential for all APIs, helping alleviate the number one pain point for API consumers when it comes to onboarding with an API, as well as expanding the number of API paths an application puts to work, making API documentation one of the most important areas of the API lifecycle.
    elements:
      - name: Workflow Documentation
        label: Workflow Documentation     
  - label: Test
    image: images/lifecycle-arrow-test.png
    description: A test-driven API lifecycle ensures that each API accomplishes the intended purpose it was developed for, providing manual and automated ways to ensure an API hasn't changed unexpectedly, is as performant as required, and meets the security expectations of everyone involved, helping establish a high quality of service consistently across all APIs.
    elements:
      - name: Workflow Testing
        label: Workflow Testing   
  - label: Monitor
    image: images/lifecycle-arrow-monitor.png
    description: All tests applied to an API should be monitored on a logical schedule and from relevant geographic regions, monitoring that APIs aren't breaking their contract, falling below their agreed upon service level agreement (SLA), or becoming a security risk, helping automate the quality of service across APIs in a way that allows teams to be as productive as possible.
    elements:
      - name: Workflow Testing Monitor
        label: Workflow Testing Monitor    
      - name: Workflow Testing Monitor Results
        label: Workflow Testing Monitor Results  
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
      - name: Workflow Monitor Report
        label: Workflow Monitor Report           
      - name: Application Performance Management (APM)  
        label: Application Performance Management (APM)                                      
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/29
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/business-workflows.md
...
<p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.</p>
