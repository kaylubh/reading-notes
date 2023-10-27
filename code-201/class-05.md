# Images, Color, Text

## HTML Media

1. **What is a real world use case for the alt attribute being used in a website?**

    The text in the `alt` attribute is used by screen readers to describe images to visually impaired users. The attribute also provides alternative content in the images place should there be an issue preventing the image from being displayed.

2. **How can you improve accessibility of images in an HTML document?**

    You can improve accessibility by always including the `alt` attribute if an image is not decorative. Also use `<figure>` and `<figcaption>` with images to help improve readability. Lastly, don't use the `title` attribute because it is not accessible by screen readers or users with keyboard only input.

3. **Provide an example of when the figure element would be useful in an HTML document.**

    The `<figure>` element is useful when combining an image with a caption or grouping together related content.

4. **Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.**

    An image in GIF format is best used to show images which are simple and do not need to be resized, it is also popular when displaying simple animations. An image in SVG format is best used to display illustrations or graphics, rather than photos, especially when you want to display them at different sizes.

5. **What image type would you use to display a screenshot on your website and why?**

    I would use a PNG because it has wide support, is a preferred format for image reproduction such as screenshots, and is generally a smaller file size than some other formats.

## Learn CSS: Using Color in CSS, Styling HTML Text Elements

1. **Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.**

    Foreground colors are the ones at the front of an element for example in an element with text it would be the text itself. Background colors are the ones that makeup the whole element such as the entire height and width of a paragraph.

2. **Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?**

    I would use color to add a background to make the text stand out more. I would also use color to add accents to things like navigation, links, pictures, and other elements which are distinct from the primary blog content.

3. **What should you consider when choosing fonts for an HTML document?**

    You should consider the readability of the font as well as its support across different devices and browsers.

4. **What do font-size, font-weight, and font-style do to HTML text elements?**

    - `font-size` is used to set the size of text in an element
    - `font-weight` is used to make text bold
    - `font-style` is used to italicize text

5. **Describe two ways you could add spacing around the characters displayed in an h1 element.**

    You could add spacing by using the `line-height` property. You could also adjust the `padding` and `margin` properties of the element or its parent container.

## Things I want to know more about

- How widely used are new image file formats such as APNG, AVIF, and WebP?
- What are some good tools for picking colors?

## References

- [MDN: Multimedia and embedding](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)
- [MDN: Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
- [MDN: Image file type and format guide](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)
- [MDN: Learn to style HTML using CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
- [MDN: Applying color to HTML elements using CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)
- [MDN: Fundamental text and font styling](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)
