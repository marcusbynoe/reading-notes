# Readings: Introduction to React and Components

## Component-Based Arcitecture[^1]

[^1]: My reference: <https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm>

1. A component is a software object that is modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

2. Here is a list of some characteristics of Components:

- `Replaceable` − Components may be freely substituted with other similar components.

- `Extensible` - A component can be extended from existing components to provide new behavior.

- `Independent` - Components are designed to have minimal dependencies on other components.

3. Here is a list of some of the advatanges of using component-based architecture:

- `System maintenance and evolution` − Easy to change and update the implementation without affecting the rest of the system.

- `Reduced cost` − The use of third-party components allows you to spread the cost of development and maintenance.

- `Reliability` − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

## What is Props and How to Use it in React[^2]

[^2]: My reference: <https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0>

1. Properties

2. It is used for passing data from one component to another.

3. First step is to define an attribute and its value(data). Second step is to pass it to child component(s) by using props. Lastly, you render the props data.
