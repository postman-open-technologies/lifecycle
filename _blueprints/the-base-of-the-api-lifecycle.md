---
name: The Base of the API Lifecycle
description: This blueprint illustrates what we consider to be the base of the API lifecycle, providing a starting point for additional lifecycle variations elsewhere on this site. Depending on your priorities and your entry point, you may need to expand or remove from this base lifecycle to match your desired situation.
image: lifecycle.png
tags:
  - Default
stage: Master
type: sync
order: 1
maturity: mature
version: 2021-09-11
areas:  

  - label: Define
    description: Making sure the operations around an API are properly defined, laying the foundation for being able to effectively design and bring an API to life, while also establishing a known place, or places to go to get all the information you need regarding each individual API or groups of APIs. 
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Team Members
        label: Team Members
      - name: Team Workspace
        label: Team Workspace
      - name: Public Workspace
        label: Public Workspace
      - name: Github Repository
        label: Github Repository          
  - label: Design
    image: images/lifecycle-arrow-design.png
    description: Establishing a formal process and approach to designing an API helps establish consistency of each API that ends up in production, ensuring that APIs are developed using common industry and organizational patterns while establishing known practices for shaping the surface area and behaviors of APIs.
    elements:
      - name: OpenAPI
        label: OpenAPI    
      - name: Mock Server
        label: Mock Server   
      - name: Comments
        label: Comments      
  - label: Document
    image: images/lifecycle-arrow-document.png
    description: Having complete, accurate, and easy to follow documentation is essential for all APIs, alleviating the number one pain point for API consumers when it comes to onboarding with APIs, providing the human-readable technical details of what an API does, helping minimize the time to first API call.
    elements:
      - name: Reference Documentation
        label: Reference Documentation 
        context: 1  
      - name: Examples
        label: Examples
        context: 1            
  - label: Deploy
    image: images/lifecycle-arrow-deploy.png
    description: Providing a well-defined process to deploy an API into development, staging, and production environments, helping teams efficiently deliver future iterations of an API in a consistent and repeatable way, ensuring that APIs are properly tested, secured, and governed as a native part of the deployment process.
    elements:
      - name: CI/CD Pipeline
        label: CI/CD Pipeline
        context: 1
      - name: Gateway
        label: Gateway     
        context: 1  
      - name: Usage Plan
        label: Usage Plan    
        context: 1        
  - label: Test
    image: images/lifecycle-arrow-test.png
    description: A test-driven API lifecycle ensures that each API delivers the intended outcomes it was developed for in the first place, providing manual as well as automated ways to ensure an API hasn't changed unexpectedly and is as performant as required, helping establish a high quality of service consistently across all APIs. 
    elements:
      - name: Contract Testing
        label: Contract Testing  
        context: 1 
      - name: Performance Testing
        label: Performance Testing   
        context: 1             
  - label: Secure
    image: images/lifecycle-arrow-test.png
    description: Ensuring that there is a consistent approach to identity and access management for each API, but also the proper security testing in place to make sure that all APIs are being secured in a consistent way no matter which team developed them, or whether they will be used for private, partner, or public use in applications.
    elements:
      - name: Authentication
        label: Authentication
        context: 1         
      - name: Security Testing
        label: Security Testing   
        context: 1  
  - label: Monitor
    image: images/lifecycle-arrow-monitor.png
    description: Making sure that all APIs are fully monitored by scheduling contract, performance, security, and other tests from multiple cloud regions, but also being able to monitor the activity, changelog, and state of an API using notifications, helping keep teams and consumers informed regarding the state of the APIs they depend on.
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
      - name: Activity
        label: Activity  
      - name: Change Log
        label: Change Log   
      - name: Notifications
        label: Notifications                                  
  - label: Discover
    image: images/lifecycle-arrow-discover.png
    description: Enabling discovery across operations, helping teams find existing APIs before they develop new ones, properly matching API consumers with the right APIs, while supporting documentation, workflows, and the feedback loops that exist as part of the operation of internal, partner, and public APIs supporting applications and integrations.
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
       
discussion: 'https://github.com/postman-open-technologies/lifecycle/discussions/27'
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/base.md
...
The API lifecycle will mean many different things depending on who you are talking to. This base API lifecycle isn't meant to be a lifecycle definition that matches the needs of every enterprise organization, but is intended to provide you with a base example to help you begin thinking about what your own API lifecycle is. The blueprint is designed to provide you a base that you can add to or remove from, iterating upon until you find a common definition of the API lifecycle that works for your organization.
