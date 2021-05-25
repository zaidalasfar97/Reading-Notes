# What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
#### The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your app.
# When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
#### You will exporting the new data to replace the state from the reducer.

# Terms:
#### middleware:Code you put in between the framework receiving a request and the framework generating the response.
#### thunk:Is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store’s dispatch method, which is then used to dispatch regular synchronous actions inside the function’s body once the asynchronous operations have been completed.

# Redux Toolkit  :
##### configureStore(): wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.
##### createReducer(): that lets you supply a lookup table of action types to case reducer functions, rather than writing switch statements. In addition, it automatically uses the immer library to let you write simpler immutable updates with normal mutative code, like state.todos[3].completed = true.
##### createAction(): generates an action creator function for the given action type string. The function itself has toString() defined, so that it can be used in place of the type constant.
##### createSlice(): accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.
##### createAsyncThunk: accepts an action type string and a function that returns a promise, and generates a thunk that dispatches pending/fulfilled/rejected action types based on that promise
##### createEntityAdapter: generates a set of reusable reducers and selectors to manage normalized data in the store
##### The createSelector utility from the Reselect library, re-exported for ease of use.