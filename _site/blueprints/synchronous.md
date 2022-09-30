# Synchronous
The web is created by the ability to request HTML pages via URLs and receive a response that hopefully contains what we are looking for. It was a low-cost approach that has been applied to the ability to synchronously GET, POST, PUT, or DELETE digital resources and capabilities via the Internet. 

## Request

- **Authentication** - Requiring everyone making a request to provide authentication, ensuring that everyone who is using an API is supposed to be using it, keeping everything secure.
- **Parameters** - Allowing each request to be customized by providing a set of parameters along with each request, transforming the response the API consumer is looking to get.
- **Headers** - Defining and shaping the transport of the the request by setting the headers of the request which is used by the network and the server to handle the request nd response.
- **Body** - The machine readable XML or JSON request body being send as part of the request, providing the information being submitted by the consumer as part of each request.

## Response

- **Status Code** - Providing standards HTTP status codes that articulate the success or failure of a request in a way that any machine can be programmed to understand when handling.
- **Headers** - The headers of the request, defining how the transport and shaping of the request was handled, allowing for the receiving system to understand how it arrived.
- **Body** - The response data or message being returned as part of the API request, returning JSON or XML that can be used in any application or integration that is using the API.

