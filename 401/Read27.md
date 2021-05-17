# Describe use cases for useMemo() and useReducer():
### useReducer takes three positional arguments — a reducer, its initial state, and a function that can return the initial state — let’s call it init for now. The final argument is optional. You can just pass in the initialState as is (e.g. {count: 0}), but if you want to operate on it in any way, I’d suggest using the init function.

### useMemo(): useMemo is similar to useCallback except that instead of memoizing a function, it memoizes a value

# Why do custom hooks need the use prefix?

##### React custom hooks is nothing more than a JavaScript function. It encapsulates components logic, can be imported, exported and reused all over the application. If you have a repetitive hooks logic in components, it might be a good idea to extract it into a separate function and reuse all over the application. Also, a custom hook function can call other React hooks if needed.

# What do custom hooks usually do?
#### Custom hooks allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks.

# Using any list of custom hooks, research and name one that you think will be useful in your applications
###  useClippy ,  useBrowserContextCommunication ,useScript

# Term :
### Reducer	: is a function that determines changes to an application’s state. It uses the action it receives to determine this change.


# context api :
### Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language