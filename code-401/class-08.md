# Python List Comprehensions and Decorators

## Notes

- Add `*args` and `**kwargs` to decorator wrapper functions to work with functions with arguments
- Use the `@functools.wrap` on wrappers to preserve function attributes for introspection
- Add a `return` to the decorator wrapper if you need a return from the decorated function

## Reading Questions

1. **What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.**

    Syntax: `list = [<expression> for <item> in <iterable object>]`

    Syntax with condition: `list = [<expression> for <item> in <iterable object> if <condition>]`

    Example:

    ```python
    integers = [1, 2, 3]
    squared_integers = [integer ** 2 for integer in integers]
    print(squared_integers) # [1, 4, 9]
    ```

    List comprehensions are a more efficient and readable way to loop through a collection of items. List comprehensions also allow you to add a conditional statement to the loop and only output items matching that condition.

1. **What is a decorator in Python?**

    A decorator wraps a function and modifies its behavior. Use the `@` symbol to reference the decorator function directly above the function definition. To write a decorator function, use a inner function that acts as a wrapper.

    ```python
    def decorator(function):
      def wrapper():
        function()
      return wrapper

    @decorator
    def function():
      pass
    ```

1. **Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading.**

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

- Are there more built-in decorators besides class decorators and how are they used?

## References

- [PythonForBeginners: List Comprehension in Python](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)
- [Real Python: Primer on Python Decorators](https://realpython.com/primer-on-python-decorators/)
