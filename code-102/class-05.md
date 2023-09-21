# CSS Basics

CSS or ,**C**ascading **S**tyle **S**heets, is a language used to modify the presentation of HTML. CSS is used to affect the style and layout of HTML and can even be used to create effects such as animations. A CSS file is made up of rules which specify how the HTML is presented.

## Adding CSS

CSS can be added to your HTML in three ways:

### External CSS

External CSS is the most common, and preferred method, to add CSS to your project. CSS rules are written in an independent CSS file which is linked to the HTML it will affect. In order for the CSS to affect the HTML you will need to link the external style sheet to the HTML:

```html
<head>
<link rel="stylesheet" href="style.css">
</head>
```

The `href` attribute's value will be the name and path to the CSS file you want to use. The `<link>` element should be placed in the `<head>` of the HTML page.

### Internal CSS

Internal CSS is used to create an internal style sheet within an HTML file. While ***External CSS*** is the preferred method, ***Internal CSS*** could be used to create a unique style for a particular HTML page. Internal CSS rules will override any CSS rules that affect the same elements from an external CSS file. To add internal CSS you add a `<style>` element within the `<head>` of an HTML page:

```html
<head>
    <style>
        h1 {
            color: red;
        }
    </style>
<head>
```

### Inline CSS

The last and least commonly used method is ***Inline CSS***. While ***External CSS*** is the preferred method, ***Inline CSS*** could be used to create a unique style for a specific and singular element. A better method to achieve the same result would be to assign the individual element a unique `id` attribute which can then be selected using a CSS rule in an external style sheet. Inline CSS rules will override any CSS rules that affect the same elements from all other CSS rules including an external CSS file and internal CSS. Inline CSS is added in a `style` attribute within the element:

```html
<body>
    <h1 style="color:red;">Heading</h1>
</body>
```

## CSS Rules

CSS is a rule-based language in which you define the rules by creating style(s) that will be applied to particular elements on an HTML page. 

### Selectors

CSS rules begin with a selector which selects, or specifies, which elements it will affect. A selector could be an element `h1`, an element class `.class`, or an element id `id`. There is also a wildcard selector `*` used to select all elements. Selectors can be combined to further specify which elements to style.

### Property:Value Declarations

After specifying the selector in a CSS rule and a set of curly braces `{}` to hold the declaration(s), you will use property:value pairs to declare how to style the element(s). First you specify the ***property*** followed by a colon `:` to separate it from the ***value***. Lastly, all declarations ended with a semicolon `;` to separate it from other declarations.

### Putting It All Together

```css
p {
    color: red;
    text-align: center;
}
```
