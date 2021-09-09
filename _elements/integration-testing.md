---
name: Integration Testing
description: 
  - Integration tests can be defined for any API using executable and shareable collections, testing integrations, as well as other more custom scenarios or business approaches, providing a single or suite of integration tests that can be manually run, schedule across multiple regions, or executed as part of a CI/CD pipeline, automating integration testing consistently across APIs.
links:
    - title: Link Title
      url: http://example.com
    - title: Link Title
      url: http://example.com
    - title: Link Title
      url: http://example.com            
video: ''
screenshots:
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png          
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png  
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png   
...
Integration testing ensures that each individual API and collection paths comply with the integration that was put for with each version. Potentially using the OpenAPI for an API to generate tests, or generate collections that can be used to define specific business objectives or business scenarios. JSON Schema provides the details of the integration, and when applied as part of an OpenAPI definition, you end up with a machine readable integration that can be manually or automatically tested against, ensuring that each API doesn't change over time. It is common for collections to be define for the integration tests for each API, and then have these contracts tests scheduled for regular run via a monitor, as well as included as part of CI/CD pipelines. Providing robust coverage for integration tests that developers can manually run, or automate as required as part of the API lifecycle.