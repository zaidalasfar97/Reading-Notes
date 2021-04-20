# What’s the difference between a FIFO and a standard queue?
##### FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers.

# How can the server be assured a message was properly received?
##### Client sends a request to server, Server receives a request ,Server sends a response ,Client receives a response

# What classic design pattern is best represented by event driven programming?
##### The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods. It is mainly used for implementing distributed event handlingsystems, in "event driven" software.

# How do you test an event driven system?



# Term :
### Serverless API:Serverless is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers
### Triggers:The specified event and the default behavior of an event (like form submission) for the selected elements. This method is similar to the triggerHandler() method, except that triggerHandler() does not trigger the default behavior of the event.
### Dynamo vs Mongo:DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas. ... DynamoDB uses tables, items and attributes, MongoDB uses JSON-like documents. DynamoDB supports limited data types and smaller item sizes; MongoDB supports more data types and has fewer size restrictions.



# SNS :
### Amazon Simple Notification Service (Amazon SNS) is a web service that enables you to build distributed web-enabled applications. Applications can use Amazon SNS to easily push real-time notification messages to interested subscribers over multiple delivery protocols.

# SQS :
### Amazon Simple Queue Service (Amazon SQS) is a reliable, highly-scalable hosted queue for storing messages as they travel between applications or microservices. Amazon SQS moves data between distributed application components and helps you decouple these components.

### You can use AWS SDKs to access Amazon SQS using your favorite programming language. The SDKs perform tasks such as the following automatically:

#### Cryptographically sign your service requests
#### Retry requests
#### Handle error responses