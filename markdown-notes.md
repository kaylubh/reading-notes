# Markdown

## About

### What is it?

Markdown is a lightweight markup language used to create simple, static documents or webpages. Markup formatting is added to text using a text or code editor which is then rendered to display the formatting. Markdown differs from a WYSIWYG (What You See Is What You Get Editor) since formatting is added directly in the text versus using tools to apply formatting to the content.

### Why use it?

Markdown is a flexible and independent method which can be used to create a variety of things such as websites, books, webpages, and documentation. Markdown can be used universally on any editor and can be easily displayed in multiple applications. Unlike documents created in other editors which are often created in a proprietary formats, documents created in Markdown are always viewable and readable even without the existence of a particular application.

## Syntax

### Headings

Headings are created using the `#` symbol in front of the text you want to create as a heading. There are 6 levels of headings, denoted by the number of `#` symbols in front of the text. The largest heading is created using one `#` symbol and the smallest heading is created using 6 `#` symbols.

>```markdown
># Heading
>```
>
>creates the largest heading:
>
># Heading
>
>```markdown
>###### Heading
>```
>
>creates the smallest heading:
>
>###### Heading

### Text

Text can be formatted in several different ways to bring attention to content or create a desired effect.

#### **Bold**

To make text bold you use either a double asterisk `**` or double underscore `__` before and after the text. While either method can be used, it is recommended to only use the double asterisks `**` because of the way some applications process underscores `__` might result in your content being displayed incorrectly.

>```markdown
>**Bolded Text**
>```
>
>**Bolded Text**

#### *Italics*

To make text italicized you use either an asterisk `*` or underscore `_` before and after the text. While either method can be used, it is recommended to only use the asterisk `*` because of the way some applications process underscores `_` might result in your content being displayed incorrectly.

>```markdown
>*Italicized Text*
>```
>
>*Italicized Text*

### Links

A link is created in two parts. First the content you want to be displayed for link is wrapped in square brackets `[]`. This is immediately followed by where the link should go wrapped in parentheses `()`. Do not add a space between the square brackets `[]` and parentheses `()` or it will be rendered as two separate strings of text instead of a link.

>```markdown
>[This is a link to this page](https://kaylubh.github.io/reading-notes/markdown-notes.html)
>```
>
>[This is a link to this page](https://kaylubh.github.io/reading-notes/markdown-notes.html)
>

### Lists

#### Unordered (Bulleted)

An unordered, or bulleted, list is created using the `-` dash, `*` asterisk, or `+` plus symbols and a space before the content on each bullet in the list.

>```markdown
>- Item 1   * Item 1    + Item 1
>- Item 2   * Item 2    + Item 2
>- Item 3   * Item 3    + Item 3
>```
>
>- Item 1
>- Item 2
>- Item 3

#### Ordered (Numbered)

An ordered, or numbered, list is created using a number and a period `1.` before the content.

>```markdown
>1. Item 1
>2. Item 2
>3. Item 3
>```
>
>1. Item 1
>2. Item 2
>3. Item 3
