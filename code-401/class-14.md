# Data Visualization

## Notes

- Seaborn uses matplotlib and pandas

# Reading Questions

1. **What are the key differences between Matplotlib, Seaborn, and Bokeh libraries in terms of their features and use cases? Provide an example of a specific visualization that is more suitable for each library.**

    - matplotlib
      - Used to create plots from a dataset
      - Simple scatter plots
    - Seaborn
      - Extends matplotlib to make plotting more complex data easier
      - Provides customization options for plots
      - Statistical graphics tools
      - Multi-plot views
    - Bokeh:
      - Plotting/data visualization tool
      - Allows for user interactivity

1. **In the Seaborn library, what are the main functions to create relational, categorical, and distribution plots? Briefly explain the purpose of each type of plot and provide an example use case.**

    **Relational Plots**: Visualizes the relationship between multiple statistical relationships. Has multiple options for different plot types and details to best visualize different types of data.

    ```python
    sns.relplot(
    data=dots, kind="line",
    x="time", y="firing_rate", col="align",
    hue="choice", size="coherence", style="choice",
    facet_kws=dict(sharex=False),
    )
    ```

    **Categorical Plots**: Visualizes data grouped by different categories associated with the data. Also has multiple different options.

    ```python
    sns.catplot(data=tips, kind="swarm", x="day", y="total_bill", hue="smoker")
    ```

    **Distribution Plots**: Visualizes the distribution of values of variables in a dataset.

    ```python
    sns.displot(data=tips, x="total_bill", col="time", kde=True)
    ```

    > Code examples from [Seaborn Docs](https://seaborn.pydata.org/tutorial/introduction.html#a-high-level-api-for-statistical-graphics)

1. **Discuss the role of the Seaborn Cheat Sheet in a Python developer’s workflow. What are some key sections or elements featured in the cheat sheet that can help a developer quickly reference Seaborn functionalities?**

    The Seaborn cheat sheets is a quick reference for loading datasets appropriately and creating plots using Seaborn. The sections I will be using the most are in "Plotting With Seaborn" so I can get an idea of how to implement a particular plot and what its different options are.

## Things I want to know more about

- Understanding what is the right plotting tool to use for different use cases

## References

- [Seaborn: User guide and tutorial](https://seaborn.pydata.org/tutorial.html)
- [Bokeh Tutorial](https://notebooks.gesis.org/binder/jupyter/user/bokeh-bokeh-notebooks-ipmh4dbp/notebooks/tutorial/00%20-%20Introduction%20and%20Setup.ipynb)
- [Seaborn cheat sheet](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Seaborn_Cheat_Sheet.pdf)
