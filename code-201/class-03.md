# HTML Lists, Control Flow with JS, and the CSS Box Model

These notes provide an overview of HTML ordered and unordered lists. It also provides an introduction to the CSS box model and the JS concepts of arrays, operators, expressions, conditionals, and loops.

## Learn HTML: Lists

1. **When should you use an unordered list in your HTML document?**

    Use an unordered list when it doesn't matter the order in which content is displayed in a list.

2. **How do you change the bullet style of unordered list items?**

    You can change the bullet style using the CSS property `list-style-type`. There is an HTML attribute `type` which could also have similar effects but is deprecated and should not be used.

3. **When should you use an ordered list vs an unordered list in your HTML document?**

    Ordered lists should be used when it matters the order the content is displayed in or if the content is typically referred to by its number in a list. A good litmus test for which list to use would be to try changing the order of the items in your list, if the meaning has changed then it is best to use a ordered list `<ol>`, otherwise an unordered list `<ul>` is the best fit.

4. **Describe two ways you can change the numbers on list items provided by an ordered list?**

    You can change the numbers on an ordered list by adding the `type` attribute to an `ol` element. Such as `<ol type="a">` for lowercase letters or `<ol type="I">` for uppercase Roman numerals. They can also be changed using the CSS property `list-style-type`, which is the preferred method.

## Learn CSS: The Box Model

1. **Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**

    > *The Box Model*
    >
    > The box, or box model, is a group of four inseparable friends: Content, Padding, Border, and Margin, who do everything together. Content always stays in the center of the group no matter what happens. Padding keeps some space between Content and Border because sometimes they don't get along and need a little extra space. Border makes sure all the friends stay together. And lastly but surely not least of the bunch is Margin, who has the all important job of keeping the friends far enough away from others who might break up the group.

2. **List and describe the four parts of an HTML elements box as referred to by the box model.**

    - Content Box: The area where your content is displayed; size it using properties like `inline-size` and `block-size` or `width` and `height`.
    - Padding Box: The padding sits around the content as white space; size it using `padding` and related properties.
    - Border Box: The border box wraps the content and any padding; size it using `border` and related properties.
    - Margin Box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using `margin` and related properties.

      *Source: [Mozilla Developer Network Web Docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#what_is_the_css_box_model)*

## Learn JS: Arrays, Operators and Expressions, Conditionals, Loops

1. **What data types can you store inside of an Array?**

    The data you can store in an array is similar to variables. You can store strings, numbers, and other arrays.

2. **Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?**

    Yes it is a valid array which itself is storing more arrays. You can access the values stored using the `map()` or `filter()` functions.

  ```js
  const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
  ```

3. **List five shorthand operators for assignment in javascript and describe what they do.**

    Shorthand operators make it easier to achieve a desired result with less code, for example:
    -  Addition Assignment: `x += y` would add `x` to `y` and assign the new value to `x`
    -  Subtraction Assignment: `x -= y` would subtract `y` from `x` and assign the new value to `x`
    -  Multiplication Assignment: `x *= y` would multiply `x` by `y` and assign the new value to `x`
    -  Division Assignment: `x /= y` would add `x` by `y` and assign the new value to `x`
    -  Exponentiation Assignment: `x **= y` would raise `x` by the power of `y` and assign the new value to `x`

4. **Read the code below and evaluate the last expression and explain what the result would be and why.**

    The expression would evaluate to the boolean `false` because of the variable `c = false`. As long as one variable is false in this expression it will always evaluate to false.

    ```js
    let a = 10;
    let b = 'dog';
    let c = false;

    // evaluate this
    (a + c) + b;
    ```

5. **Describe a real world example of when a conditional statement should be used in a JavaScript program.**

    A conditional statement could be used in a JS program to determine if a user has provided a response to a requested input.

6. **Give an example of when a Loop is useful in JavaScript.**

  A loop could be useful in executing the same code on items in an array. This would allow you to execute the same code on every item in an array without having to retrieve each item with duplicated code.

## Things I want to know more about

- Considering how lists are used and often heavily modified with CSS, are there accessability concerns and how do you best prevent them if there are?
- How to use the box model and the other different CSS models
- More information on how shorthand operators work, especially the non-arithmetic ones

## References

- [MDN: HTML: HyperText Markup Language](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN: \<ol>: The Ordered List element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
- [MDN: \<ul>: The Unordered List element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
- [MDN: Learn to style HTML using CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
- [MDN: The box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#what_is_the_css_box_model)
- [MDN: JavaScript — Dynamic client-side scripting](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
- [MDN: Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
- [MDN: Expressions and operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [MDN: Making decisions in your code — conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
- [MDN: Looping code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)
