# JavaScript Functions

JavaScript functions are a specific block of code comprised of statements intended to accomplish a task. Functions should receive input and produce output in a way that creates correlation between the input and output. Functions are executed when the function is invoked (called).

## Control Flow

Control flow is the order that a computer executes a script. Unless otherwise structured, code is executed from it's first line to the last line of a file. Control structures can be used to control the order in which code executes. These could be things such as conditionals, loops, functions, and events.

## Defining Functions

Functions can be defined by ***function declarations*** and ***function expressions***. These notes will only cover ***function declarations***.

### Functions Declarations

A function declaration, or function statement, are comprised of the name of the function, the parameters of the function, and the statements which make up the function. To create a function you first begin with the `function` keyword followed by the name of the function such as `myFunction()`. Functions will always have the parentheses `()` immediately after the name of the functions, these parentheses are used to store the parameters of the function. The main body of the function is then created using JavaScript statements inside a set of curly braces `{}`. If you want your function to return a value to the function or variable which called it, the last statement must be the `return` keyword followed by which value you want to return.

```js
function myFunction(x, y){
    sum = x + y;
    return sum;
}
```

## Invoking Functions

Simply defining a function does not cause the function to execute. Functions need to be invoked or called in order to execute. Functions can be invoked when they are called from other JS code, when an event happens, or automatically if self-invoked. Continuing with the example above, you could create a statement to call the function which will then cause it to execute.

```js
function myFunction(x, y){
    sum = x + y;
    return sum;
}

const answer = myFunction(2, 2);
```

In this example, the function is again defined and expects to be provided with two parameters which it will add together and provide the sum of those values as its return output. The function is then called in the statement which sets the variable `answer` to the value returned by `myFunction()`.

## References

- [MDN JavaScript Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
