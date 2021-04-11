# What is the benefit of transforming data into packets? 
##### Packet switching is used to optimize the use of the channel capacity available in digital telecommunication networks, such as computer networks, and minimize the transmission latency (the time it takes for data to pass across the network), and to increase robustness of communication .

# UDP is often refereed to as a connectionless protocol. Why is this?
##### No connection needs to be established between the source and destination before you transmit data. UDP does not have a mechanism to make sure that the payload is not corrupted.

# Can a socket server application have multiple socket connections?

##### A server socket listens on a single port. ... Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to.

# Can a socket connection application be connected to multiple socket servers?
##### A server socket listens on a single port. ... Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to.

# Can an application be both a socket server and a socket connection?
##### However it is possible, and not unusual, to process both input and output streams of a socket on the same thread and supporting a single connection at a time allows the Runnable requirement to be dropped .

# Terms : 

# Observer Pattern :
##### The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

# Event Handler: 
##### Any function or object that is registered to be notified of events. Or more specifically, to the mechanism of registering event listeners via on… attributes in HTML or properties in Web APIs.

# Event Driven Programming: 
##### is when a program is designed to respond to user engagement in various forms. It is known as a programming paradigm in which the flow of program execution is determined by “events.” Events are any user interaction, such as a click or key press, in response to prompt from the system.

# Event Loop:
##### which is responsible for executing the code, collecting and processing events, and executing queued sub-tasks.

# Event Queue: 
##### Is a repository where events from an application are held prior to being processed by a receiving program or system.

# Call Stack:
##### Is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions.

# Database :
##### A database is a collection of information that is organized so that it can be easily accessed, managed and updated. 

# What Socket.IO :
#### Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server.

## How does that work?
#### The client will try to establish a WebSocket connection if possible, and will fall back on HTTP long polling if not.WebSocket is a communication protocol which provides a full-duplex and low-latency channel between the server and the browser.

