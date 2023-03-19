# Class 11 Notes

## **Audio, Video, Images**

### [*Video and Audio Content*](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

- Explain how the ability to use video and audio on the web has evolved since the early 2000s.

    > Back then they required a plug-in like Flash and Silverlight but are now obsolete.

- Describe the use of the src and controls attributes in the `<video>` element.

    > src contains path to the video whilst controls brings up the rewind, play, pause and stop.

- Why is it important to have fallback content inside the `<video>` element?

    > In case the video doesnt load, the user will know what was suppose to be there.

- Write a very short story where `<audio>` and `<video>` are characters.

    > Audio meets video. They fall in love. They benefit each other and produce more than they ever could alone.

### [*A Complete Guide To Grid*](https://css-tricks.com/snippets/css/complete-guide-grid/)

- How does Grid layout differ from Flex?

    > Grid is two-dimensional while Flex is one-dimensional.

- Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

    > The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container is the grid container.

    > The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.

    > The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.

[*Responsive Images*](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

- Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

    > Keep content in its place.

- Define the following `<img>` attributes `srcset` and `sizes`.

    > The standard `<img>` element traditionally only lets you point the browser to a single source file. We can however use two attributes — `srcset` and `sizes` — to provide several additional source images along with hints to help the browser pick the right one.

- Write an example of how they are used.
How is `srcset` more helpful for responsive images than CSS or JavaScript?

    1. Look at its device width.

    1. Work out which media condition in the sizes list is the first one to be true.

    1. Look at the slot size given to that media query.

    1. Load the image referenced in the srcset list that has the same size as the slot or, if there isn't one, the first image that is bigger than the chosen slot size.

----

❗❗❗ **Bookmark and Review** ❗❗❗

[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

> This article is review from Class 05.

[Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)