# Forms and JS Events

## HTML Forms: How To Structure A Web Form

1. **Why are forms so important in web development?**

    Form are one of the primary ways that users can interact with a web page or application. Forms can receive input from the user which can then be sent for server-side processing or used to control elements on the page.

2. **When designing a form, what are some key things to keep in mind when it comes to user experience?**

    - Ask for as little data as possible
    - Focus on simple, short forms

3. **List 5 form elements and explain their importance.**

    - `<form>` used wrap around all the elements in a form. Provides semantic markup to the document and help assistive devices identify forms.
    - `<label>` used to provide a semantic and rendered label explaining what the particular form input is expecting
    - `<input>` used to create an element for a user to provide input, several different types defined with the `type` attribute
    - `<textarea>` used to create a larger multi-line area for a user to input text
    - `<button>` can be used to control actions with the form such as submitting the form

## Learn JS: Introduction To Events

1. **How would you describe events to a non-technical friend?**

    Events are simply ways to understand when something has happened on a website like when it is loaded or when you click on something. There are many other types of events but they all provide the ability to do something when something happens.

2. **When using the addEventListener() method, what 2 arguments will you need to provide?**

    First you will need to provide the name of the event to listen form in a string and second a function to call when it happens.

3. **Describe the event object. Why is the target within the event object useful?**

    The event object provides additional information about an event that can be used to add functionality to an event handler.

4. **What is the difference between event bubbling and event capturing?**

    Event bubbling represents how event occur on an element starting from the element and on each all its parent elements. Event capturing happens in the reverser order, the even begins on the highest level parent first and goes down to the element itself last.

## Things I want to know more about

- Common/best practices of using events to add dynamic functionality to web pages

## References

- [MDN: Web forms — Working with user data](https://developer.mozilla.org/en-US/docs/Learn/Forms)
- [MDN: Your first form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)
- [MDN: How to structure a web form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)
- [MDN: JavaScript — Dynamic client-side scripting](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
- [MDN: Introduction to events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
- [MDN: The HTML5 input types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)
- [MDN: Event reference](https://developer.mozilla.org/en-US/docs/Web/Events)
