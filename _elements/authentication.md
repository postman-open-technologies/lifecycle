---
name: Authentication
description: 
  - The usage of known standards for authentication across all APIs as part of the API management layer helps reduce friction for developers onboarding while applying the right level of security and access control to ensure that APIs are accessible by consumers, but then out of reach of unwanted actors, and are visible via reporting and dashboards that leverage API management observability. 
links:
    - title: Authorizing Requests
      url: https://learning.postman.com/docs/sending-requests/authorization/
    - title: Specifying authorization details
      url: https://learning.postman.com/docs/sending-requests/authorization/#specifying-authorization-details         
    - title: Syncing Cookies
      url: https://learning.postman.com/docs/sending-requests/authorization/#syncing-cookies        
video: ''
screenshots:
  - title: Specifying Authorization Details
    url: images/elements/authentication-1.jpg        
  - title: Applying Variables for Secrets
    url: images/elements/authentication-2.jpeg  
  - title: Collection Level Authorization
    url: images/elements/authentication-3.jpeg    
...
Authentication for a single, or many different APIs are a native part of a collection, and can be defined at the collection, folder, or individual request level, providing a very configurable authentication layer for automating across API operations. Postman supports API keys, bearer token, basic auth, digest auth, OAuth 1.0 & 2.0, Hawk Authentication, AWS Signature, and Akamai EdgeGrid when it comes to making API requests. Authentication works seamlessly with environments, allowing secrets and tokens to be abstracted away to environments, but then applied to collections as part of specific authentication configuration using variables. Providing a very flexible and practical approach to applying authentication across many different APIs across many different teams in a manual or automated way.