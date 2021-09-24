---
name: Development Environments
description: 
  - Machine readable environments for APIs allow for abstracting away common elements of a API development environment from the definition of each API, allowing different environments to be paired with collections for each API at design, develop, and build time.
links:
    - title: Managing environments
      url: https://learning.postman.com/docs/sending-requests/managing-environments/
    - title: Adding Environment Variables
      url: https://learning.postman.com/docs/sending-requests/managing-environments/#adding-environment-variables
    - title: Accessing Environments
      url: https://learning.postman.com/docs/sending-requests/managing-environments/#accessing-environments 
    - title: Working with Environments as a Team
      url: https://learning.postman.com/docs/sending-requests/managing-environments/#accessing-environments  
    - title: Managing Environment Roles
      url: https://learning.postman.com/docs/sending-requests/managing-environments/#accessing-environments                   
video: ''
screenshots:
  - title: Screenshot Description
    url: images/elements/environment-1.jpeg
...
A development environment is a set of variables you can use in your Postman requests. You can use environments to group related sets of values together for use across individual, or many different collections. Environments help you abstract away secrets, tokens, and other data that you will need to use across different collections while working with different APIs. You can think of environments as a mini key-value store that you can apply to collections, but then also store data pulled from collection runs, persisting data across many different API requests. It is common for collection run results to be stored within environments, paginated data, and other results from API workflows and automation, making environments a pretty robust way to persist valuable data across API consumption.

