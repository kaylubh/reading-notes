# Object-Oriented Programming, HTML Tables

## Domain Modeling

1. **Explain why we need domain modeling.**

    Domain modeling allows us to create a conceptual model of a problem domain that can be used by users both technical and non-technical to understand what the problem is made up of and what constraints there are. This model can then be used to guide development, especially in object-oriented programming.

## HTML Table Basics

1. **Why should tables not be used for page layouts?**

    The more complex markup associated with using a table for a layout makes it more difficult for accessibility tools like screen readers to interpret a page where a table was used for layout. Using tables for layout makes it more difficult to create responsive design on pages.

2. **List and describe 3 different semantic HTML elements used in an HTML `<table>`**

    - `<th>` for table header
    - `<tr>` for table rows
    - `<caption>` can be used to add a caption to a table

## Introducing Constructors

1. **What is a constructor and what are some advantages to using it?**

    A constructor is a function called with the `new` keyword to create a new object. It allows use to create objects with a shared shape, or set of properties and methods, without having to create or change object literals for each instance of the object.

2. **How does the term `this` differ when used in an object literal versus when used in a constructor**

    When used in an object literal `this` refers to the current object the code is running in or on. When used in a constructor `this` refers to the object being created by the constructor.

## Object Prototypes Using A Constructor

1. **Explain prototypes and inheritance via an analogy from your previous work experience.**

    Prototypes are like a template used to create objects reference back to as a default object. Objects will inherit properties and methods from a prototype if they don't have their own.

## Things I want to know more about

Prototypes

## References

- [Code Fellows: Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
- [MDN: HTML table basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
- [MDN: HTML table advanced features and accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)
- [MDN: JavaScript object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
- [UI Dev: A Beginner's Guide to JavaScript's Prototype](https://ui.dev/beginners-guide-to-javascript-prototype)
