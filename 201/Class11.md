# Class 11 Notes

# Video and Audio Content

1. Back in the early 2000s, online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. While it may have been cool back then, both technologies had security and accessibility issues which put them on the path to being obsolete. Nowadays native HTML solutions `<video>` and `<audio>` elements and the availability of JavaScript APIs for controlling them are used. Along with online video providers like YouTube and Dailymotion.

2. `src`: contains a path to the video you want to embed.

  `controls`: used to include the browser's own control interface, or build your interface using the appropriate JavaScript API.

3. Fallback content will be displayed if the browser accessing the page doesn’t support the `<video>` element. So you can provide a direct link to the video file or message explaining that their browser can’t run the content.

4. Roses are red, violets are blue, `<audio>` lets you hear content, while `<video>` shows it to you.

## A Complete Guide To Grid

1. Flex was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time.

2. `Grid Container`: The element on which `display:` grid is applied. It’s the direct parent of all the grid items.

 `Grid Item`: The children (i.e. direct descendants) of the grid container.

 `Grid Line`: The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.

## Responsive Images

1. It helps deliver optimal file size, the right image for the right screen size, improves user experience and improves loading time.

2. `srcset`: Defines the set of images we will allow the browser to choose between, and what size each image is. For example, it specifies the URL of the image to use in different situations.

  `sizes`: Defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose. So it specifies the sizes of an icon for visual media.

3. When the browser starts to load a page, it starts to download (preload) any images before the main parser has started to load and interpret the page's CSS and JavaScript. That mechanism is useful in general for reducing page load times, but it is not helpful for responsive images — hence the need to implement solutions like `srcset`.

## Things I want to know more about

- Would like to play around with implementing multimedia to a website.
