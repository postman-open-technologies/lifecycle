---
name: Resolvers
description: 
  - The bindings that map incoming queries to specific data sources so that APIs know where to find resources, distilling down API requests into meaningful queries that will make sense to backend systems, connecting the front end requests to the backend stores, routing API requests to where they need to go.
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
Resolver is a collection of functions that generate response for a GraphQL query. In simple terms, a resolver acts as a GraphQL query handler. Every resolver function in a GraphQL schema accepts four positional arguments. A resolver is a function that's responsible for populating the data for a single field in your schema. It can populate that data in any way you define, such as by fetching data from a back-end database or a third-party API. Providing the essential mapping needed to handle the requests coming in via a GraphQL, make the round trip to some backend system to retrieve the data, and then return the data in the desired format as defined by the API consumers query.