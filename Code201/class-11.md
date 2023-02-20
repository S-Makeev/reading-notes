# Readings: Audio, Video, Images

**-Explain how the ability to use video and audio on the web has evolved since the early 2000s.**

The ability to use audio and video rose exponentially thanks to plugin-based technologies, such as Flash and Silverlight. At this point, both of them become obsolete. 

**-Describe the use of the src and controls attributes in the `<video>` element.**

The src attribute allows to set the link to the video file itself, while controls allows to apply basic way for a user to control video via simple interface. 

  
**-Why is it important to have fallback content inside the `<video>` element?-**

Because if a browser doesn't support video element, user would still be able to access the link directly. 

**-Write a very short story where `<audio>` and `<video>` are characters.**

In order to make it to the other side of the river where the port was, audio and video had to row at the same time.

**-How does Grid layout differ from Flex?**

Flex container can wrap and move down independently of the row above, while grid while wrapping, will mirror behaviour of the elements above. Flex is one dimensional, while Grid is two dimensional. Grid is mostly defined on the parent element, while in flexbox most of the layout happens on the parent element. 


**-Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**

Grid container - The element on which the grid is applied and it's a parent of all grid items. 
Grid item - the children of the grid container.We'll find the item elements, but not sub-items.
Grid line - lines that divide the grid vertically or horizontally making up the structure of the grid. 

**-Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**

So that we can save the bandwidth for our users by offering them variants of file sizes that will be used, depending on the device they have.

**-Define the following `<img>` attributes srcset and sizes. Write an example of how they are used.**

srcset provides a browser with a list of images and their parameters. sizes - defines certain conditions what image size will be used based of the current conditions. 

**-How is srcset more helpful for responsive images than CSS or JavaScript?**

> When the browser starts to load a page, it starts to download (preload) any images before the main parser has started to load and interpret the page's CSS and JavaScript. That mechanism is useful in general for reducing page load times, but it is not helpful for responsive images — hence the need to implement solutions like srcset

