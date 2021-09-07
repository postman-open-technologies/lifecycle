---
name: New API Using the AsyncAPI Specification
description: A blueprint for beginning an event-driven API lifecycle by designing a new API using an AsyncAPI.
image: https://postman-toolboxes2.s3.amazonaws.com/assets/api.png
tags:
  - OpenAPI
  - Design-First
stage: New
type: async
order: 2
areas:  

  - label: Define
    image: images/lifecycle-arrow-define.png
    description: Ensuring that operations supporting an API is properly defined, as well as what is needed to properly design and bring an API to life. A little planning and organization at this step of an APIs journey can go a long way towards ensuring the overall health and velocity of an API, and the applications that depend on this internal, partner, or public API.
    elements:
      - name: Use Cases
        label: Use Cases
      - name: Schema
        label: Schema        
      - name: Events
        label: Events
      - name: Application
        label: Application       
  - label: Develop
    image: images/lifecycle-arrow-deploy.png  
    description: Provide a mock for the API.
    elements:
      - name: Code
        label: Code
      - name: Business Logic
        label: Business Logic 
  - label: Operate
    description: Operate an API in production. 
    image: images/lifecycle-arrow-manage.png  
    elements:
      - name: Deploy
        label: Deploy
      - name: Secure
        label: Secure    
      - name: Audit
        label: Audit   
      - name: Monitor
        label: Monitor       
      - name: Inform
        label: Inform  
  - label: Discover
    image: images/lifecycle-arrow-discover.png
    description: Discovery involving an API.
    elements:
      - name: Events
        label: Events    
      - name: Relationships
        label: Relationships                                                          
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/19
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/new-api-using-the-asyncapi-specification.md
...
<p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.</p>