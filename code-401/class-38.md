# React Review

## Reading Questions

1. **How does lifting state up in a React application help with managing data flow and what are the benefits of using this approach?**

    Lifting up state in a React application can make it easier to work with state when the stateful data needs to be used to affect multiple components, by lifting up to state to their common parent/ancestor it allows you to easily influence multiple components when the state changes. The alternative to this requires you pass state via functions passed via props which is usually an unnecessarily complex solution.

1. **Explain the concept of conditional rendering in React and provide an example of how to implement it in a component.**

    Conditional rendering in React is used to control when content is rendered through specified conditions such as a boolean prop or the existence of data at the time of render. There are a few methods to implement this in React:

    - Use a conditional statement in the return block to specify which markup to use based on a condition
    - Use a ternary operator to specify the markup to use
    - Use the logical AND operation to create an expression which renders markup when the left condition is true, otherwise it will render nothing

1. **What are the main principles behind “Thinking in React” and how do they guide the process of designing and building a React application?**

    The main principles to thinking in React is to break up the application into components and manage data flow with state and props. Building an application in React requires you to define separate components which establishes the structural hierarchy of the application and make decisions about how data is passed down and back up along this structure.

## Things I want to know more about

- How does Next.js affect React features such as state and other hooks?

## References

- [React Docs: Sharing State Between Components](https://react.dev/learn/sharing-state-between-components)
- [React Docs: Conditional Rendering](https://react.dev/learn/conditional-rendering)
- [React Docs: Thinking in React](https://react.dev/learn/thinking-in-react)
