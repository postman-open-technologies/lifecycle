---
name: Mock Server
description: 
  - A mock server helps replicate as much of the functionality and API would have in production, before the time to actually have to write any code, making APIs be more tangible and real early on in the lifecycle, allowing teams to rapidly design an API that meets the needs of everyone involved, providing usable elements that power design, documentation, testing, and other elements of the API lifecycle.
links:
    - title: Setting up mock servers
      url: https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/
    - title: Configuring mock details
      url: https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/#configuring-mock-details
    - title: Making requests to mocks
      url: https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/#making-requests-to-mocks     
    - title: Viewing mock calls
      url: https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/#viewing-mock-calls   
    - title: Troubleshooting mock calls
      url: https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/#troubleshooting-mock-calls                           
video: '<iframe width="560" height="315" src="https://www.youtube.com/embed/n_7UUghLpco" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'
screenshots:
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png          
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png  
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png   
...
Mock servers provide a simulated reflection of what each API can do, mocking each path request, as well as the response. It is difficult to mock every feature of an API, but mock servers will get you about 75% of the way towards what you will experience in production. An easy to use mock server will help your team get hands on with what an API does, while also allowing them to quickly iterate upon the design and provide feedback without actually having to write code. Mock servers can be defined by generating Postman collections from OpenAPI definitions, and it even can make sense to have multiple mock servers tailored for specific business use cases or outcomes, providing usable representations of the value that an API will deliver in production. Mock servers can be made publicly available or restricted by API key, helping reduce friction for usage, while also potentially limiting who has access to mocked instances of an API.
