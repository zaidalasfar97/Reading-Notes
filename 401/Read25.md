# Why do we not need more .html pages in a multi-page React app?
### React-router-dom : It contains the DOM bindings for React Router. In other words, the router components for websites. 

# If we wanted a component to show up on every page, where would we put it and why?
### Inside the `<BrowserRouter />`, outside a `<Route />` .

# What does props.children contain? 
### That it is used to display whatever you include between the opening and closing tags when invoking a component.

# Term :

#### Composition :natural pattern of the component model. It's how we build components from other components, of varying complexity and specialization through props. Depending on how generalized these components are, they can be used in building many other components
#### Children / Child Components :A child component is a more specific part inside a parent component. Example would be a parent component being a PERSON. ARMS and LEGS are child components of it.
#### Hash Routing :Is using the anchor part of the URL to simulate different content. For example http://site.com/#/products/list leads to displaying a list of products. We have to mention that the #/products/list bit is never sent to the server.
#### Link Routing : Provides declarative, accessible navigation around your application.

# Making Sense of React Hooks :

#### Hooks apply the React philosophy (explicit data flow and composition) inside a component, rather than just between the components. That’s why I feel that Hooks are a natural fit for the React component model.
#### Unlike patterns like render props or higher-order components, Hooks don’t introduce unnecessary nesting into your component tree. They also don’t suffer from the drawbacks of mixins.

#### Do Hooks Make React Bloated?
##### Before we look at Hooks in detail, you might be worried that we’re just adding more concepts to React with Hooks. That’s a fair criticism. I think that while there is definitely going to be a short-term cognitive cost to learning them, the end result will be the opposite.

# the state hook : 
### What is a Hook? A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We’ll learn other Hooks later.

#### What does calling useState do? It declares a “state variable”. Our variable is called count but we could call it anything else, like banana. This is a way to “preserve” some values between the function calls — useState is a new way to use the exact same capabilities that this.state provides in a class. Normally, variables “disappear” when the function exits but state variables are preserved by React.


# hooks api :
#### Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class. 

#### UseState is a Hook , We call it inside a function component to add some local state to it. React will preserve this state between re-renders. useState returns a pair: the current state value and a function that lets you update it. You can call this function from an event handler or somewhere else. It’s similar to this.setState in a class, except it doesn’t merge the old and new state together. 

## But what is a Hook?
#### Hooks are functions that let you “hook into” React state and lifecycle features from function components. Hooks don’t work inside classes.

## Hooks API Reference :


#### Basic Hooks : useState ,useEffect, useContext .

#### Additional Hooks :useReducer ,useCallback ,useMemo ,useRef,useImperativeHandle,useLayoutEffect,useDebugValue .

## Using the Effect Hook : 

####  Placing useEffect inside the component lets us access the count state variable (or any props) right from the effect. We don’t need a special API to read it — it’s already in the function scope. Hooks embrace JavaScript closures and avoid introducing React-specific APIs where JavaScript already provides a solution.







