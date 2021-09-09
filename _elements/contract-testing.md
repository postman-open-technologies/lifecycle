---
name: Contract Testing
description: 
  - Contract tests can be derived from API artifacts like OpenAPI, JSON Schema, and GraphQL, and used to ensure there are no changes to what has been promised when an API was designed or developed, providing a repeatable test that can be run manually, on a schedule from multiple regions, or as part of a CI/CD pipeline to ensure contracts with consumers are upheld. 
links:
    - title: Consumer-driven Contract Testing using Postman
      url: https://medium.com/better-practices/consumer-driven-contract-testing-using-postman-f3580dba5370         
video: '<iframe width="560" height="315" src="https://www.youtube.com/embed/Ynfr-y_1WRs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'
screenshots:
  - title: Contract Testing
    url: images/elements/contract-testing-1.png 
elements:
  - name: Contract Testing Monitor
    label: Contract Testing Monitor   
    context: 0     
  - name: Contract Testing Monitor Results
    label: Contract Testing Monitor Results   
    context: 0   
  - name: Contract Testing Monitor Report
    label: Contract Testing Monitor Report   
    context: 0           
...
Contract testing ensures that each individual API and collection paths comply with the contract that was put for with each version. Potentially using the OpenAPI for an API to generate tests, or generate collections that can be used to define specific business objectives or business scenarios. JSON Schema provides the details of the contract, and when applied as part of an OpenAPI definition, you end up with a machine readable contract that can be manually or automatically tested against, ensuring that each API doesn't change over time. It is common for collections to be define for the contract tests for each API, and then have these contracts tests scheduled for regular run via a monitor, as well as included as part of CI/CD pipelines. Providing robust coverage for contract tests that developers can manually run, or automate as required as part of the API lifecycle.