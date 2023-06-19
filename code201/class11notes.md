# Video and Audio Content

## 1. Explain how the ability to use video and audio on the web has evolved since the early 2000s

Using video and audio on the web has changed since the early 2000s. Initially, Flash was commonly used, but now HTML5 provides native support for video and audio without the need for plugins. This has made it easier to play media on different devices and improved compatibility. There are more video and audio formats available, and streaming technologies have enhanced the quality of online media. JavaScript tools allow developers to control and manipulate video and audio elements. Mobile optimization techniques ensure better experiences on smartphones and tablets. Accessibility standards have also been emphasized, making multimedia content more inclusive with features like captions and audio descriptions. Overall, these advancements have made using video and audio on the web more accessible, compatible, and enjoyable.

## 2. Describe the use of the `src` and `controls` attributes in the `<video>` element

The "src" attribute in the `<video>` element is used to specify the video file's location or URL that should be displayed on the web page.

The "controls" attribute in the `<video>` element enables the default video player controls, allowing users to play, pause, adjust volume, and navigate through the video without any additional coding.

## 3. Why is it important to have fallback content inside the `<video>` element?

Fallback content is important in the `<video>` element because it ensures that users can still access information or alternative media if the video cannot be played. It improves accessibility and provides a better user experience.

## 4. Write a very short story where `<audio>` and `<video>` are characters

Once upon a time, Audio and Video were inseparable companions. Audio enchanted with its melodious tunes, while Video mesmerized with captivating visuals. Together, they added magic and emotion to our lives, reminding us of the power of sound and image in creating unforgettable experiences.

# A complete guide to grid

## 1. How does Grid layout differ from Flex?

Grid layout and Flexbox are different CSS layout systems. Grid layout focuses on creating grid-based layouts with rows and columns, offering precise control. Flexbox is used for arranging elements along a single axis, allowing flexibility and responsiveness.

## 2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences

In Grid layout, the grid container is like a box that holds the grid items. The grid items are the elements inside the container, and they are positioned and aligned within the grid. Grid lines are the lines that form the grid, helping to define the rows and columns where the grid items are placed.

# Responsive Images

## 1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

Developers should make images responsive to improve user experience, optimize page load times, and ensure accessibility across different devices.

## 2. Define the following  `<img>` attributes `srcset` and `sizes`. Write an example of how they are used

The `srcset` attribute in the `<img>` tag provides a list of image sources with their respective sizes or descriptors. It helps the browser choose the best image to display based on the device's capabilities. The `sizes` attribute defines the conditions for different image sizes based on the screen width. It allows the browser to determine the appropriate image to load.

EX.

```javascript
<img src="small.jpg" 
     srcset="small.jpg 300w, medium.jpg 600w, large.jpg 1200w"
     sizes="(max-width: 600px) 300px, 600px">
```

## 3. How is srcset more helpful for responsive images than CSS or JavaScript?

The `srcset` attribute is better for responsive images because it allows the browser to automatically choose the right image based on the device, optimizing network efficiency and providing a browser-native solution without the need for extra CSS or JavaScript.
