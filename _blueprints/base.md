---
name: The Base of the API Lifecycle
description: This blueprint illustrates a generic API lifecycle. It provides a starting point for subsequent lifecycle variations elsewhere on this site. Depending on your priorities and starting point, you may need to expand this base lifecycle to match your desired situation.
image: lifecycle.png
tags:
  - Default
stage: Master
type: sync
order: 1
maturity: draft
version: 2021-09-11
areas:  

  - label: Discover
    description: Before starting a new API endeavor, it is crucial to discover if the solution to the problem you're trying to solve already exists. Building on already existing functionality brings products and services to market faster. Postman has several elements that make this discovery step easier.
    image: images/lifecycle-arrow-discover.png
    elements:
      - name: Search
        label: Search
      - name: Watch
        label: Watch
      - name: Private Network
        label: Private Network
  - label: Design
    image: images/lifecycle-arrow-design.png
    description: Designing an interface is one of the most critical steps in the API's lifecycle. It involves making decisions on how the interface will look and feel when used. American software engineer Grady Booch calls these decisions "significant", where significance is measured by the cost of change. Once your API has its first user, the cost of changing that interface increases significantly. Applying the appropriate rigor at this stage of the lifecycle will decrease the likelihood that change is necessary later. This includes, but is not limited to, defining performance, functionality, and security expectations.
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
    image: images/lifecycle-arrow-deploy.png
    description: Publishing is the act of making an *implementation* available that executes a service's interface in an accessible environment. This act requires more than just pushing a deployment to a cloud host. Publishing an API entails communicating documentation and, in some cases, code to the appropriate audience. 
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
    image: images/lifecycle-arrow-security.png
    description: An APIs usefulness to automation also makes APIs a potential target for malicious actors. Ensuring security is accounted for and applied consistently for all APIs produced is a significant step. 
    elements:
      - name: Role Based Access Control
        label:  Role Based Access Control      
      - name: Security Testing
        label: Security Testing      
      - name: Authorization
        label: Authorization 
  - label: Monitor
    image: images/lifecycle-arrow-monitor.png
    description: To properly manage APIs and how they flow through the API lifecycle, it is vital to have accurate and up-to-date information. Postman provides several valuable elements to track APIs across the platform.
    elements:
      - name: Activity
        label: Activity  
      - name: Change Log
        label: Change Log  
      - name: Reporting
        label: Reporting  
      - name: Notifications
        label: Notifications                          
  - label: Manage
    image: images/lifecycle-arrow-manage.png
    description: Markets, strategies, team experience, and professional expectations change. So too, do APIs. However, changing an interface is no trivial task, given the number of integrations depending on it. Learning to prioritize and schedule changes to minimize the negative impacts is a skill. Thankfully, Postman includes elements to navigate through this step of growing importance.
    elements:
      - name: Versioning
        label: Versioning
      - name: Deprecate
        label: Deprecate         
discussion: 'https://github.com/postman-open-technologies/lifecycle/discussions/27'
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/base.md
...
<p>Every organization creating APIs has an API lifecycle, whether they know it or not. The difference separating high-performing API companies from those with inconsistent results is a thoughtful and practiced approach. Below are key aspects of the API lifecycle, common characterists worth focusing on, and how Postman’s API platform supports each. </p>
