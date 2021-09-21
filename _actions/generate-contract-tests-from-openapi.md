---
name: Generate Contract Tests from OpenAPI
description: OpenAPI allows for the automation of contract tests for each API, helping increase the coverage for contract tests without much more work.
links:
    - title: Link Title
      url: http://example.com
    - title: Link Title
      url: http://example.com
    - title: Link Title
      url: http://example.com            
video: '<iframe width="560" height="315" src="https://www.youtube.com/embed/fzN67jPLpqI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'
tools:
    - title: Postman Contract Test Generator
      description: Postman collection and environment that will take an Open API Spec, validate component adherence, generate contract tests, and execute them.
      url: https://github.com/allenheltondev/postman-contract-test-generator      
issue: https://github.com/postman-open-technologies/lifecycle/issues/53
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_actions/generate-contract-tests-from-openapi.md      
...
You can generate a collection for testing purposes using an OpenAPI in the Postman platform today, but you then have to create your own test scripts. Until this capability is supported natively within the Postman platform there are community options for automating the generation of contract tests from OpenAPI. You can find an open source solution for generating postman collections that include contract tests from Allen Helton of Tyler Techologies, and a video of him talking through is approach from Postman Galaxy. Showing one possible way that you can automate how you test the contracts of your APIs consistently across all of your API operations.