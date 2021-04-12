# What does it mean that web sockets are bidirectional? Why is this useful?
###### Whereas HTTP relies on a client request to receive a response from the server for every exchange, WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.

# Does socket.io use HTTP? Why?
###### Yes , a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js .

# What happens when a client emits an event?
###### The event will be send to the server which will listening to event.

# What happens when a server emits an event?
###### When a click event happens, run the callback function. Inside the callback function, have socket emit this "chat" event to the server. 

# What happens if a client “misses” an event?
###### Ignore the event .

# Terms :

### Socket:
###### Is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to. An endpoint is a combination of an IP address and a port number.

### Web Socket :
###### is an advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server. With this API, you can send messages to a server and receive event-driven responses without having to poll the server for a reply.
### Socket.io:
######  enables real-time bidirectional event-based communication.
### Client :
###### program separate from the server that initiates requests for services or info from the server .
### Server :
###### is a computer that provides data to other computers. It may serve data to systems on a local area network (LAN) or a wide area network (WAN) over the Internet. Many types of servers exist, including web servers, mail servers, and file servers. Each type runs software specific to the purpose of the server.
### OSI Model :
###### (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system. The OSI model characterizes computing functions into a universal set of rules and requirements in order to support interoperability between different products and software.
### TCP Model:
###### transmission control protocol, essentially a concise version of the OSI model.
### Packets:
###### Formatted unit of data carried by a packet-switched network, packet consists of control information and user data/payload.

# Socket.io Chat Example :
###### Writing a chat application with popular web applications stacks like LAMP (PHP) has normally been very hard. It involves polling the server for changes, keeping track of timestamps, and it’s a lot slower than it should be.

###### Sockets have traditionally been the solution around which most real-time chat systems are architected, providing a bi-directional communication channel between a client and a server.

###### This means that the server can push messages to clients. Whenever you write a chat message, the idea is that the server will get it and push it to all other connected clients.

# Rooms and Namespaces :
##### A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients.