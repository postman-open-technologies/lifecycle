---
name: Response Governance Rules
description: 
  - Rules can be defined to govern the response details provided for each API, leveraging the response object for OpenAPI or AsyncAPI contracts, but then apply specific ruling looking for common patterns to be present like the status code, media type, and other details of an API, meeting specific guidelines regarding what responses should look like.
links:
    - title: Response Spectral Rulesets
      url: https://rules.linting.org/#rulesets-responses
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
Response governance rules provide a base of YAML or JSON rules that can be applied to the response object within OpenAPI or AsyncAPI contracts, checking for specific patterns like the status code, media type, and other elements of an API. Rules can be defined centrally by governance leadership, or locally within teams, and then applied either at design, develop, or build time in a manual or automated way depending on the objectives of team, department, organization, or industry-wide governance.