# Data Structures and Algorithms

## Data Structures

- Linked Lists: made up of nodes, fist item in the list is head, last is tail; quick at adding and removing items from head and tail but inefficient when retrieving items by index
- Arrays: collection of items, lists in Python; efficient at retrieving items by index but potentially takes up more space than other data structures
- Hash Tables: collection of keys referencing values; efficient at retrieving and adding, can be spread out across memory, possible issues with collisions
- Stacks: first in, last out collection; call stack, push and pop; efficient but limited use cases
- Queues: first in, first out; enqueue and dequeue; efficient but limited use cases
- Graphs: similar to linked list, the links are called "edges" and have weights
- Trees: type of graph which data expands in one direction

## Discussion Questions

1. **What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?**

    When deciding on which data structure to use, you should consider how you need to use the data to solve a particular problem. Different data structures can take up different amount of space in memory and are more efficient in different ways depending on how you want to manipulate the data.

1. **How can we ensure that we’ll avoid an infinite recursive call stack?**

    When using a recursive function you need to make sure to include a base case in the function to prevent an infinite loop. The base case defines a condition in the function in which the function doesn't call itself. As long as the base case condition isn't met then the function will continue to call itself by using the recursive case.

## Things I want to know more about

- Common and realistic use cases for recursive functions
- How are linked lists used

## References

- [Triple Byte: Why you should learn Big-O and stop hacking your way through algorithms](https://web.archive.org/web/20230207075759/https://triplebyte.com/blog/why-you-should-learn-big-o-and-stop-hacking-your-way-through-algorithms)
- [freeCodeCamp: Recursion in software development](https://www.youtube.com/watch?v=vPEJSJMg4jY)
- [Aaron Jack: DATA STRUCTURES you MUST know](https://www.youtube.com/watch?v=sVxBVvlnJsM)
- [HackerRank: Big O Notation](https://www.youtube.com/watch?v=v4cd1O4zkGw)
