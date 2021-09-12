---
name: Build a Business Workflow
description: This API lifecycle blueprint focuses on defining common business workflows, then automating around these well defined scenarios. Defining collections across multiple APIs, including authentication, scripting, data, environments, then automate using monitors and pipelines.
conclusion: This blueprint looks at how you can approach the development and operation of API-driven workflows using a well defined API lifecycle. Each element within this blueprint works to provide a simple overview of what is involved across the entire life of an API, with more detail present on the detail page for each element (if you are viewing this on the API lifecycle project site). If you are reading this via a PDF or printed version you can visit the landing page for this blueprint to access more information and view specific actions you might possibly consider taking as part of applying each element of this proposed lifecycle within your own operations. This blueprint is a living document and will continue to evolve and be added to over time based upon feedback from readers. If you have any questions, feedback, or feel like there is more information you need, feel free to jump on the Github discussion for this blueprint, or any of the individual elements present--the value this blueprint provides is actively defined by the feedback community members like you.
image: workflow.png
tags:
  - OpenAPI
  - Design-First
stage: Automation
type: sync
order: 1
maturity: stable
version: 2021-09-11
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
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/29
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/business-workflows.md
...
A standardized API lifecycle can be applied to the design, development, and usage of API business workflows that are defined as machine readable collections which can be automated using monitors and CI/CD pipelines. Postman collections provide a versatile approach to defining multiple individual API requests that include authentication, parameters, headers, and other details, then organize into folders and specific sequences. Providing a format for defining, documenting, but then also executing common business workflows across many internal, partner, or external APIs. Something becomes endlessly useful when managed as part of a well defined lifecycle, equipping developers with what they need to define and design the workflows, but also maintain them, execute them, and use them to automate a variety of business tasks that exist in their worlds.
