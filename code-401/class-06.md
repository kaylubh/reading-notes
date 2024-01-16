# Python Random Module and Testing

## Notes

- To use the random module in Python in needs to be imported `import random`
- Test coverage and code coverage are synonymous

## Reading Questions

1. **How can the random module be utilized in Python to generate random numbers or make selections from a list, and what are some common functions available within the module?**

    - `randint()`: generates random numbers in a range, requires two arguments: the start and end of the range, causes an error if second argument is less than the first
    - `random()`: returns a floating point number between 0 and 1
    - `choice()`: returns a random element from an input collection object (list, tuple)
    - `choices()`: similar to `choice()` but accepts a second argument to specify the number of elements to return in a list, causes an error if number of elements requested is less than the length of list
    - `shuffle()`: shuffles the elements of a list in place
    - `randrange()`: generates a random number from an input range, requires arguments for start, end, and step; exclusive of the end of the range `random.randrange(0, 15, 5) # 0, 5, 10`

1. **In the context of software development, what is risk analysis, and what are the key steps involved in conducting a risk analysis for a software project?**

    In software development, risk analysis is used to understand what a project intends to accomplish and the associated outcomes if software is developed incorrectly to meet that intent. This risk analysis is used to help focus resources for testing and better understand how to implement features while minimizing failures and the potential for liability.

    The key steps of a risk analysis are:

    1. Search for risk
    1. Analyze the effects and impact of each risk
    1. Create mitigation strategies

1. **What is test coverage and why is it an important (or potentially misleading) metric in software testing?**

    Test coverage, or code coverage, is a metric or concept used to explain how you are testing all the code in a given codebase. It is hard to define an exact amount of test coverage that should be completed but there needs to be enough tests to ensure the core functionality of a codebase is working as expected while trying to reduce the amount of duplicate tests which test the same functionality. While a high metric, like 100% test coverage, might sound like good coverage it does not necessarily reflect the quality of the tests for the code which may be testing to situations that are improbable when the code moves to production.

1. **What is Big O notation, and how is it used to describe the performance of an algorithm? Give an example of an everyday task (not software related) that demonstrates O(n) time complexity.**

    Big O notation is used to describe how much space and time an operation takes. When writing Big O notation you always assume the worst-case scenario such as the largest possible input. An example of an everyday task which has O(n) time complexity would be grocery shopping where "n" is the size of your shopping list. This would have a linear time complexity increase as the size of the list increases the amount of time it takes you to complete your shopping increases roughly the same amount for each item on the list.

## Things I want to know more about

- Strategies in software development to implement risk analysis and management without slowing down production unnecessarily
- Tools that measure test coverage

## References

- [PythonForBeginners: How to Use the Random Module in Python](https://www.pythonforbeginners.com/random/how-to-use-the-random-module-in-python)
- [edureka!: What is Risk Analysis in Software Testing and how to perform it?](https://www.edureka.co/blog/risk-analysis-in-software-testing/)
- [Martin Fowler: Test Coverage](https://martinfowler.com/bliki/TestCoverage.html)
- [HackerRank: Big O Notation](https://www.youtube.com/watch?v=v4cd1O4zkGw)
