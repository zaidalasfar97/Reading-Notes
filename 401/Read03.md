# Name 3 real world use cases where you’d want to change the request with custom middleware

##### 1-Error handling
##### 2-Authentication
##### 3-Data management

# True or false: The route handler is middleware?
##### False.

# In what ways can a middleware function end the process and send data to the browser?
##### Middleware functions are functions that have access to the request object (req), the response object (res), and the next function in the application’s request-response cycle. The next function is a function in the Express router which, when invoked, executes the middleware succeeding the current middleware.

# At what point in the request lifecycle can you “inject” middleware?
##### Before the main middleware that should send the response to the client.
 
# What can cause express to error with “Request headers sent twice, cannot start a second response” 
##### The error "Error: Can't set headers after they are sent." means that you're already in the Body or Finished state, but some function tried to set a header or statusCode. When you see this error, try to look for anything that tries to send a header after some of the body has already been written. For example, look for callbacks that are accidentally called twice, or any error that happens after the body is sent.

# Terms : 
## Middleware
#### Any functionality that sits in between request/response, but does not send out response itself.
## Request Object
#### Represents the information in the HTTP request from the client to the server.
## Response Object
#### Information in the HTTP response from the server to the client.
## Application Middleware
#### Middleware that plays a role in the function of the application.

## Routing Middleware Middleware
#### that plays a role in path routing.

## TDD 
#### Style of programming in which three activities are tightly interwoven - coding, testing (unit tests), and design.

## Behavioral Testing 
#### Testing of the external behavior of the program (also known as black-box testing), usually a functional testing

# ES6 Classes :
#### Classes are a template for creating objects. They encapsulate data with code to work on that data. Classes in JS are built on prototypes but also have some syntax and semantics that are not shared with ES5 class-like semantics.


# Using Express Routing :
#### refers to how an application’s endpoints (URIs) respond to client requests.
#### You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests. For a full list, see app.METHOD. You can also use app.all() to handle all HTTP methods and app.use() to specify middleware as the callback function (See Using middleware for details).

# Express Routing: 
#### Express 4.0 comes with the new Router. Router is like a mini express application. It doesn't bring in views or settings, but provides us with the routing APIs like .use, .get, .param, and route.