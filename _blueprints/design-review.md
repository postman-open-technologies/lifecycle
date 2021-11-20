---
name: Design Review
description: A design review establishes a period in which an API designer or developer can submit an API for review by a formal design reviewer, as well as architects from a centralized API governance group, evaluating the API for compliance against an organizations governance design guidelines.
conclusion: This blueprint is meant to provide a standardized approach to automating API design reviews across operations as part of a standardized API lifecycle. Each element within this blueprint works to provide a simple overview of what is involved across the entire life of an API, with more detail present on the detail page for each element (if you are viewing this on the API lifecycle project site). If you are reading this via a PDF or printed version you can visit the landing page for this blueprint to access more information and view specific actions you might possibly consider taking as part of applying each element of this proposed lifecycle within your own operations. This blueprint is a living document and will continue to evolve and be added to over time based upon feedback from readers. If you have any questions, feedback, or feel like there is more information you need, feel free to jump on the Github discussion for this blueprint, or any of the individual elements present--the value this blueprint provides is actively defined by the feedback community members like you.
image: test-automation.png
tags:
  - OpenAPI
  - Design-First
stage: Governance
type: sync
order: 1
maturity: draft
version: 2021-09-11
areas:  

  - label: Define
    description: Each API being submitted as part of an API design review process should possess the necessary artifacts and elements needed to properly evaluate the design of each API. To ensure the API design review is as efficient and effective as possible it helps to have a dedicated location for the review to happen, with everything present to to conduct review, and provide feedback around the API, as well as supporting elements. Setting the stage for a speedy but effective review, sending an API back development, or allowing it to move everything forward to production.
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Team Workspace
        label: Team Workspace
        context: 1
      - name: Team Members
        label: Team Members   
        context: 1    
      - name: Github Repository
        label: Github Repository
        context: 1
      - name: Design Rules
        label: Design Rules        
        context: 1          
      - name: OpenAPI
        label: OpenAPI      
        context: 1  
      - name: Reference Documentation
        label: Reference Documentation      
        context: 1   
      - name: Examples
        label: Examples      
        context: 1   
      - name: Mock Server
        label: Mock Server      
        context: 1  
      - name: Examples
        label: Examples      
        context: 1    
      - name: Contract Testing
        label: Contract Testing   
        context: 1          

  - label: Process
    image: images/lifecycle-arrow-test.png
    description: Once ready, with all the needed artifacts and element, an API should be submitted to a well defined process for reviewing the design of an API, then providing feedback on the state of an API, and whether it is ready for production, in as short of time as possible. Reaching a desireable outcome that upholds an organization's design guidelines, and helps make teams better at what they do. Ensuring that eery API design review is a learning opportunity for both designer and reviewer. Continuing to improve the API design process with each API submitted for review, making operations incrementally better along the way.
    elements:
      - name: Design Review
        label: Design Review
      - name: Design Review Timeline
        label: Design Review Timeline
      - name: Design Review Feedback
        label: Design Review Feedback
      - name: Design Review Outcomes
        label: Design Review Outcomes                        

discussion: https://github.com/postman-open-technologies/lifecycle/discussions/33
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/test-automation.md
roles:
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
This blueprint works to provide a high level walk-through what an API design review process can look like. API design reviews give pause before any API goes into to production to make sure every APIs meets the design standards of an organization. Designers and developers should have a wealth of resources to help them design the best possible API before it gets submitted, but the injection of the design process ensures that each API gets attention from designer reviewers, architects, and anyone else who might speak to the value an API should deliver, and the needs of consumers. APIs design processes will make your APIs better, your teams better, and your overall organization better at doing what it does best. 