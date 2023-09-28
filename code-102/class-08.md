# JavaScript Expressions and Loops

In JavaScript, expressions and loops can be used to control when and how many times your JS code will execute. Both expressions and loops make use of operators within JavaScript such as assignment operators `=`, comparison operators `==` `!=`, and arithmetic operators `+` `++`.

## Expressions

An expression is a piece of code that resolves to a value. There are two types of expressions, ones that have side effects and ones that only evaluate. An expression such as `x = 1` has the ***side effect*** of assigning the value of "1" to the variable "x". An expression of `1 + 1` will simply evaluate with no effects. Almost all expressions written by developers are intended to have ***side effects*** so instead of `1 + 1`, storing the result of that expression in a new variable `y = 1 + 1` creates an effect from the expression. Expressions can also be used to evaluate arithmetic and create comparisons which evaluate to true or false.

## Loops

Loops are used in JavaScript to easily repeat code such as statements or functions. There are many different types of loops which provide different ways for the loop to start and end. These notes will cover the `while` loop and `for` loop.

### `while` Loop

A `while` loop will execute its statements as long as a condition evaluates to true. As long as the condition continues to evaluate to true it will continue to execute the statements it contains. Only when the condition evaluates to false will it stop. This can result in very long or potentially infinite loops if the conditions are not properly designed. `while` loops are best used for situations when you don't know how many times you want your code to execute such as when receiving user input.

```js
while (conditon) {
    statement;
}
```

```js
let x = 3;

while (x <= 5) {
    x++;
}
```

In this example, the variable `x` is assigned the value of "3". A `while` loop is then used to evaluate if `x` is less than or equal to 5. If this is true, which it is, it the executes the statement `x++` which will increment, or add 1, to the value of `x` to "4". It will then repeat this loop until the condition evaluates to false which will happen when the value of `x` becomes "6". This will ***break the loop*** and move on to the next line in the JavaScript code.

### `for` Loop

A `for` loop will also execute its statements as long as a ***condition*** evaluates to true. A `for` loop differs from a `while` loop because you also specify the starting point, or ***initialization***, and optionally include an ***afterthought*** which will increment or decrement the initializing variable. `for` loops will also stop, or break, when the condition evaluates to false. `for` loops are best used in situations when you know how many times you want you code to execute.

```js
for (initialization; condition; afterthought) {
    statement;
}

```

```js
for (i = 0; i < 5; i++) {
    console.log(i); // 1, 2, 3, 4
}
```

In `for` loops, the initialization creates a variable, commonly "i", which controls the loop and establishes its starting point, in this case "0". In this example, the variable `i` is initialized with a value of "0". The condition then evaluates it to see if it is true that it is less than 5, which it is so it executes the `console.log(i)` statement in the code block to log the value of `i` in the console. ***After*** it executes this statement, the afterthought increments (adds 1) to the value of `i`. This loop will repeat and log in the console the value of `i` until `i` is assigned the value of "5" which will evaluate to false since 5 is not less than 5 and break the loop.

## References

- [MDN Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [MDN Loops and Iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)
