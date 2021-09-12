---
name: Linting
description: 
  - Validating an API schema against a known set of constraints, ensuring that all artifacts in use across API operations are well defined and match known and intended schema for use as part of requests, responses, and the messages being sent, published, and subscribed to across API operations. 
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
The linting of API contracts, requests, responses, and other artifacts is a regular part of the API lifecycle. JSON Schema provides a machine readable way for developers to annotate JSON documents, providing a machine readable definition that can be used to validate almost any part of API operations. Linting is central to the design process, and is how API testing and governance is realized across API operations. Linting is baked into the Postman API platform as part of API builder, test scripts, and can be applied in CI/CD pipelines to help automate the linting of artifacts as part of the build process.