# FileIO & Exceptions

## Reading Questions

1. **What is the purpose of the `with` statement when opening a file in Python, and how does it help manage resources while reading and writing files?**

    After opening a file in Python you always want to make sure to close the file. Leaving a file open without automatically closing it can result in Python trying to open too many files with your operating system. Additionally, open files present a risk of file corruption should there be an error that results in the program or system crashing. Using the `with` statement to preface on `open` statements in will automatically close the file even in cases of error. `with open(file_name.txt) as file_variable`

1. **Explain the difference between the `read()` and `readline()` methods for file objects in Python. Provide examples of when to use each method.**

    The `read()` method is used to either read the entire file or a specified number of bytes if a size argument is passed. The `readline()` method is used to read the contents of one line in a file or the number of characters if an argument is passed.

1. **Briefly describe the concept of exception handling in Python. How can the `try`, `except`, and `finally` blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.**

    - `try` will always run the code in the try block first until an exception is thrown
    - `except` runs this code when there is an exception
    - `else` runs code if there are no exceptions
    - `finally` always runs this code last regardless of exceptions

    When running a Python program if it encounters an exception (error) it will cause the program to stop and not run any further past the line where the exception happened. Using a `try, except` block allows you to control what happens when an exception is thrown and define custom exceptions as needed.

## Things I want to know more about

- How does Python import non `.py` file types and use them; what are some common uses for this

## References

- [Real Python: Reading and Writing Files in Python](https://realpython.com/read-write-files-python/)
- [Real Python: Python Exceptions: An Introduction](https://realpython.com/python-exceptions/)
- [Corey Schafer: Python Tutorial: File Objects - Reading and Writing to Files](https://www.youtube.com/watch?v=Uh2ebFW8OYM)
