# Explain what a “Singleton” is (in Computer Science terms): 
#### A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. It is used in scenarios when a user wants to restrict instantiation of a class to only one object. This is helpful usually when a single object is required to coordinate actions across a system.

#### The singleton pattern is used in programming languages such as Java and .NET to define a global variable. A single object used across systems remains constant and needs to be defined only once rather than many times.

# Explain how the Singleton pattern can be used with Node modules, specifically with classes
##### Sometimes you need to make sure that you have one and only one instance of an object. This is where the singleton pattern can be useful. A singleton represents a single instance of an object. Only one can be created, no matter how many times the object is instantiated. If there’s already an instance, the singleton will create a new one. Let’s take a look at where creating multiple instances of one object might create problems within our application.

# If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
#### Access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.


# Router Middleware:
#### Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of express.Router(). Load router-level middleware by using the router.use() and router.METHOD() functions.

# Dynamic module loading:
#### A recent addition to JavaScript modules functionality is dynamic module loading. This allows you to dynamically load modules only when they are needed, rather than having to load everything up front.

# Singleton Pattern:
#### The singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.

# CRUD -> REST Method Matches:
#### CRUD (Create, Read, Update, Delete) is an acronym for ways one can operate on stored data. It is a mnemonic for the four basic functions of persistent storage.  CRUD typically refers to operations performed in a database or datastore, but it can also apply to higher level functions of an application such as soft deletes where data is not actually deleted but marked as deleted via a status.

# Mock Testing:
#### Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones.

# Securing Passwords with Bcrypt Hashing Function :


#### Passwords are the first line of defense against cyber criminals. It is the most vital secret of every activity we do over the internet(bank account, email account, shopping cart account).
#### The benefit of hashing is that if someone steals the database with hashed passwords, they only make off with the hashes and not the actual plaintext passwords.

### PROBLEMS WITH CRYPTOGRAPHIC HASH ALGORITHM :
##### Brute Force attack
##### Hash Collision attack
##### BCrypt, IT's SLOW AND STRONG AS HELL

# Basic access authentication : 
#### HTTP Basic authentication (BA) implementation is the simplest technique for enforcing access controls to web resources because it does not require cookies, session identifiers, or login pages; rather, HTTP Basic authentication uses standard fields in the HTTP header.

# Authentication Cheat Sheet : 
#### Authentication is the process of verifying that an individual, entity or website is whom it claims to be. Authentication in the context of web applications is commonly performed by submitting a username or ID and one or more items of private information that only a given user should know.

## Authentication General Guidelines¶
### User IDs
##### Make sure your usernames/user IDs are case-insensitive. User 'smith' and user 'Smith' should be the same user. Usernames should also be unique. For high-security applications, usernames could be assigned and secret instead of user-defined public data.

### Implement Proper Password Strength Controls :
##### Minimum length of the passwords should be enforced by the application. Passwords shorter than 8 characters are considered to be weak. 
##### Allow usage of all characters including unicode and whitespace. There should be no password composition rules limiting the type of characters permitted.
##### Ensure credential rotation when a password leak, or at the time of compromise identification.



# node.bcrypt.js : 
# A library to help you hash passwords.

##### bcrypt is a password-hashing function designed by Niels Provos and David Mazières, based on the Blowfish cipher and presented at USENIX in 1999.[1] Besides incorporating a salt to protect against rainbow table attacks, bcrypt is an adaptive function: over time, the iteration count can be increased to make it slower, so it remains resistant to brute-force search attacks even with increasing computation power.

##### The bcrypt function is the default password hash algorithm for OpenBSD[2] and other systems including some Linux distributions such as SUSE Linux.[3]

##### There are implementations of bcrypt for C, C++, C#, Elixir,[4] Go,[5] Java,[6][7] JavaScript,[8] Perl, PHP, Python,[9] Ruby, and other languages.
