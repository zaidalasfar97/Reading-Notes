# Write the following steps in the correct order:
##### Register your application to get a client_id and client_secret
##### Ask the client if they want to sign in via a third party
##### Receive authorization code
##### Redirect to a third party authentication endpoint
##### Make a request to the access token endpoint
##### Make a request to a third-party API endpoint
##### Receive access token

# What can you do with an authorization code? 
#### The only thing you can do with the authorization code is to make a request to get an access token

# What can you do with an access token?
##### Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user's data. Access tokens must be kept confidential in transit and in storage.

# What’s a benefit of using OAuth instead of your own basic authentication?
##### OAuth doesn’t share password data but instead uses authorization tokens to prove an identity between consumers and service providers.


# Client ID:
##### The client_id is a public identifier for apps. Even though it's public, it's best that it isn't guessable by third parties, so many implementations use something like a 32-character hex string. It must also be unique across all clients that the authorization server handles
# Client Secret : 
##### Is a secret used by the OAuth Client to Authenticate to the Authorization Server. The Client Secret is a secret known only to the OAuth Client and the Authorization Server. Client Secret must be sufficiently random to not be guessable.
# Authentication Endpoint : 
##### The Authentication API enables you to manage all aspects of user identity when you use Auth0. It offers endpoints so your users can log in, sign up, log out, access APIs, and more.
# API Endpoint :
##### IS a point at which an application program interface (API) -- the code that allows two software programs to communicate with each other -- connects with the software program 
# Authorization Code :
##### Is a temporary code that the client will exchange for an access token. The code itself is obtained from the authorization server where the user gets a chance to see what the information the client is requesting, and approve or deny the request
# Access Token : 
##### Is an object encapsulating the security identity of a process or thread. A token is used to make security decisions and to store tamper-proof information about some system entity.


# What is JSON Web Token? 
#### JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed.

# When should you use JSON Web Tokens?
#### Authorization. 
#### Information Exchange .


# What is the JSON Web Token structure? 
#### Header
#### Payload
#### Signature

