# How granular should your reducers be?
#### There should be a separate reducer function for each slice of data. They are combined before being put into the store.

# Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
#### We suggest you write independent small reducer functions that are each responsible for updates to a specific slice of state. We call this pattern “reducer composition”. A given action could be handled by all, some, or none of them. 

# Name a strategy for preventing the above
#### 1-Develop the right attitude about driving. ...
#### 2-Get as much supervised practice driving as possible.


# Term
### store :A store holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it.
### combined reducers :The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.


# Async actions:
### Redux Middleware and Side Effects :
##### we said that Redux reducers must never contain "side effects". A "side effect" is any change to state or behavior that can be seen outside of returning a value from a function. Some common kinds of side effects are things like:

###### Logging a value to the console
###### Saving a file
###### Setting an async timer
###### Making an AJAX HTTP request
###### Modifying some state that exists outside of a function, or mutating arguments to a function
###### Generating random numbers or unique random IDs (such as Math.random() or Date.now())


### Writing an Async Function Middleware :
###### Both of the middleware in that last section were very specific and only do one thing. It would be nice if we had a way to write any async logic ahead of time, separate from the middleware itself, and still have access to dispatch and getState so that we can interact with the store.

###  Redux thunk:
##### By default, Redux’s actions are dispatched synchronously, which is a problem for any non-trivial app that needs to communicate with an external API or perform side effects. Redux also allows for middleware that sits between an action being dispatched and the action reaching the reducers.There are two very popular middleware libraries that allow for side effects and asynchronous actions: Redux Thunk and Redux Saga.

