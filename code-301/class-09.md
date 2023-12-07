# Functional Programming

## Functional Programming Concepts

1. **What is functional programming?**

    Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

    > Definition from [Wikipedia](https://en.wikipedia.org/wiki/Functional_programming)

2. **What is a pure function and how do we know if something is a pure function?**

    A pure function does not cause any side effects and is deterministic which means it will always return the same output given the same inputs.

3. **What are the benefits of a pure function?**

    - Easier maintainability

4. **What is immutability?**

    In short immutability is describing a value that cannot be changed.

5. **What is Referential transparency?**

    Referential transparency means you could replace an expression with its result and it would have no effects or changes on the program as a whole.

## Node JS Modules and require()

1. **What is a module?**

    A logical separation of code into a separate file which is separated for maintainability and readability.

2. **What does the word ‘require’ do?**

    Imports a module from another file.

3. **How do we bring another module into the file the we are working in?**

    You import the module using the require function. `require('./example-file')`

4. **What do we have to do to make a module available?**

    Export the parts of the module you want to be available to be imported (required). `module.exports = exampleFunction`

## Things I want to know more about

- What functional programming looks like and how it's used

## References

- [Medium: Concepts of Functional Programming in Javascript](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)
- [Net Ninja: Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)
