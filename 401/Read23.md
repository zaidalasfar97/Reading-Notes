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