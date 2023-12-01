# React: Putting it All Together

## React Docs - Thinking in React

1. **What is the single responsibility principle and how does it apply to components?**

    The single responsibility principle is a programming concept that says "A module should be responsible to one, and only one, actor" ([Wikipedia](https://en.wikipedia.org/wiki/Single-responsibility_principle)). This applies to components in React because it is best practice to have your components make up one part of an application. This makes the app easier to manage and allows for reusability.

2. **What does it mean to build a ‘static’ version of your application?**
 
    A static version displays the basic interfaces and data models of the application with no interactivity. This gives you a starting point to add more content and interactivity.

3. **Once you have a static application, what do you need to add?**

    *INTERACTIVITY*

4. **What are the three questions you can ask to determine if something is state?**

    1. Does it remain unchanged over time? If so, it isn’t state.
    2. Is it passed in from a parent via props? If so, it isn’t state.
    3. Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!

    Anything that doesn't apply to these three questions is probably state

    > Examples provided from [React Docs](https://react.dev/learn/thinking-in-react)

5. **How can you identify where state needs to live?**

    After identifying which components need the state, find the closest common parent of those components and that is usually the best place to put the state.

## Higher-Order Functions

1. **What is a “higher-order function”?**

    "Functions that operate on other functions, either by taking them as arguments or by returning them."

    > Definition from [Eloquent JavaScript: Higher-order functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

2. **Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**

    It returns a variable `m` whose value is the boolean result of the expression `m > n`

3. **Explain how either map or reduce operates, with regards to higher-order functions.**

    They are methods (functions) which take a function as one of their parameters which means they can be considered higher-order functions.

## Things I want to know more about

- Is building a static application common in all programming workflows or just React?
- Practical examples of higher-order functions

## References

- [React Docs: Thinking in React](https://react.dev/learn/thinking-in-react)
- [Eloquent JavaScript: Higher-order functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)
