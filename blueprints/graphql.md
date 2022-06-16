# GraphQL
GraphQL provides the ability to apply queries, mutations, and subscriptions defined within a query language to synchronous and asynchronous APIs. Adding another type of contract to our API toolbox for providing a very flexible query language for front-end developers to use when getting the data they need.

- **Operations** - The document which contains the types of operations: query, mutation, and subscription along with any fragments, describing what is possible wiith the API.
- **Document** - GraphQL has two types of documents: execution documents and schema documents, shaping what tpes of queries are possible, and how consumers can use.
- **Selection Sets** - With an execution document a set of fields that make up the content contained within curly braces, describing the desired fields associated with a query.
- **Fields** - And object-specific attribute that can be requested and returns a value, providing the atomic unit of any combination of data that is made available via API.
- **Fragments** - There are three types of fragments: named fragments allow us to reuse fields, type conditions allow us to conditionally select fields and inline fragments that don't have a name defined inside the selection set.
- **Directives** - There are four directives defined in the spec: @skip, @include, @specifiedBy and @deprecated, chnaging how a section of the document is executed.
- **Mutations** - Different types of operations that can be made, enabling different state changes when it comes to data, providing the ability to read, update, and other states.
- **Subscriptions** - These are long-lived requests that allow the server to send the client events as they happen, allowing consumers to be subscribed to the data they need.

GraphQL is an optimal solution when you have large volumes of data with a wide surface area, and you have a known set of developers who are familiar with GraphQL, the schema, and are building a variety of applications that have specialized needs around specific domains of data.
