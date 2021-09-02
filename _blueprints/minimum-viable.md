---
name: Minimum Viable
description: A foundational example of what the API lifecycle can be for an organization.
image: https://postman-toolboxes2.s3.amazonaws.com/assets/api.png
tags:
  - Minimum
stage: New
type: sync
order: 1
areas:  

  - label: Define
    description: Ensuring that operations supporting an API is properly defined, as well as what is needed to properly design and bring an API to life. A little planning and organization at this step of an APIs journey can go a long way towards ensuring the overall health and velocity of an API, and the applications that depend on this internal, partner, or public API.
    elements:
      - name: Team Workspace
        label: Team Workspace
      - name: Team
        label: Team        
      - name: Github Repository
        label: Github Repository
      - name: Use Cases
        label: Use Cases
  - label: Design
    description: Design the surface of the API.
    elements:
      - name: OpenAPI
        label: OpenAPI
      - name: Design Patterns
        label: Design Patterns        
  - label: Mock
    description: Provide a mock for the API.
    elements:
      - name: Mock Server
        label: Mock Server
      - name: Examples
        label: Examples 
  - label: Document
    description: Provide humans with documentation.  
    elements:
      - name: Reference Documentation
        label: Reference Documentation
      - name: Workflow Documentation
        label: Workflow Documentation        
  - label: Test
    description: Ensure an API has proper testing.  
    elements:
      - name: Contract Testing
        label: Contract Testing   
      - name: Performance Testing
        label: Performance Testing   
      - name: Security Testing
        label: Security Testing   
  - label: Monitor
    description: All tests applied to an API should be monitored on a logical schedule and from relevant geographic regions, monitoring that APIs aren't breaking their contract, falling below their agreed upon service level agreement (SLA), or becoming a security risk, helping automate the quality of service across APIs in a way that allows teams to be as productive as possible.
    elements:
      - name: Contract Monitor
        label: Contract Monitor   
      - name: Performance Monitor
        label: Performance Monitor   
      - name: Security Monitor
        label: Security Monitor                          
  - label: Deploy
    description: Deploy an instance of an API.   
    elements:
      - name: CI/CD Pipeline
        label: CI/CD Pipeline
      - name: Gateway
        label: Gateway     
  - label: Manage
    description: Manage the access to an API.
    elements:
      - name: Onboarding
        label: Onboarding
      - name: Usage Plan
        label: Usage Plan    
      - name: Key
        label: Key       
  - label: Discover
    description: Ensure an API is discoverable. 
    elements:
      - name: Private Network
        label: Private Network   
      - name: Public Network
        label: Public Network   
      - name: Search
        label: Search                  
  - label: Retire
    description: Begin the retirement of an API.      
    elements:
      - name: Retire
        label: Retire  
      - name: Deprecate
        label: Deprecate    
      - name: Archive
        label: Archive      
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/9
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/design-using-openapi.md
...
<p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.</p>