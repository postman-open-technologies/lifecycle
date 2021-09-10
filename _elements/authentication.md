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
Authentication begins on the producer side by selecting the appropriate authentication method to use when deploying an API to the gateway, setting the tone for how identity, authentication, and access control will work across the API lifecycle. Next, authentication can be defined as part of API consumption at the collection, folder, or individual request level, providing a very configurable authentication layer for automating across API operations. Authentication works seamlessly with environments, allowing secrets and tokens to be abstracted away to environments, but then applied to collections as part of specific authentication configuration using variables. Providing a very flexible and practical approach to applying authentication across many different APIs across many different teams in a manual or automated way.