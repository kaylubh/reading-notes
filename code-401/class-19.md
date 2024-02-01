# Automation

# Reading Questions

1. **How can you use regular expressions in Python to search for specific patterns in a string, and what is the primary module to work with them?**

    In order to use regular expressions in Python you will need the regular expressions module which can be imported from the standard library with `re`. Regular expressions can be used with the methods provided in the `re` library to find patterns in strings, validate strings match certain patterns, or even replace characters in a string.

1. **What is the purpose of the shutil module in Python, and provide an example of a common use case for file or directory management with this module?**

    The `shutil` module can be used to find, copy, and archive (compress/zip) files. A common use case would be copying files to a new location when executing a program, which could be used to automate certain tasks.

1. **Compare and contrast the os and shutil modules. When would you choose to use one over the other?**

    The `os` module provides several different functionalities but is primarily used for file system management tasks and managing process environments. Unlike `shutil`, `os` gives you additional options for file system tasks like creating and deleting directories.

## Things I want to know more about

- Is using libraries like `shutil` to copy files the same as doing it in the terminal manually?
- How to automate running terminal commands

## References

- [datacamp: Python Regular Expression Tutorial](https://www.datacamp.com/tutorial/python-regular-expression-tutorial)
- [PyMOTW-3: shutil — High-level File Operations](https://pymotw.com/3/shutil/)
- [PyMOTW-3: os — Portable access to operating system specific features](https://pymotw.com/3/os/)
