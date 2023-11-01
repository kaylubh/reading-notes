# CSS Layout

## Learn CSS - Flexbox

1. **Flexbox is designed for one-dimensional content. Explain what this means.**

    Flexbox allows you adjust the size and location of content along one axis on the page. You can adjust how content is displayed on rows or how it is displayed in columns but not both. This means if you have content on two separate rows you cannot align the content between both rows because it would be a second dimension.

2. **Explain the difference between the main axis and cross axis.**

    The main axis and cross axis will either be row or column. When working with flexbox you set your main axis using the `flex-direction` property or the default it row, in this case the cross-axis would then be column. You can only affect how items are displayed along the main axis.

3. **How can using certain properties of flexbox negatively impact accessibility?**

    Certain properties like `flex-direction` when using `row-reverse` and `column-reverse` and the `order` property affect how content is displayed on screen without changing the order of the content in the HTML. How content is structured in HTML is how the content will be provided to assistive devices such as screen readers. If there is a disconnect between this structure and the display of the content this can create challenges with navigating a page.

## CSS Layout - Flexbox

1. **What are some advantages of using flexbox over float?**

    Using flexbox makes it much easier to achieve certain layouts that require vertically centering content or resizing content to be of equal size across a page regardless of the viewport.

2. **How does this topic connect with your long term goals?**

    This topic connects with my long term goals to learn more about and become a developer because flexbox is a modern CSS technique used to help build well-designed and responsive web pages.

## Things I want to know more about

- How to control when content should "wrap" when using flexbox

## References

- [web.dev: Flexbox](https://web.dev/learn/css/flexbox/)
- [MDN: Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
- [web.dev: Layout](https://web.dev/learn/css/layout/)
