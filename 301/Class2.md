# Readings: State and Props

## React Lifecycle

1. Based off the diagram, it looks like "render" happens first

2. The `static getDerivedStateFromProps` method is first to be invoked.

3. Constructor, Render, componentDidMount, React Updates & componentWillUnmount.

## React State Vs Props

1. You can pass dynamic data like objects and strings.

2. Props you pass into a component which is is handled outside of a component and state is handled inside of that component.

3. If something is being updated in the app, you need to use State. So if you want to change something in your application, you need to store it in State so the application can be re-rendered properly.

4. One example is if you have a form that requires user input. Once the user inputs/updates the information, it should be stored in State. Or if you have a counter, you need to use State to re-render the updated count.

## Things I want to know more about

- Can State and Props be used at the same time?