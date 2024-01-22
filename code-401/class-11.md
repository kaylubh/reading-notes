# Data Analysis: NumPy

## Notes

- When using NumPy arrays, all elements of the array have to be of the same type

## Reading Notes

1. **What are the key features and benefits of Jupyter Lab, and how does it differ from Jupyter Notebook?**

    - Work with multiple different files in one spot
    - Integrated Jupyter Notebooks

1. **What are the main functionalities provided by the NumPy library, and how can it be useful in Python programming, particularly for scientific computing and data manipulation tasks?**

    The NumPy library makes it easier to work with large datasets using arrays. It allows for quicker data manipulation and analysis operations on a dataset by providing a shorter and more readable syntax to reference the data using its shape.

1. **Explain the basic structure and properties of NumPy arrays, and provide examples of how to create, manipulate, and perform operations on them.**

    NumPy allows you to convert standard multidimensional arrays into NumPy arrays which make it easier to manipulate the data and extract information from the data in the arrays.

    To create a NumPy array, you declare the NumPy package with the array method and then pass in an array. Alternatively, you can use methods such as the `zeros` and `random.rand` methods to create an array filled with zeros or random numbers given the shape of the array as an argument. There are many other ways to create a NumPy array.

    ```python
    import numpy as np

    my_array = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]

    numpy_array = np.array(my_array)
    ```

## Things I want to know more about

- More example of using NumPy to understand how to do it and use cases

## References

- [JupyterLab: Get Started](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html)
- [Dataquest: NumPy Tutorial: Data Analysis with Python](https://www.dataquest.io/blog/numpy-tutorial-python/)
