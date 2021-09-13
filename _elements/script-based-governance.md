---
name: Script-Based Governance
description: 
  - A script-based approach to governance involves using the same collection based approach used to apply contract, performance, and other types of testing with Postman collections, but instead of testing an instance of an API, you are testing the surface area of the API by pulling the OpenAPI and writing test scripts for specific governance assertions.
links:
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
A script-based approach to applying governance to any OpenAPI or AsyncAPI is the flexible approach to governance allowing for almost any type of assertion or desired outcome, but will require custom scripting to define each governance assertion. The OpenAPI or AsyncAPI for an API can be pulled via a URL or the Postman API, and then test scripts can be written to traverse and apply a variety of custom assertions, looking for problems in the design of each API. As with other API testing, the test results pane or visualizer can be used to report on the findings, alerting the developer that something is wrong with the design and what needs to be fixed, or throw an error to trigger the failure of a pipeline at build time. A script-based approach to governance will provide the widest flexibility, but require the most investment to develop the scripts needed to enforce governance across known API artifacts.