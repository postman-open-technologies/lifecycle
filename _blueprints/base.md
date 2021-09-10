---
name: The Base of the API Lifecycle
description: This represents the base of the API lifecycle that anyone should be thinking about.
image: https://postman-toolboxes2.s3.amazonaws.com/assets/api.png
tags:
  - Default
stage: Master
type: sync
order: 1
areas:  

  - label: Discover
    description: Before starting a new API product, it is important to discover if the solution to the problem you're trying to solve already exists. Building on already existing functionality brings products and services to market faster. Postman has a number of features that makes this discovery step easier.
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
    description: Designing an interface is one of the most critical steps in the API's lifecycle. It involves making decisions on how the interface will look and feel when used. American software engineer Grady Booch calls these decisions "significant", where significance is measured by the cost of change. Once your API has its first user, the cost of changing that interface increases significantly. Applying the appropriate rigor at this stage of the lifecycle will decrease the likelihood that change is necessary later. 
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
    description: At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio.
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
    description: APIs usefulness to automation also makes APIs a potential target for malicious actors. Ensuring security is accounted for and applied consistently for all APIs produced is an incredibly important step. 
    elements:
      - name: Role Based Access Control
        label:  Role Based Access Control      
      - name: Security Testing
        label: Security Testing      
      - name: Authorization
        label: Authorization 
  - label: Monitor
    image: images/lifecycle-arrow-monitor.png
    description: In order to properly manage APIs and how they flow through the API lifecycle, it is vital to have accurate and up-to-date information. Postman provides a number of useful features to track APIs across the platform.
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
    description: Markets, strategies, team experience, and professional expectations change. So too do APIs. Changing an interface is no trivial task, however, given the number of people that may depend on it. Learning to prioritize and schedule changes to minimize the negative impacts is a skill. Thankfully, Postman includes features to navigate through this important step.
    elements:
      - name: Versioning
        label: Versioning
      - name: Deprecate
        label: Deprecate         
discussion: 'https://github.com/postman-open-technologies/lifecycle/discussions/27'
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/base.md
...
<p>Every organization creating APIs has an API lifecycle, whether they know it or not. The difference separating high-performing API companies from those with inconsistent results is a thoughtful and practiced approach. Below are key aspects of the API lifecycle, common characterists worth focusing on, and how Postman’s API platform supports each. </p>
