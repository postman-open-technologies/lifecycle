# GraphQL
GraphQL provides the ability to apply queries, mutations, and subscriptions defined within a query language to synchronous and asynchronous APIs. Adding another type of contract to our API toolbox for providing a very flexible query language for front-end developers to use when getting the data they need.

- **Operations** - the document which contains the types of operations: query, mutation, and subscription along with any fragments.
- **Document** - GraphQL has two types of documents: execution (query) documents and schema documents (which will be discussed in a future post)
- **Selection Sets** - With an execution document a set of fields that make up the content contained within curly braces.
- **Fields** - And object-specific attribute that can be requested and returns a value.
- **Arguments** - Are named values that are provided to its field function and change how it behaves.
- **Variables** - Are declared after the operation name, for example,
- **Field Aliases** - Changes the name of a field that was declared on the server in the retuned response.
- **Fragments** - There are three types of fragments: named fragments allow us to reuse fields, type conditions allow us to conditionally select fields and inline fragments that don't have a name defined inside the selection set.
- **Directives** - There are four directives defined in the spec: @skip, @include, @specifiedBy and @deprecated. All directives begin with the @ symbol and change how a section of the document is validated or executed by the server. Custom directives are allowed and frequently used.
- **Mutations** - Technically “mutation” is an operation type, but top-level mutation fields are often called “mutations.” Mutations alter data.
- **Subscriptions** - These are long-lived requests that allow the server to send the client events as they happen.
