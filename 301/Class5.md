# Class 5

## Thinking in React

1. single responsibility principle: A module should be responsible to one, and only one, actor. It applies to components in that one component should be dedicated to one thing. So if it ends up growing, it should be decomposed into smaller subcomponents.

2. Building a version of your app that takes your data model and renders the UI but has no interactivity.

3. Build components that reuse other components and pass data using props.

4. - Is it passed in from a parent via props?

  - Does it remain unchanged over time?

  - Can you compute it based on any other state or props in your component?

5. - Identify every component that renders something based on that state.

  - Find a common owner component (a single component above all the components that need the state in the hierarchy).

  - Either the common owner or another component higher up in the hierarchy should own the state.

  - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## Higher-Order Functions

  1. Functions that operate on other functions, either by taking them as arguments or by returning them.

  2. The `map` method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.

  ## Things I want to know more about

  - N/A