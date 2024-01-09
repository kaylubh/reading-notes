# Testing and Modules

## Reading Questions

1. **What are the key principles of Test-Driven Development (TDD) in Python, and how do they contribute to the overall quality of code?**

    Some of the key principles in TDD are to establish the expected output of a program before beginning to actually code and then using this information to create tests which can verify if the code being developed meets the requirements. This allows you to focus on writing code tailored to the requirements and can provide logical starting and end points for production.

2. **Explain the purpose of the `if __name__ == '__main__':` statement in Python scripts. What are some use cases for including this conditional in your code?**

    This conditional statement checks to see if the module being run is part of the source file or if it is being imported. If the module is from the source it's `__name__` variable will be assigned the value of `__main__` whereas in the case of importing it will be assigned the file name as it's value. Using this condition in your module allows you to execute different code when the module is being run standalone or as an imported module to another script.

3. **Describe the concept of recursion in Python.**

    Recursion can be used in many programming languages including Python to have a function call itself in order to create an algorithm to solve a problem. In Python, a function can be used to define some code and have it call the function again based on a condition. When creating a recursive function like this, you need to ensure that a base case exists and that the expected input to the code will eventually match the base case condition. This allows you to establish a base case condition which will stop the function from recursing, or calling itself, infinitely.

4. **What is the difference between Python modules and packages? Explain how to create, import, and use them in your Python programs.**

    Modules are programs that are broken down into smaller components which are part of a larger application. Packages are groupings of related modules, packages can be used to import multiple modules at once. To import a module use `import <file_name>` and then you can use that module by accessing the objects in the module with dot notation, `example_module.example_function`.

## Things I want to know more about

- Use cases for the `if __name__ == '__main__':` statement

## References

- [Medium: In Tests We Trust — TDD with Python](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)
- [Geeks for Geeks: What does the `if __name__ == “__main__”:` do?](https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/)
- [Geeks for Geeks: Introduction to Recursion – Data Structure and Algorithm Tutorials](https://www.geeksforgeeks.org/introduction-to-recursion-data-structure-and-algorithm-tutorials/)
- [Real Python: Python Modules and Packages – An Introduction](https://realpython.com/python-modules-packages/)
