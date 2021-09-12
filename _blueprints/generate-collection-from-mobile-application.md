---
name: Generate Collection From Mobile Application API
description: This blueprint introduces how APIs behind mobile applications can be reverse engineered and defined as a collection so that documentation, testing, and other common areas of the API lifecycle can be applied to help stabilize the APIs we depend on behind our applications.
conclusion: This blueprint intends to provide a look at how you can bring an API into a standardized API lifecycle by reverse engineering API traffic behind a mobile application using a proxy  Each element within this blueprint works to provide a simple overview of what is involved across the entire life of an API, with more detail present on the detail page for each element (if you are viewing this on the API lifecycle project site). If you are reading this via a PDF or printed version you can visit the landing page for this blueprint to access more information and view specific actions you might possibly consider taking as part of applying each element of this proposed lifecycle within your own operations. This blueprint is a living document and will continue to evolve and be added to over time based upon feedback from readers. If you have any questions, feedback, or feel like there is more information you need, feel free to jump on the Github discussion for this blueprint, or any of the individual elements present--the value this blueprint provides is actively defined by the feedback community members like you.
image: mobile-application.png
tags:
  - OpenAPI
  - Prototype-First
stage: Reverse
type: sync
order: 7
maturity: stable
version: 2021-09-11
areas: 

  - label: Define
    image: images/lifecycle-arrow-define.png
    description: Ensuring that operations supporting an API is properly defined, as well as what is needed to properly design and bring an API to life. A little planning and organization at this step of an APIs journey can go a long way towards ensuring the overall health and velocity of an API, and the applications that depend on this internal, partner, or public API.
    elements:
      - name: Proxy
        label: Proxy 
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
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/10
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/generate-collection-from-mobile-application.md
...
Mobile applications are often developed rapidly using APIs without much consideration for how those APIs will be used beyond the current project. Mobile applications are often developed by teams and contractors who may not have exposure to the standardized development of APIs within an organization which would allow for APIs to be reused across multiple applications and integrations. A recurring situation that will make it necessary to reverse engineer the APIs behind a mobile application, generate a collection, documentation, and establish testing and monitors that help provide more observability into what is happening with API infrastructure behind the mobile applications we depend on. Postman provides a proxy for routing mobile traffic and generating a collection that describes the surface area of requests and responses, allowing it to be cleaned up, documented, then available for testing, monitoring, and discovery. Providing a powerful way to reverse engineer existing APIs behind mobile applications, but them make them more visible and reusuable across an organization, helping eliminate redundancy across operations.