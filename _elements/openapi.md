---
name: OpenAPI
description: 
  - The OpenAPI specification provides a common vocabulary for describing the surface area of request and response APIs, as well as webhooks, ensuring that API producers and consumers are on the same page when it comes to integration, but also helps stabilize multiple areas of the API lifecycle providing a contract that can be used for delivering documentation, mocks, testing, and more.
links:
  - title: OpenAPI Initiative Website
    url: https://www.openapis.org/
  - title: Specification Documentation
    url: https://spec.openapis.org/oas/latest.html
  - title: Postman Learning Center
    url: https://learning.postman.com/docs/integrations/available-integrations/working-with-openAPI/           
video: '<iframe width="560" height="315" src="https://www.youtube.com/embed/V2PWRA6q3jE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'
actions:
  - name: Import OpenAPI
  - name: Generate Collection from OpenAPI
  - name: Generate OpenAPI from Collection
  - name: Generate OpenAPI from Code Annotations  
  - name: Sync OpenAPI to Github
  - name: Watch OpenAPI
  - name: Comment on OpenAPI
  - name: Sync OpenAPI to AWS API Gateway
  - name: Generate Client Code from OpenAPI
  - name: Generate Server Code from OpenAPI
screenshots:
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png          
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png  
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png     
...
The OpenAPI acts as the contract for any HTTP API, providing a machine readable way to describe the details of each request and response in a way that can be used across the entire API lifecycle. OpenAPI can be introduced in different ways via the API lifecycle, but once introduced should be managed as the source of truth for each API, always keeping up to date and managed via Postman workspace as well as synced to relevant repositories. The OpenAPI for each API can be used to generate collections for documentation, mocking, testing, and other areas of the API lifecycle, providing executable representations of each API tailored for a specific purpose, while maintaining a single source of truth for the contract of each API that can be used to keep docs, mocks, and tests in sync, but also to validate that each API contract is being met.