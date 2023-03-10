# Rest Full API
## What is Rest Full API

REST is an acronym for REpresentational State Transfer and an architectural style for distributed hypermedia systems. Roy Fielding first presented it in 2000 in his famous dissertation.
 # Guiding Principles of REST
 
 1. Uniform Interface: This principle involves defining a uniform interface for communication between the client and server. The interface should be simple and consistent across all resources. It should also provide the ability to manipulate resources through representations, with metadata to describe the resource.
 
 2. Client-Server Architecture: This principle involves separating the client and server components, allowing them to evolve independently. The client sends requests to the server, and the server returns responses to the client.

 3. Statelessness: In REST, the server does not store any client context between requests. Each request from the client must contain all the necessary   information required to understand the request, meaning that each request is independent of any previous requests.

 4. Cacheability: Caching improves network efficiency and reduces server load by allowing clients to cache responses. The server must indicate which responses are cacheable, and the client must enforce cache validation.

 5. Layered System: The layered system principle involves creating a hierarchy of layers, with each layer responsible for a specific function. Each layer can only interact with the layer directly below it and has no knowledge of other layers. This principle improves scalability and simplifies implementation.

 6. Code-On-Demand (Optional): This principle allows for server-side scripts to be sent to the client and executed on demand. This feature is optional, and not all RESTful architectures implement it. It is mostly used in web applications that require complex processing on the client side.

 Following these guiding principles can help ensure that a RESTful web service is scalable, easy to maintain, and interoperable with other web services.
 
# Advantage of  REST API


1.Scalability: REST API allows for a distributed architecture where the client and server components can be scaled independently. This means that each component can be scaled up or down based on the demand, allowing the application to handle a large number of users and requests.

2.Simplicity: REST API follows a simple and uniform interface for communication between the client and server, using HTTP methods such as GET, POST, PUT, DELETE. This makes it easy for developers to understand and implement, reducing the time and effort required to develop and maintain the API.

3.Flexibility: REST API can be used to communicate with any type of system, including mobile devices, web browsers, and other servers. It is also language and platform-independent, which means that it can be used with any programming language or platform.

4.Cacheability: REST API supports caching, which reduces network traffic and improves performance by allowing clients to cache responses. This reduces the load on the server and improves the overall performance of the application.

5.Security: REST API provides several security mechanisms such as HTTPS, OAuth, and SSL/TLS, which ensure that the data exchanged between the client and server is secure and confidential.

6.Cost-Effective: REST API can be implemented at a lower cost than other API architectures because it requires less overhead, infrastructure, and maintenance.

Overall, REST API provides a simple, flexible, and scalable architecture that can be used to develop a wide range of applications, making it a popular choice among developers.
