# What’s the difference between PUT and PATCH?
###### The main difference between PUT and PATCH requests is witnessed in the way the server processes the enclosed entity to update the resource identified by the Request-URI. When making a PUT request, the enclosed entity is viewed as the modified version of the resource saved on the original server, and the client is requesting to replace it. However, with PATCH, the enclosed entity boasts a set of instructions that describe how a resource stored on the original server should be partially modified to create a new version.

###### The second difference is when it comes to idempotency. HTTP PUT is said to be idempotent since it always yields the same results every after making several requests. On the other hand, HTTP PATCH is basically said to be non-idempotent. However, it can be made to be idempotent based on where it is implemented.


# Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
###### 1-https://www.mock-server.com/
###### 2-https://beeceptor.com/
###### 3-https://mockoon.com/







# Compare and contrast SOAP and REST:

###### SOAP and REST both allow you to create your own API. API stands for Application Programming Interface. It makes it possible to transfer data from an application to other applications. An API receives requests and sends back responses through internet protocols such as HTTP, SMTP, and others.

###### Many popular websites provide public APIs for their users, for example, Google Maps has a public REST API that lets you customize Google Maps with your own content. There are also many APIs that have been created by companies for internal use.

###### SOAP and REST are two API styles that approach the question of data transmission from a different point of view.


# web server:
###### a remote computer or a computer program that delivers web pages to a user's computer, or a client, upon request from a web browser.

# Express: 
###### is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.

# Routing:
###### A Javascript router is a key component in most frontend frameworks. It is the piece of software in charge to organize the states of the application, switching between different views

# WRRC:
###### Web Response Request Cycle.