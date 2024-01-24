# Linear Regressions

## Notes

- Scikit Learn is a library that provides machine learning methods for predictive data analysis
- Linear regression is a regression method
- When using data for the x input on a a linear regression model it must be two dimensional, specifically one column and no limit on rows

## Reading Questions

1. **Can you explain the basic concept of linear regression and its purpose in the context of machine learning and data analysis?**

    Linear regression plots scattered data points and estimates the linear relationship between those points to provide a model for predicting future points in the data. A straight line that best fits the linear relationship of the data is added to the plotted to visualize this. It is used in the context of machine learning and data analysis to analyze the if/what the correlation between variables in a large data set and predict output.

1. **Describe the process of implementing a linear regression model using Python’s Scikit Learn library, including the necessary steps and functions.**

    1. Import

        ```python
        import numpy as np
        from sklearn.linear_model import LinearRegression
        ```

    1. Data

        ```python
        # x is input, y is output
        x = np.array([5, 15, 25, 35, 45, 55]).reshape((-1, 1))
        y = np.array([5, 20, 14, 32, 22, 38])
        ```

    1. Model

        ```python
        model = LinearRegression()
        model.fit(x, y)
        ## OR ##
        model = LinearRegression().fit(x, y)
        ```

    1. Results

        ```python
        r_sq = model.score(x, y)
        ```

    1. Predict

        ```python
        y_pred = model.predict(x)
        ```

    > Code samples from [Real Python](https://realpython.com/linear-regression-in-python/#simple-linear-regression-with-scikit-learn)

1. **What is the purpose of splitting the dataset into train and test sets, and how does this contribute to the evaluation of a machine learning model’s performance?**

    The train test split allows you to model a simulation of how a model would perform with new data. By splitting the data into a train set and a test set it provides a way to tests the models performance with new data.

## Things I want to know more about

- A better understanding of how to implement a linear regression model using the Scikit Learn library

## References

- [ActiveState: How To Run Linear Regressions In Python Scikit-learn](https://www.activestate.com/resources/quick-reads/how-to-run-linear-regressions-in-python-scikit-learn/)
- [Real Python: Linear Regression in Python](https://realpython.com/linear-regression-in-python/)
- [jbstatistics: Introduction to Simple Linear Regression](https://www.youtube.com/watch?v=KsVBBJRb9TE)
- [builtin: Understanding Train Test Split](https://builtin.com/data-science/train-test-split)
- [Statistics Solutions: What is Linear Regression?](https://www.statisticssolutions.com/free-resources/directory-of-statistical-analyses/what-is-linear-regression/)
