# Pythonisms

## Reading Notes

1. **What are dunder methods in Python, and how do they allow for the customization of built-in behavior in classes? Provide an example of a common dunder method and its purpose.**

    Dunder methods (double underscore methods), also known as special methods or magic methods, allow you to add methods similar to the ones on built-in types such as getting its length `len()` or being able to iterate over something.

1. **Explain the concept of an iterator in Python. How do you create a custom iterator using the `iter()` and `next()` methods, and why are they important for enabling iteration in a class?**

    An iterator allows you to to go through all the values in an object that contains values which can listed such as elements in a list or characters in string.  You can add functionality to a custom class using the `iter()` and `next()` methods to allow to iterate over an instance of the class.

    ```python
    class BoundedRepeater:
        def __init__(self, value, max_repeats):
            self.value = value
            self.max_repeats = max_repeats
            self.count = 0

        def __iter__(self):
            return self

        def __next__(self):
            if self.count >= self.max_repeats:
                raise StopIteration
            self.count += 1
            return self.value
    ```

    > Code example from [dbader.org: Python Iterators: A Step-By-Step Introduction](https://dbader.org/blog/python-iterators)

1. **What is a generator in Python, and how does it differ from a regular function? Illustrate your answer with an example of a generator function using the ‘yield’ keyword.**

    A generator function only executes when `next()` is called on the generator function. The `yield` keyword is used similarly to return to pass control back to the caller of the function but the generator does not execute any code after the `yield` keyword until `next()` is called on it.

1. **Define decorators in Python and explain their primary use case. How can you create and apply a custom decorator to a function or method? Provide a simple example to demonstrate this concept.**

    Decorators allows you add additional functionality to or modify the behavior of functions. Creating and using decorators creates a modular and reusable way to apply this to multiple functions across a codebase.

    Template Decorator:

    ```python
    import functools

    def decorator(func):
      @functools.wraps(func)
      def wrapper_decorator(*args, **kwargs):
        # Do something before
        value = func(*args, **kwargs)
        # Do something after
        return value
    return wrapper_decorator
    ```

    > Code from [Real Python](https://realpython.com/primer-on-python-decorators/#a-few-real-world-examples)

## Things I want to know more about

- The most common dunder methods to implement on a class
- How is a generator function used in a class?
- When is a good use case for a decorator?

## References

- [dbader.org: Enriching Your Python Classes With Dunder (Magic, Special) Methods](https://dbader.org/blog/python-dunder-methods)
- [dbader.org: Python Iterators: A Step-By-Step Introduction](https://dbader.org/blog/python-iterators)
- [dbader.org: What Are Python Generators?](https://dbader.org/blog/python-generators)
- [Real Python: Primer on Python Decorators](https://realpython.com/primer-on-python-decorators/)
