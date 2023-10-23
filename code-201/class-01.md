# Readings Overview

These notes provide a quick overview of the technologies that make up web development and how to begin creating a website.

## Getting Started

1. **Compose a short poem describing how HTTP sends data between computers.**

    > HTTP
    >
    > At *Hyper* speed, as fast as light, the *Text* and all its friends, begin their *Transfer* to the future, only to repeat the *Protocol* again when it arrives

2. **Describe how HTML, CSS, and JS files are “parsed” in the browser.**

    The browser parses the entirety of the HTML. As it is parsing the HTML, it requests the CSS and JS files which are linked in the HTML. The browser then parses all the CSS before parsing and executing the JS files.

3. **How can you find images to add to a Website?**

    You can find images to add to a website by using [Google Images](https://images.google.com/). When searching for images you should filter the results to exclude copyrighted images. On Google Images, select "Creative Commons licenses". Another useful image resource is [Unsplash](https://unsplash.com/).

4. **How do you create a String vs a Number in JavaScript?**

    To create a string in JavaScript, surround the content in single or double quotes. Do not use any quotes around a number for it to be considered a number by JavaScript.

5. **What is a Variable and why are they important in JavaScript?**

    Variables are containers used to store values in JavaScript. Variables enable you to have dynamic content using JavaScript.

## Introduction to HTML

1. **What is an HTML attribute?**

    Attributes provide additional information about the element and might be necessary for the element to function or the attribute might modify the content in the element.

2. **Describe the Anatomy of an HTML element.**

    An HTML element consists of three parts: the opening tag, the content, and the closing tag. The opening tag in an element is enclosed with angle brackets `<>`, while the closing tag uses the same brackets with a forward slash `</>`.

3. **What is the Difference between `<article>` and `<section>` element tags?**

    An `<article>` is used to enclose content which makes sense by itself. A `<section>` is used to enclose a group of content that is related. It is best practice to begin a `<section>` with a heading.

4. **What Elements does a “typical” website include?**

    A typical website will include the header `<header>`, navigation `<nav>`, main content `<main>`, sidebar `<aside>`, and footer `<footer>` elements.

5. **How does metadata influence Search Engine Optimization?**

    Information in the metadata is used to help create the descriptions displayed in search engine results. Additionally, the metadata helps the search engine determine how well the website matches the users search.

6. **How is the `<meta>` HTML tag used when specifying metadata?**

    The `<meta>` tag is used in the `<head>` of an HTML file to provide additional information about the content of a page.

## Miscellaneous

### How to start to design a Website

1. **What is the first step to designing a Website?**

    The first step of designing a website is *project ideation*. The what, how, and why of a website.

2. **What is the most important question to answer when designing a Website?**

    The most important question to answer is ***what you want your website to accomplish***.

### Semantics

1. **Why should you use an `<h1>` element over a `<span>` element to display a top level heading?**

    When creating a heading, the `<h1>` element makes the code more readable, provides context for SEO, and helps improve the accessability of a site. Simply using a `<span>` element provides no information about the purpose of the content in the element which can contribute to making code difficult to read in addition to not providing the other aforementioned benefits of using an appropriate semantic element.

2. **What are the benefits of using semantic tags in our HTML?**

    Semantic elements help make code more readable for developers, especially developers other than the original author. They also help search engines understand a website's structure better and improve SEO. Using semantic elements can also make a page more accessible for users navigating a page with tools such as a screen reader.

### What is JavaScript?

1. **Describe 2 things that require JavaScript in the Browser?**

    JavaScript is required to add most dynamic functionality to a page loaded in a browser. Some examples of this could include processing user input and displaying content based on specified conditions.

2. **How can you add JavaScript to an HTML document?**

    JavaScript can be added to an HTML document in a similar manner as CSS is added: external, internal, and inline. External and internal JS is added using the `<script>` element while inline JS is added as an attribute to an HTML element.

## Things I want to know more about

- What is the industry standard for the typical elements in a webpage?
- What information should be in the `<meta>` section and what types of metadata are deprecated?
- When and how should I use the "defer" and "async" keywords when adding a JS file via the `<script>` element?

## References

- [MDN: Getting started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)
- [MDN: How the web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- [MDN: What will your website look like?](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
- [MDN: JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [MDN: Getting started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)
- [MDN: Document and website structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
- [MDN: What's in the head? Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)
- [MDN: How do I start to design my website?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Design_and_accessibility/Thinking_before_coding)
- [MDN: Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- [MDN: What is JavaScript?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
