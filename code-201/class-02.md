# Basics of HTML, CSS & JS

These notes are a continuation from the previous notes providing an overview of HTML, CSS, and JS. It also covers the importance of semantic elements and using operators/comparison in JavaScript.

## Introduction to HTML Continued

1. **Why is it important to use semantic elements in our HTML?**

    Semantic elements help to define the purpose of content. Semantic elements make it easier to recognize what the function of code will be.

2. **How many levels of headings are there in HTML?**

    There are six levels of headings, `<h1>` thru `<h6>`.

3. **What are some uses for the `<sup>` and `<sub>` elements?**

    They could be used for things like dates and certain things when using math.

4. **When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?**

    To provide the full expansion of the term you would use the "title" attribute. `<abbr title="example">ex.</abbr>`

## Learn CSS

1. **What are ways we can apply CSS to our HTML?**

    CSS can be applied to HTML in three ways: using an external stylesheet with the `<link>` element, in an internal stylesheet using the `<style>` element, and lastly inline by using the style attribute `<p style="">` on an HTML element.

2. **Why should we avoid using inline styles?**

    Mixing two different types of code, HTML and CSS, by using inline styles makes the code less readable. It could also result in duplication of work when a single CSS rule in an internal or external stylesheet would achieve the same effect with less code or editing.

3. **Review the block of code below and answer the following questions:**

    1. **What is representing the selector?**

        `h2`

    2. **Which components are the CSS declarations?**

        `color: black;` `padding: 5px;`

    3. **Which components are considered properties?**

        `color` and `padding`

    ```css
    h2 {
        color: black;
        padding: 5px;
    }
    ```

## Learn JS

1. **What data type is a sequence of text enclosed in single quote marks?**

    A string

2. **List 4 types of JavaScript operators.**

    - The assignment operator `=` used to assign value to variables
    - The addition operator `+` used for addition or concatenating strings
    - The strict equality operator `===` used to compare if two values are equal and the same data type
    - The not operator `!` which can be used to return the logical opposite

3. **Describe a real world Problem you could solve with a Function.**

    You could use a function to determine if the data entered into a form is the valid and expected input from user.

### Making Decisions In Your Code – Conditionals

1. **An if statement checks a __ and if it evaluates to ___, then the code block will execute.**

    condition, true

2. **What is the use of an else if?**

    To add conditions to check besides the initial "if" condition and the "else" condition.

3. **List 3 different types of comparison operators.**

    strict equality `===`, greater than and less than `<` `>`, and greater than or equal to and less than or equal to `<=` `>=`

4. **What is the difference between the logical operator && and ||?**

    `&&` is the logical "AND" operator, `||` is the logical "OR" operator

## Things I want to know more about

- When/why would you use HTML elements such as `<em>` and `<strong>` versus formatting content with CSS?
- Are internal stylesheets considered bad practice the same way inline styling is?
- How/when do you use switch statements and ternary operators?

## References

- [MDN: Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
- [MDN: HTML text fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
- [MDN: Advanced text formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)
- [MDN: How CSS is structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)
- [MDN: JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [MDN: Making decisions in your code — conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals#ternary_operator)
