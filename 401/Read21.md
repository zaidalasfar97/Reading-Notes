# Does a deployed React application require a server?
#### You don't necessarily need a static server in order to run a Create React App project in production. It also works well when integrated into an existing server side app.

# Why do we prefer to test a React application at the behavior rather than the unit level?
#### This documentation section focuses on testing strategies for the first case. While full end-to-end tests can be very useful to prevent regressions to important workflows, such tests are not concerned with React components in particular, and are out of the scope of this section.

# What does npm run build do?
#### runs the script "build" and created a script which runs your application - let's say server.js.

# Describe the actual composition / architecture of a React application



# Term :

### BDD : behavior-driven development (BDD) is an Agile software development process that encourages collaboration among developers, QA, and non-technical or business participants in a software projec

### Acceptance Tests:is a formal description of the behavior of a software product, generally expressed as an example or a usage scenario. A number of different notations and approaches have been proposed for such examples or scenarios.

### mounting:This method is called just before a component mounts on the DOM or the render method is called. After this method, the component gets mounted.


# SetState :
#### setState() is the only legitimate way to update state after the initial state setup. Let’s say we have a search component and want to display the search term a user submits.

# Handling Events :
#### Handling events with React elements is very similar to handling events on DOM elements. There are some syntax differences:

#### React events are named using camelCase, rather than lowercase.
#### With JSX you pass a function as the event handler, rather than a string.


# Forms :
### In HTML, form elements such as <input>, textarea, and select typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

# State and Lifecycle :

#### Converting a Function to a Class
#### You can convert a function component to a class in five steps:

#### Create an ES6 class, with the same name, that extends React.Component.
#### Add a single empty method to it called render().
#### Move the body of the function into the render() method.
#### Replace props with this.props in the render() body.
#### Delete the remaining empty function declaration.

# Components and Props : 
#### Components let you split the UI into independent, reusable pieces, and think about each piece in isolation. 

#### This function is a valid React component because it accepts a single “props” (which stands for properties) object argument with data and returns a React element. We call such components “function components” because they are literally JavaScript functions.

#### You can also use an ES6 class to define a component:


```
class Welcome extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1>;
  }
}
```
