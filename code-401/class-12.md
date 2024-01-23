# Data Analysis: Pandas

## Reading Questions

1. **Explain the purpose and basic functionality of the Pandas library. What are some common operations that can be performed on data using Pandas, and how do they contribute to data analysis and manipulation?**

    Pandas is used to organize datasets into tables similar to spreadsheets inside of Python code. After importing data and organizing it a data structure from the Pandas library you can then use methods from the library which provide a wide variety of data manipulation and analysis functions.

    - `.head()` `.tail()` : view the top and bottom rows, can specify a number of rows
    - `.index()` `.columns()` : the row indexes and column headers
    - `.to_numpy()` : converts the table to a NumPy array without indexes or columns
    - `.plot()` : plots the dataset using matplotlib

1. **What are the primary data structures in Pandas, and how do they differ in terms of use cases?**

    - `Series` : a one dimensional array, a single column from a table
    - `DataFrame` : a two dimensional array or table

1. **Describe the process of loading a dataset into a Pandas DataFrame. What are some common file formats that can be used, and which Pandas functions are utilized to read these formats?**

    When loading a dataset into a Pandas DataFrame you use the class function and pass in the dataset to be loaded. `DataFrame(dataset)` The dataset needs to be two dimensional like a two dimensional array, a Python dictionary, or a table from a spreadsheet. Different file formats can also be loaded into a DataFrame using their respective methods.

    ```python
    import pandas as pd

    # csv
    pd.read_csv("file.csv")

    # excel
    pd.read_excel("file.xlsx")
    ```

## References

- [Pandas Docs: User Guide, 10 minutes to pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)
- [Pandas Docs: Getting Started](https://pandas.pydata.org/pandas-docs/stable/getting_started/intro_tutorials/index.html)
- [Corey Schafer: Pandas Tutorials](https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS)
- [Python Programmer: What is Pandas? Why and How to Use Pandas in Python](https://www.youtube.com/watch?v=dcqPhpY7tWk&t=391s)
- [Medium: Towards Data Science: Be a more efficient data scientist, master pandas with this guide](https://towardsdatascience.com/be-a-more-efficient-data-scientist-today-master-pandas-with-this-guide-ea362d27386)
