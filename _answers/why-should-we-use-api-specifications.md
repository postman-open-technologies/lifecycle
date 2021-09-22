---
name: Why Should We Use API Specifications?
description: API specifications like OpenAPI, AsyncAPI, and JSON Schema provide us with a shared vocabulary for describing the surface area of our APIs in exact and machine-readable ways.
links:
    - title: OpenAPI
      url: https://openapis.org/
    - title: AsyncAPI
      url: https://www.asyncapi.com/
    - title: JSON Schema
      url: https://json-schema.org/          
video: '<iframe width="560" height="315" src="https://www.youtube.com/embed/XX9QeeQTNPE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'     
...
OpenAPI, AsyncAPI, and JSON Schema give us a human and machine-readable way to describe the surface area of our APIs. OpenAPI allows us to describe the details of synchronous, request, and response APIs, using JSON Schema to define what should be submitted and what a user can expect back as a response. AsyncAPI does the same thing but focuses on the more asynchronous event and message-driven APIs, describing the channels and other details, while also using JSON Schema to describe the objects being published and subscribed to each channel. API specifications describe the surface area of our APIs so that we can:

- **Document** - Generate human readable HTML documentation for each API.
- **Mock** - Generate static mock servers that emulate what an API can do.
- **Test** - Generate contract, performance, and other types of API tests.
- **Generate Code** - Generate code in a variety of programming languages.

These are just a handful of the most common reasons API providers use API specifications. However, in addition to these API lifecycle benefits, API specifications provide us with a standard, widely understood way to describe the surface area of our APIs in a way that other developers will understand. API specifications help make how we communicate and collaborate around an API across the API lifecycle, helping increase team velocity when producing and consuming APIs. These API specifications are used by top API providers like eBay, Salesforce, Github, Twitter, and others to describe their APIs so that they can document, mock, test, and generate code across their API operations.