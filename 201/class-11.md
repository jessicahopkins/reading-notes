# Read: Class 11

These topics are important because they help you add life to a website and introduce HTML that allow you to do that and CSS techniques (GRID) to design your website.  Also, what it takes to make a website responsive and have a great user experience.

## Audio, Video, Images

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
    * In the past third-party plugins (i.e. Flash, Silverlight) were the popular platfor for delivering audio/video to the web.  However, they became outdated and have security concerns.  HTML Native support became the go to.
    * Content Delivery Networks (CDN's) improved delivery of multimedia contents.  They reduce latency and stream videos faster.  Think Netflix, YouTube, Spotify.
1. Describe the use of the src and controls attributes in the `<video>` element.
    * The src attribute specifices the URL or path to the video, the same as with images.
    * The controls attribute, adds a set of built-in control buttons to play the video player (play, pause, volume control)
1. Why is it important to have fallback content inside the `<video>` element?
    * It is important to include fallback content inside the `<video>` element for several reasons, primarily to ensure a positive user experience and compatibility in situations where the video cannot be displayed or played as intended. Fallback content provides a backup solution.
1. Write a very short story where `<audio>` and `<video>` are characters.
    * Story provided courtesy of ChatGPT:

Once upon a time in the digital realm, there lived two curious characters named Audio and Video. They were inseparable friends, always found side by side.

Audio had a melodious voice and a knack for storytelling. Video, on the other hand, had a captivating visual presence and could bring any tale to life.

One day, they decided to embark on an adventure to entertain the people of the internet. Audio started narrating a thrilling story, setting the stage with words that painted vivid pictures in the listeners' minds.

As Audio spun the narrative, Video jumped in, using its magical powers to create a breathtaking visual spectacle that mirrored the words of the story. Together, they transported their audience to distant lands, through epic battles, and into the hearts of the characters.

Their partnership was truly enchanting, and they received praise and adoration from the online world. Audio and Video became a dynamic duo, proving that the perfect harmony of sound and visuals could capture the imagination and touch the soul.

And so, their adventures continued, with Audio's words and Video's visuals weaving captivating tales for all to enjoy in the vast digital realm.

Sources:

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

## A Complete Guide to Grid

1. How does Grid layout differ from Flex?
    * Grid is two-dimensional while flex is one-dimensional
    * Grid is used to create layouts that are both horizonal and vertical while Flex is best for layouts along a single axis (row or column but not both at same time)

1. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
    * Grid Container - An HTML element (parent container) that you designate as a grid by applying the `display: grid;` property in CSS.  It is the container for all grid items within it.
    * Grid Item - An HTML element that is a direct child of a grid container and becomes part of the layout.  Grid items are positioned within rows and columns of the grid.
    * Grid Line - Grid lines are the horizontal and vertical lines that define the boundaries of rows and columns within the grid container.

Sources:

[A Coplete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
    * Making images responsive on a website is not only about visual appeal but also about ensuring a better user experience, improved performance, and search engine optimization.
1. Define the following `<img>` attributes srcset and sizes. Write an example of how they are used.
    * srcset - The srcset attribute allows you to provide a list of image files, each with different resolutions or sizes. Browsers use this list to choose the most suitable image to display, based on the user's device capabilities and screen size.
    * sizes - The sizes attribute specifies the size of the image element concerning the viewport width and, optionally, the image's layout. It provides hints to the browser regarding how much space the image will occupy in the layout.
1. How is srcset more helpful for responsive images than CSS or JavaScript?
    * While CSS and JavaScript can also be used to implement responsive images, they often involve more manual effort, custom coding, and potential pitfalls, such as browser inconsistencies and additional load times. srcset streamlines the process and ensures that responsive images are handled efficiently, making it the preferred choice for many web developers when optimizing images for different screen sizes and devices.

Sources:

[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

## Bookmarks

[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

[Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)

## Things I Want to Know More About

* Adding a video to a website
* Demo of Grid in action and playing with it
