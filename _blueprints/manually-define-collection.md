---
name: Manually Define Collection for Existing API
description: A blueprint for beginning the API lifecycle by manually defining a collection.
image: https://postman-toolboxes2.s3.amazonaws.com/assets/api.png
tags:
  - OpenAPI
  - Prototype-First
stage: Existing
type: sync
order: 4
areas:

  - label: Define
    image: images/lifecycle-arrow-define.png
    description: Ensuring that operations supporting an API is properly defined, as well as what is needed to properly design and bring an API to life. A little planning and organization at this step of an APIs journey can go a long way towards ensuring the overall health and velocity of an API, and the applications that depend on this internal, partner, or public API.
    elements:
      - name: Collection
        label: Collection    
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
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/13      
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/manually-define-collection.md       
...
<p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.</p>