---
name: Authentication
version: 2021-09-21
description: 
  - The consistent application of standard authentication as part of a standardized API management layer striking a balance between access to digital resources but ensuring that undesirable actors do not have access to valuable assets.
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
Authentication begins on the producer side by selecting the appropriate authentication method when deploying an API to the gateway, setting the tone for how identity, authentication, and access control will work across the API lifecycle. Next, authentication can be defined as part of API consumption at the collection, folder, or individual request level, providing a configurable authentication layer for automating across API operations. Authentication should be balanced across both the producer and consumer side of the API lifecycle, putting well-known practices to work, allowing both sides to securely access, refresh, and engage with necessary authentication.
