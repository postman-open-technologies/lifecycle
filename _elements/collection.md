---
name: Collection
description: 
  - A machine readable artifact that acts as a container for storing and organizing multiple API requests, providing an executable, self-documented reference for a complete API, a subset of an API, as well as workflows containing multiple requests from across many different APIs in a specific order, with a precise business function. 
links:
    - title: Stay Organized with Postman Collections
      url: https://www.postman.com/collection/
    - title: Collection SDK
      url: https://learning.postman.com/docs/developer/collection-sdk/
    - title: Creating your first collection
      url: https://learning.postman.com/docs/getting-started/creating-the-first-collection/ 
    - title: Using the Collection Runner
      url: https://learning.postman.com/docs/running-collections/intro-to-collection-runs/             
video: '<iframe width="560" height="315" src="https://www.youtube.com/embed/QKxukXJWRPI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'
actions:
  - name: Import Collection
  - name: Generate Collection from OpenAPI
  - name: Generate OpenAPI from Collection
  - name: Sync Collection to Github
  - name: Watch Collection  
  - name: Fork Collection   
  - name: Comment on Collection 
screenshots:
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png          
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png  
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png     
elements:
  - name: Request
    label: Request   
    context: 0  
  - name: Authentication
    label: Authentication  
    context: 0   
  - name: Scripts
    label: Scripts       
    context: 0         
...
Postman collections are a fundamental executable unit of value describing an API or collection of APIs intended to accomplish a specific business purposes. Collections resemble OpenAPI often times in how they are used, but diverge when it comes to being able to derive different documentation, mocks, tests, and complete or subsets of an API, providing a machine readable representation, but also one that can be executed as part of different lifecycle processes. Collections can contain many different API requests that can be organized by folders, possessing all the technical details of each API request, but also contains authorization, scripts, and other useful elements. Collections are the heartbeat of the Postman API platform, and begin with helping save requests defined while using Postman as an API client, but can also be applied to almost every stop along the API lifecycle when producing APIs, and speed up integration and automation for API consumers. Collections are extremely versatile, and represent a low-code vision of what is possible when it comes to working with APIs.