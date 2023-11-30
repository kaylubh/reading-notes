# React and Forms

## How to use Forms in React

1. **What is a ‘Controlled Component’?**

    A "controlled component" is one that's state is being handled by React instead of the native DOM.

2. **Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

    It depends on the complexity of the form and the intent of the form. Simpler forms might be easier to implement when they are submitted instead of updating the state each time a user inputs something. Conversely, by storing the state on input instead of submit, you can better manage complex or bigger forms and do things like update or re-render the form based on user input if needed.

3. **How do we target what the user is entering if we have an event handler on an input field?**

    You can target what the user is entering by using the event object that is created when the event fires. `event.target` will return the input field that fired the event allowing you to retrieve things like the input `event.target.value`

## The Conditional (Ternary) Operator Explained

1. **Why would we use a ternary operator?**

    The ternary operator allows you write shorter and simpler conditional statements.

2. **Rewrite the following statement using a ternary statement:**

    ```javascript
    if(x===y){
      console.log(true);
    } else {
      console.log(false);
    }
    ```

    ```javascript
    x===y ? console.log(true) : console.log(false);
    ```

## Things I want to know more about

- Common/best practices for React controlled forms
- Differences between the `if` conditional statement and the ternary operator

## References

- [Robin Wieruch: How to use Forms in React](https://www.robinwieruch.de/react-form/)
- [Medium: JavaScript — The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
