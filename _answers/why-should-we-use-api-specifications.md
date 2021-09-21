---
name: Why Should We Use API Specifications?
description: API specifications like OpenAPI, AsyncAPI, and JSON Schema provides us with a common vocabulary for describing the surface area of our APIs in very precise and machine readable ways.
links:
    - title: OpenAPI
      url: https://openapis.org/
    - title: AsyncAPI
      url: https://www.asyncapi.com/
    - title: JSON Schema
      url: https://json-schema.org/          
video: '<iframe width="560" height="315" src="https://www.youtube.com/embed/XX9QeeQTNPE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'     
...
OpenAPI, AsyncAPI, and JSON Schema give us a human and machine readable way to describe the surface area of our APIs. OpenAPI allows us to describe the details of synchronous, request and response APIs, using JSON Schema to describe the details of what should be submitted, and what a user can expect back as a response. AsyncAPI does the same thing, but focuses on more asynchronous event and message driven APIs, describing the channels and other details, while also using JSON Schema to describe the objects being published and subscribed to each channel. API specifications describe the surface area of our APIs so that we can:

- **Document** - Generate human readable HTML documentation for each API.
- **Mock** - Generate static mock servers that emulate what an API can do.
- **Test** - Generate contract, performance, and other types of API tests.
- **Generate Code** - Generate code in a variety of programming languages.

These are just a handful of the most common reasons why API providers are using API specifications. However, in addition to these API lifecycle benefits, API specification provide us with a common, widely understand way to describe the surface area of our APIs in a way that other developers will understand. API specifications help make how we communicate and collaborate around an API across the API lifecycle, helping increase team velocity when it comes to producing and consuming APIs. 