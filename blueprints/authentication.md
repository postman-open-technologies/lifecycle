## Authentication 
Almost all APIs require authentication, providing a standardized way for API consumers to identify themselves and obtain access to digital resources and capabilities being made available via APIs, helping API producers protect their digital resources, while still opening up access to intended users. 

### Types 
The types of authentication. 

- **Keys** - API keys provide the simplest form of access to an API, allowing consumers to sign up for an account, define what their application is, and then receive a key they can include in headers or other parameters to identify themselves, ensuring that API producers are fully aware of everyone who has access to an API, and all consumers have a way to clearly identify themselves and receive personalized usage data for each key. 
- **Basic Authentication** - A simple form of HTTP authentication is all an app or service requires, HTTP basic authentication might be a good fit. It uses a locally derived username and password and relies on Base64 encoding. Authentication uses the HTTP header, making it easy to integrate.  
- **OAuth 1.0** - OAuth 1.0 enables client applications to access data provided by a third-party API. For example, as a user of a service, you can grant another application access to your data with that service without exposing details like your username and password. Accessing user data with OAuth 1.0 involves a few requests back and forth between client application, user, and service provider. 
- **OAuth 2.0** - With OAuth 2.0, you first retrieve an access token for the API, then use that token to authenticate future requests. Accessing data with OAuth 2.0 varies greatly between API service providers, but typically involves a few requests back and forth between client application, user, and API. 
- **Bearer Token** - Bearer tokens enable requests to authenticate using an access key, such as a JSON Web Token (JWT). The token is a text string, included in the request header. In the request Authorization tab, select Bearer Token from the Type dropdown list. In the Token field, enter your API key value. For added security, store it in a variable and reference the variable by name. 
 
 
