---
name: Generate OpenAPI a New API Using Code Annotations
description: A blueprint for beginning the API lifecycle by automatically generating an OpenAPI.
image: https://postman-toolboxes2.s3.amazonaws.com/assets/api.png
tags:
  - OpenAPI
  - Prototype-First
stage: Active
type: sync
order: 5
areas:

  - label: Define
    image: images/lifecycle-arrow-define.png
    description: Ensuring that operations supporting an API is properly defined, as well as what is needed to properly design and bring an API to life. A little planning and organization at this step of an APIs journey can go a long way towards ensuring the overall health and velocity of an API, and the applications that depend on this internal, partner, or public API.
    elements:
      - name: Code Annotations
        label: Code Annotations  
      - name: OpenAPI
        label: OpenAPI            
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
  - label: Discover
    image: images/lifecycle-arrow-discover.png
    description: The ability to discover APIs at all stages of the API lifecycle is key to reduce redundancy across operations, helping teams find existing APIs before they develop new ones, and properly match API consumers with the right APIs, supporting documentation, relevant workflows, and the feedback loops that exist as part of the operation of APIs internally within the enterprise, or externally with 3rd party developers. 
    elements:
      - name: Private Network
        label: Private Network   
      - name: Public Network
        label: Public Network   
      - name: Search
        label: Search   
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/15 
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/generate-openapi-from-code-annotations.md 
...
Not all APIs and the teams developing them are able to embrace a design first approach to delivering APIs and sometimes it makes more sense for developers to write the code first, then provide annotations within the code that can be used to generate OpenAPI definitions for each API as part of the regular build process. It is important that there is an OpenAPI contract for each API, so that documentation, mocks, testing, and other elements can be generated, but not all teams will be able to hand-craft the OpenAPI from scratch. Making code annotations a valid approach to developing an API using a code-first approach, but still realizing the benefits of having an up to date machine readable contract present for each API as it evolves throughout the lifecycle.