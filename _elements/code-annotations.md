---
name: Code Annotations
description: 
  - Language specific code annotations can be used to generate OpenAPI definitions for APIs in a variety of programming languages, allowing developers to provide the necessary information to create an APi contract from within their natural development environment, embracing a code-first approach to the API lifecycle while still ensuring there is an OpenAPI to be used for the rest of the lifecycle.
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
elements:
  - name: Client Snippets
    label: Client Snippets   
    context: 0    
  - name: Client SDKs
    label: Client SDKs   
    context: 0     
  - name: Code Annotations
    label: Code Annotations   
    context: 0     
...
Code annotations are a common way to generate API specifications from code. Relying on developers to deliver an API using traditional software development processes, but then annotating each method to define the inputs and outputs that would correspond to the API request and response each method delivers. Code annotations can be used to generate OpenAPI, collections, and other machine readable artifacts that can then be used to produce documentation, tests, and other elements of the API lifecycle. Many organizations rely on developers to produce each version of an API, and then automate the generation of documentation, tests, and other elements from the annotation, reducing the role of the developer in having to learn and understand API specification formats and change their existing behavior beyond just annotating each portion of the code they are responsible for within their IDE.