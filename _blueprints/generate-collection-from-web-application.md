---
name: Generate Collection From Web Application API
description: This blueprint introduces how APIs behind web applications can be reverse engineered and defined as a collection so that documentation, testing, and other common areas of the API lifecycle can be applied to help stabilize the APIs we depend on behind our applications.
conclusion: This blueprint intends to provide a look at how you can bring an API into a standardized API lifecycle by reverse engineering API traffic using Postman Interceptor. Each element within this blueprint works to provide a simple overview of what is involved across the entire life of an API, with more detail present on the detail page for each element (if you are viewing this on the API lifecycle project site). If you are reading this via a PDF or printed version you can visit the landing page for this blueprint to access more information and view specific actions you might possibly consider taking as part of applying each element of this proposed lifecycle within your own operations. This blueprint is a living document and will continue to evolve and be added to over time based upon feedback from readers. If you have any questions, feedback, or feel like there is more information you need, feel free to jump on the Github discussion for this blueprint, or any of the individual elements present--the value this blueprint provides is actively defined by the feedback community members like you.
image: web-application.png
tags:
  - OpenAPI
  - Prototype-First
stage: Reverse
type: sync
order: 6
maturity: stable
version: 2021-09-11
areas: 

  - label: Define
    image: images/lifecycle-arrow-define.png
    description: Ensuring that operations supporting an API is properly defined, as well as what is needed to properly design and bring an API to life. A little planning and organization at this step of an APIs journey can go a long way towards ensuring the overall health and velocity of an API, and the applications that depend on this internal, partner, or public API.
    elements:
      - name: Interceptor
        label: Interceptor 
      - name: Traffic Collection
        label: Traffic Collection      
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
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/12      
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/generate-collection-from-web-application.md
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
APIs behind web applications are often developed with it's use beyond it's immediate purpose within a single application, resulting in the need to reverse engineer, document, test, and move forward as a standardized API as part of a well known API lifecycle in the future. This is a common entry into the API lifecycle for an existing API, acknowledging that APIs will regularly be brought to life to support a specific need, but then eventually they should be standardized and made usable across multiple applications and integrations. The Postman Interceptor provides an effective way to capture traffic behind the web applications we use each day and route the traffic into a collection for cleaning up, documenting, and then potentially testing and monitoring as part of a formal API lifecycle. Providing a robust approach to rapidly mapping out API infrastructure behind our web applications, and then ensuring they are well documented and reliable for use beyond a single application. 