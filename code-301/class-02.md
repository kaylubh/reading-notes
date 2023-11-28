# React: State and Props

## React lifecycle

1. **Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**

    Render will happen before ‘componentDidMount’.

2. **What is the very first thing to happen in the lifecycle of React?**

    The constructor for React components is called before anything else happens.

3. **Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`**

    1. `constructor`
    2. `render`
    3. `React Updates`
    4. `componentDidMount`
    5. `componentWillUnmount`

4. **What does `componentDidMount` do?**

    `componentDidMount` is a method that is called immediately after a component is mounted. It is used to load network requests and initialize the DOM.

## React State Vs Props

1. **What types of things can you pass in the props?**

    You pass things to you want to initialize a component with or use to render in the component.

2. **What is the big difference between props and state?**

    Props are passed into a component and are handling externally to the component. State is internal to the component itself.

3. **When do we re-render our application?**

    We re-render the application when props or state are changed.

4. **What are some examples of things that we could store in state?**

    - Counters
    - Form values
    - User input

## Things I want to know more about

- What is the react component life cycle and how to use it?

## References

- [Medium: React: Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
- [Web Dev Simplified: React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)
