# Classes and Recursion

## Reading Questions

1. **What are the key differences between classes and objects in Python, and how are they used to create and manage instances of a class?**

    Objects allow you encapsulate multiple variables and functions into a single entity to make them easier to work with or group related data. Classes are used to create instances of an object, acting as a template for objects of that class. Classes are defined with the `Class` keyword followed by the name of the the class. Instances can be created from the class by calling the defined class function.

1. **Explain the concept of recursion and provide an example of how it can be used to solve a problem in Python. What are some best practices to follow when implementing a recursive function?**

    Recursion can be used in many programming languages including Python to have a function call itself in order to create an algorithm to solve a problem. In Python, a function can be used to define some code and have it call the function again based on a condition. When creating a recursive function like this, you need to ensure that a base case exists and that the expected input to the code will eventually match the base case condition. This allows you to establish a base case condition which will stop the function from recursing, or calling itself, infinitely.

1. **What is the purpose of pytest fixtures and code coverage in testing Python code? Explain how they can be used together to improve the quality and maintainability of a project.**

    Fixtures are an object that is used to have a shared source of data across multiple tests. This helps improve readability, reduce errors caused by duplicated code, and makes it easier to update the data used by multiple tests. Code coverage is how much of the code has been tested. For example, if a function has a condition that results in different code being executed then to get complete code coverage you would need to test all possible conditions of the function. More complete code coverage results in better quality code and reduces the chance of untested errors.

## Things I want to know more about

- Similarities and differences between Python and JS objects

## References

- [learnpython.org: Classes and Objects](https://www.learnpython.org/en/Classes_and_Objects)
- [Real Python: Thinking Recursively in Python](https://realpython.com/python-thinking-recursively/)
- [Linux Journal: Python Testing with pytest: Fixtures and Coverage](https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage)
