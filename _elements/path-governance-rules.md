---
name: Path Governance Rules
description: 
  - Rules can be defined to govern the paths provided for each API, leveraging the path object for OpenAPI or AsyncAPI contracts, but then apply specific ruling looking for common patterns to be present like words used, ensure no acronyms exist in the path, meeting specific guidelines regarding what a path can contain.
links:
    - title: Path Spectral Rulesets
      url: https://rules.linting.org/#rulesets-paths  
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
Path governance rules provide a base of YAML or JSON rules that can be applied to the path object within OpenAPI or AsyncAPI contracts, checking for specific patterns for words used to describe a path, restricting acronyms, enforcing unique ids, and other elements of an API. Rules can be defined centrally by governance leadership, or locally within teams, and then applied either at design, develop, or build time in a manual or automated way depending on the objectives of team, department, organization, or industry-wide governance.