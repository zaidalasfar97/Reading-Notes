## What does a component’s lifecycle refer to?
##### Components are created (mounted on the DOM), grow by updating, and then die (unmount on DOM). This is referred to as a component lifecycle. There are different lifecycle methods that React provides at different phases of a component's life.

## Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect

## Why are functional components preferred over class components?
##### Functional component are much easier to read and test because they are plain JavaScript functions without state or lifecycle-hooks. You end up with less code. They help you to use best practices.

## What is wrong with the following code?
##### UseEffect can't be inside for loop.

# Term:
### state hook:A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components
### effect hook : By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates. 


# Custom hooks:
### Custom Hooks are JavaScript functions whose names are prefixed with the word use. A custom Hook is a normal function but we hold them to a different standard. By adding the word use to the beginning, it lets us know that this function follows the rules of Hooks.

# useReducer :
### useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

