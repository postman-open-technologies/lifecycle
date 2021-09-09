---
name: Data Sources
description: 
  - Providing the sources of where an API retrieves it's data, mapping the API to backend databases that contain the actual resources that will be made available via each API, allowing each API to be able to find data as requests are made by consumers.
body:
  - 'At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.'
footer:
  - ''  
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
APIs provide managed programmatic access to potentially a variety of data sources, with a variety of gateway solutions for connecting, resolving, applying business logic, and transforming data from data sources as it is being made available via APIs. While it is common for API developers to directly expose data sources as create, read, update, and delete (CRUD) APIs, it is much more desirable to expose data sources as well designed API paths, as well as via GraphQL and other query languages. Data sources and APIs have a natural relationship as part of the development and delivery of APIs, but there are a variety of approaches you can take to connect data sources via your APIs.