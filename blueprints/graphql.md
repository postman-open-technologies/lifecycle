## GraphQL 
GraphQL provides the ability to apply queries, mutations, and subscriptions defined within a query language to synchronous and asynchronous APIs. GraphQL adds another type of contract to our API toolbox, allowing us to offer a very flexible query language enabling developers to get the data they need to use in any application.
In conversations, I have found enterprise organizations using GraphQL to support their mobile and single-page applications. I also see them deploying an internal graph to abstract many different APIs and data sources into a single layer of the enterprise that developers can query and work with. 

### Elements 
 

- **Operations** - You have a document describing various types of operations, such as queries, mutations, subscriptions, and any fragments, that define what is possible with the API. 
- **Document** - GraphQL has two types of documents: execution documents and schema documents. They determine what types of queries are possible and how consumers can use them. 
- **Selection Sets** - Located within an execution document, selection sets are sets of fields that make up the content contained within curly braces, describing the desired fields associated with a query. 
- **Fields** - ields are object-specific attributes that can be requested and return a value, providing the atomic unit of any combination of data made available via an API. 
- **Fragments** - here are three types of fragments. Named fragments allow us to reuse fields, Type conditions allow us to conditionally select fields, and Inline fragments don’t have a name defined inside the selection set. 
- **Directives** - There are four directives defined in the spec: @skip, @include, @specifiedby and @deprecated. They change the way a section of the document is executed. 
- **Mutations** - ifferent types of operations enable different state changes for data, providing the ability to read, update, and achieve other states. 
- **Subscriptions** - hese are long-lived requests that allow the server to send the client events as they happen, allowing consumers to subscribe to the data they need. 
 
GraphQL is an optimal solution when you have a large amount of data with a wide surface area and developers familiar with GraphQLwho are building a variety of applications with specialized needs for specific domains of data. GraphQL provides you with a powerful API layer for your distributed enterprise landscape, augmenting your RESTful and other types of APIs. That helps you stitch together all data in a meaningful API layer. 
