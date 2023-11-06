# Audio, Video, Images

## Video and Audio Content

1. **Explain how the ability to use video and audio on the web has evolved since the early 2000s.**

    Adding video and audio content to web pages was initially only possible with the use of plugins like Adobe Flash which were additional software a user had to download outside of the browser. These tools presented security and accessibility issues in addition to restricting content to proprietary formats in many cases. These technologies are no longer supported, being replaced by support for video and audio content to be included directly in the browser.

2. **Describe the use of the src and controls attributes in the `<video>` element.**

    The `src` attribute is required to set a source of the video file but can also be used on a `<source>` tag nested in the `<video>` element to specify multiple different sources to provided wider browser/device support. The `controls` attribute adds controls to the video content by using the controls built-in to the browser or device accessing the video.

3. **Why is it important to have fallback content inside the `<video>` element?**

    Some users, especially with older browsers, might not support the `<video>` element or the format(s) of the video element may not be supported by the browser/device. Fallback content provides alternative content to display in place of the video similar to the `alt` attribute functionality for images. Fallback content can describe the content the user cannot access or provide an alternative way to access the video.

4. **Write a very short story where `<audio>` and `<video>` are characters.**

    `<audio>` and `<video>` are two friends who like to share their stories with the world. Audio likes to tell his stories with lots of words on a small stage (audio player). `<video>` likes to tell her stories with many words and a whole bunch of moving pictures on a bigger stage (video player).

## A Complete Guide To Grid

1. **How does Grid layout differ from Flex?**

    Grid is used to layout content on two dimension unlike Flex which is used to layout content on one dimension.

2. **Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**

    - Grid Container: The grid container is the parent element of all the content you want to be in the grid. It is the element which has its CSS `display` property set to grid.
    - Grid Item: These are the child elements of the parent container. It does not include elements inside these child elements.
    - Grid Line: A grid line is one of the lines which divides the grid either vertically or horizontally.

## Responsive Images

1. **Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**

    Using responsive image practices can also result in only the correct image file being downloaded, potentially increasing performance speed and reducing bandwidth. These benefits can be especially helpful on mobile devices.

2. **Define the following `<img>` attributes srcset and sizes. Write an example of how they are used.**

    - `srcset` is an attribute used to specify the set of images that the browser will choose between when loading page. It lists each image file and the width of of each image.
    - The `sizes` attribute is used to set the different conditions, such as screen widths, to specify which image would be the best load on a page.

3. **How is srcset more helpful for responsive images than CSS or JavaScript?**

    By using `srcset` you only load one image, and potentially a smaller image, when the page loads instead of multiple files or a bigger file than needed.

## Things I want to know more about

- How using the default browser controls or embedding video from hosting like Vimeo and YouTube affects compatibility and the user experience
- Common uses of the `srcset` and `sizes` attributes with images

## References

- [MDN: Video and audio content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
- [CSS-Tricks: A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [MDN: Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
- [MDN: Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
- [MDN: From object to iframe — other embedding technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)
