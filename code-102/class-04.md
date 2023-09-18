# HTML Basics

HTML is an abbreviation for **H**yper **T**ext **M**arkup **L**anguage. HTML is a markup language used to define the structure of content, most commonly in webpages. HTML is made up of elements which are markup that is wrapped around content to define it's structure, functionality, and basic appearance.

## HTML Element

An HTML element consists of three parts: the *opening tag*, the *content*, and the *closing tag*. The *opening tag* in an element is enclosed with angle brackets `<>`, while the *closing tag* uses the same brackets with a forward slash `</>`. An example of a paragraph `<p>` element:

```html
<p>This is a paragraph element</p>
```

`<p>` is the *opening tag*, `This is a paragraph element` is the *content*, and `</p>` is the *closing tag*.

## HTML Attributes

Elements can also contain attributes, which are sometimes required or optional. Attributes provide additional information about the element and might be necessary for the element to function or the element might modify the content in the element. Attributes are placed in the *opening tag* of an element. In an example of the link `<a>` element, an attribute of `href` needs to be defined for it to function properly:

```html
<a href="https://www.google.com">Link to Google</a>
```

The `<a>` tag creates the link element but without the extra information provided by the `href` attribute the link would not actually point to Google.

## Semantic Elements

Semantic elements are used to help define the meaning or purpose of a particular part of code. For example, the Header 1 `<h1>` tag tells us this is the most important header in the content. The body `<body>` tag tells us this is the main body of the content.

Many semantic elements will have no impact on the appearance or functionality of the content within it but are rather used to improve the organization and readability of the code. Semantic elements also help improve the accessability of the content for things like screen readers and are also used by search engines to help index the content.

Some examples of semantic elements are `<article>`, `<footer>`, `<main>`, and `<summary>`.
