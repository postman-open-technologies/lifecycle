---
name: Matthew
description: This is a first stab at outlining Matthews lifecycle.
image: https://postman-toolboxes2.s3.amazonaws.com/assets/api.png
tags:
  - OpenAPI
stage: New
type: sync
order: 1
areas:  

  - label: Discover
    description: 
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Search
        label: Search
      - name: Watch
        label: Team Members       
      - name: Private Network
        label: Private Network
  - label: Design
    image: images/lifecycle-arrow-design.png
    description: 
    elements:
      - name: Techniques
        label: Techniques    
      - name: Goals
        label: Goals   
      - name: Comments
        label: Comments      
      - name: Mocks
        label: Mocks      
      - name: Sharing
        label: Sharing      
      - name: Documentation
        label: Documentation 
  - label: Publish
    image: images/lifecycle-arrow-design.png
    description: 
    elements:
      - name: Document
        label: Document      
      - name: Code Generation
        label: Code Generation   
      - name: Private Network
        label: Private Network   
      - name: Public Network
        label: Public Network     
  - label: Secure
    image: images/lifecycle-arrow-design.png
    description: 
    elements:
      - name: RBAC
        label: RBAC      
      - name: Security Testing
        label: Security Testing      
      - name: Authorization
        label: Authorization 
  - label: Monitor
    image: images/lifecycle-arrow-design.png
    description: 
    elements:
      - name: Activity
        label: Activity  
      - name: Change Log
        label: Change Log  
      - name: Reporting
        label: Reporting  
      - name: Notifications
        label: Activity                          
  - label: Manage
    image: images/lifecycle-arrow-design.png
    description: 
    elements:
      - name: Versioning
        label: Versioning
      - name: Deprecate
        label: Deprecate         
discussion: ''
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/matthew.md
...
This blueprint enters the API lifecycle in what is widely considered to be an API design first way, ensuring that your API effort is properly defined as you leverage OpenAPI to design, mock, document, and iterate upon the design of your API before actually writing any code. This approach is desirable because it allows for API producer and even consumer stakeholders to be involved in what an API will do early on in the process, before code is actually written. This blueprint provides one of the more optimal and forward leaning approaches to embracing a standardized API lifecycle across your teams, helping ensure the lifecycle is driven by machine readable artifacts, and has clear steps moving those artifacts from design to production in a way that everyone can understand and collaborate around.