# React: Passing Functions as Props

## React Docs - lists and keys

1. **What does `.map()` return?**

    `.map()` iterates through an array and returns a new array of the same length after executing a callback function on each item on the array. The callback function needs to return the items that will compose the new array.

2. **If I want to loop through an array and display each value in JSX, how do I do that in React?**

    You could use the `.map()` method or a for loop on the array and store the result in a variable. You then insert the array reference inside curly braces `{}` in the render statement of component function.

    ```javascript
    const products = [
      { title: 'Cabbage', id: 1 },
      { title: 'Garlic', id: 2 },
      { title: 'Apple', id: 3 },
   ];

    const listItems = products.map(product =>
      <li key={product.id}>
      {product.title}
      </li>
    );

    return (
      <ul>{listItems}</ul>
    );
    ```

    > Code example from [React.dev](https://react.dev/learn#rendering-lists)

3. **Each list item needs a unique ____.**

    Each item in a list needs a unique key.

4. **What is the purpose of a key?**

    The key is a unique identifier to each item in a list which allows React to know how to handle the items based on other interactivity or state changes.

## The Spread Operator

1. **What is the spread operator?**

    `...`

2. **List 4 things that the spread operator can do.**

    - Copy an arrays/objects
    - Merge arrays/objects
    - Conditionally add values to an array/objects
    - Replace the use of the `apply()` method

3. **Give an example of using the spread operator to combine two arrays.**

    ```javascript
    const arrayA = ['a', 'b', 'c'];
    const arrayB = ['d', 'e', 'f'];

    const arrayC = [...arrayA...arrayB] // ['a', 'b', 'c', 'd', 'e', 'f']
    ```

4. **Give an example of using the spread operator to add a new item to an array.**

    ```javascript
    const string = 4;

    const Array = [1, 2, 3, ...string] // [1 ,2, 3, 4]
    ```

5. **Give an example of using the spread operator to combine two objects into one.**

    ```javascript
    const obj1 = { foo: "bar", x: 42 };
    const obj2 = { bar: "baz", y: 13 };

    const mergedObj = { ...obj1, ...obj2 };
    // { foo: "bar", x: 42, bar: "baz", y: 13 }
    ```

    > Code example from [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax#spread_in_object_literals)

## How to Pass Functions Between Components

1. **In the video, what is the first step that the developer does to pass functions between components?**

    Pass the function from the parent to the child as a prop. `function={function}`

2. **In your own words, what does the handleClick function do?**

    Executes a function when a click event happens??? Honestly I'm super confused by this video and will do further research.

3. **How can you pass a method from a parent component into a child component?**

    Create function in the parent that accepts a callback argument, pass the function to the child, execute the function in the child with the callback as an argument

4. **How does the child component invoke a method that was passed to it from a parent component?**

    By creating a function with the prop that was passed to it from the parent.

## Things I want to know more about

- What are best practices for iterating through and adding lists of content to JSX?
- A better understanding of what the spread operator/syntax is and when to use it

## References

- [React Docs: Rendering lists](https://react.dev/learn#rendering-lists)
- [MDN: Spread syntax (...)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
- [Tim Mousk: How To Pass A Function As A Prop In React?](https://www.youtube.com/watch?v=n-6i_WGIOKE)
