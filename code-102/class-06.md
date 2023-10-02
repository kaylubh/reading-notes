# JavaScript Basics

JavaScript (JS) is a lightweight programming language which can be used in front-end or back-end development and applications. JS is used to add dynamic content to web pages as well as being used in applications outside the browser.

## Variables

Variables are containers used to store information in JS. Variables can be used to store numbers, strings, boolean, arrays, and objects. Variable names can include any combination of the letters, numbers, the dollar sign "$", and underscore "_". Variable names cannot begin with a number. The best practice is to use variable names which provide a short description or context for what information the variable is storing. Another common practice is to use lower camel case which combines multiple words into a single string, eliminating spaces, with the first word being completely lower case and any subsequent words being capitalized.

### Declaring

Declaring a variable means to create a variable in the code. This can be done in four different ways:

#### `let`

The `let` keyword is used to declare a variable whose value can be changed after it is initialized.

```js
let x = 1;
```

#### `const`

The `const` keyword is used to declare a variable whose value cannot be changed after it is initialized.

```js
const userName = 'John Doe'; 
```

#### `var`

The `var` keyword is no longer in use in modern JS but may be seen in older JS code. A variable declared with `var` can be changed after it is initialized.

```js
var oldVariable = 2;
```

#### Automatically

The last option is automatically, which means the variable is declared the first time it is used. While this is possible, it is considered bad programming practice to use a variable without declaring it first.

```js
x = 3;
```

### Initializing

Initializing a variable means to assign a value to the variable. Variables can be declared and initialized at the same time, or in the same statement, or they can declared and initialized in separate statements. When using the `const` keyword you must declare and initialize the variable in the same statement. Before a variable is initialized its value is "undefined".

```js
let x;
x = 1;

const y = 2;
```

## Operators

Operators are syntax used in JS. The two most common basic operators are `=` and `==`. The equal sign `=` is the assignment operator, which is used to assign a value to a variable. The double equal sign `==` is the equivalent of "equal to" which can be used in JS to create boolean logic.

## User Input

User input is information which is not in the code or application but received from the ***user*** whose system is executing the JS. User input can be received by soliciting the information from the user or using JS functions to obtain information from the user's system. User input can be used to create and control dynamic content. A very simple way to obtain input from the user would be to use the `prompt()` JS function:

```js
let userName;

userName = prompt('Please enter your name:');

alert('Welcome ' + userName);
```

This code would declare the variable `userName` and then use the `prompt()` function to ask the user for their name. The response from the user would be stored in the variable `userName`. Lastly it would display a welcome message to the user with the value from the `userName` variable using the `alert()` function.

## References

- [MDN JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
