---
name: Import OpenAPI
description: OpenAPI files can be imported into Postman to create a new API, importing via upload, URL, repo, or pasting in the raw text of each OpenAPI.
links:
    - title: OpenAPI in Postman
      url: https://learning.postman.com/docs/integrations/available-integrations/working-with-openAPI/           
video: ''
screenshots:
  - title: Import OpenAPI
    url: /images/actions/import-openapi.png      
...
You can import your existing OAS 3.0 definitions (OpenAPI Specification) into Postman. Postman supports both YAML and JSON formats. You can choose to upload a file, enter a URL, or directly copy your JSON/YAML. In Postman, click 'Import' to bring up the following screen. When importing your OpenAPI specification, Postman follows the endpoint hierarchy defined in the specification to create a collection organized into folders (if your OpenAPI has multiple levels of hierarchy). Postman uses the schemas defined in the OpenAPI to generate request and response bodies. Allowing for the authoring of an existing OpenAPI within the Postman platform.