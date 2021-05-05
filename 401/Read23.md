### Do child components have direct access to props/state from the parent?
### We can see there is no way to pass props from a child component to a parent component. However, we can always pass around functions from the parent to child component. The child component can then make use of these functions

### When a component “wraps” another component, how does the child component’s output get rendered?
### By adding the component as childern.

### Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?
### Yes.

### What trick can a parent use to share all props with it’s children
### Cloning children with new props.

# Terms :
### props.children:does is that it is used to display whatever you include between the opening and closing tags when invoking a component.

### Composition:the act of combining parts or elements to form a whole. Components are the UI building blocks in React applications, like pure functions are the building blocks of function composition.

## React Router :
#### React Router v4 is a pure React rewrite of the popular React package. Previous versions of React Router used configuration disguised as pseudo-components and could be difficult to understand. With v4, everything is “just components”.

## Hooks:
#### React Router ships with a few hooks that let you access the state of the router and perform navigation from inside your components.


# react-if component :
#### Conditional rendering in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.


# react testing library queries :
##### Queries are the methods that Testing Library gives you to find elements on the page. There are several types of queries ("get", "find", "query"); the difference between them is whether the query will throw an error if no element is found or if it will return a Promise and retry. Depending on what page content you are selecting, different queries may be more or less appropriate. See the priority guide for recommendations on how to make use of semantic queries to test your page in the most accessible way.


# aria roles:
####  ARIA is shorthand for Accessible Rich Internet Applications. ARIA is a set of attributes you can add to HTML elements that define ways to make web content and applications accessible to users with disabilities who use assistive technologies (AT).