---
name: Key
description: 
  - API keys provide the simplest form of access to an API, allowing consumers to sign up for an account, define what their application is, and then receive a key they can include in headers or other parameter to identify themselves, ensuring that API producers are fully aware of everyone who has access to an API, and all consumers have a way to clearly identify themselves and receive personalized usage data for each key. 
links:
    - title: Securely Using API Keys in Postman
      url: https://blog.postman.com/how-to-use-api-keys/
    - title: Generating a Postman API key
      url: https://learning.postman.com/docs/developer/intro-api/#generating-a-postman-api-key
    - title: Link Title
      url: http://example.com            
video: '<iframe width="560" height="315" src="https://www.youtube.com/embed/7F3f4WOFs38" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'
screenshots:
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png          
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png  
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png   
...
It is common practice to require API consumers to obtain an API key before they can access any API. While there are exceptions to this rule, most APIs require developers to register an application, select a usage plan, then are issued a key that is required to accompany every API call. API keys are a ubiquitous aspect of API consumption, and an essential part of the API lifecycle for API producers. Keys are managed via the gateway and management layer for APIs, and should be considered as part of both the producer and consumer side of the lifecycle, when it comes to issuing, managing, and then applying keys across many different environments. Standardizing how environment variables are used to apply keys across many different collections used to document, mock, test, and provide clients for APIs.
