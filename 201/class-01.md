# Read: Class 01

The topics covered in this class are important for learning the basics of HTML, CSS and JavaScript which you need to know in order to build a basic website.

## Getting Started

1. Compose a short poem describing how HTTP sends data between computers.
    * HTTP's swift flow,
Data journeys to and fro,
Cyber rivers grow.
1. Describe how HTML, CSS, and JS files are “parsed” in the browser.
    * The browser looks at the HTML file first.  If the browser recognizes any `<link>` elements for CSS or `<script>` elements for JavaScript it sends requests back to the server.  The browser will build a DOM tree and CSSOM structure and execute the JavaScript which shows the page to the user.
1. How can you find images to add to a Website?
    * Search the web (i.e. Google Images), right click and image and Save As.
    * Note:  Be sure to make sure the image is not copyrighted.
1. How do you create a String vs a Number in JavaScript?
    * A string has single or double quotes around it.  A Number does not have quotes.  
1. What is a Variable and why are they important in JavaScript?
    * Variable are containers that store values.  They are important to make changes and/or do anything interesting in programming.

## Introduction to HTML

1. What is an HTML attribute?
    * An HTML attribute contains information about an element.  The attribute has a name and a value.  The attribute name is followed by an equal sign and the value is wrapped in quotation marks.  Ex: class="editor-note"
1. Describe the Anatomy of an HTML element.
    * An HTLM element has the following parts:
        * An opening tag - name of the element, wrapped in opening and closing angle brackets
        * A closing tag - same name as opening tag, it includes a forward slash before the element name
        * Content - content of element (i.e. text)
1. What is the Difference between `article` and `section` element tags?
    * A `section` element tag defines a grouping or section of content, often used to break content into logical chunks.  An `article` element typically defines independent content that stands alone
1. What Elements does a “typical” website include?
    * Header `<header>`
    * Navigation Bar `<nav>`
    * Main Content `<main>`
    * Sidebar `<aside>`
    * Footer `<footer>`
1. How does metadata influence Search Engine Optimization?
    * Metadata provides clear, relevant information to search engines, making pages rank better in search results, etc.
1. How is the `meta` HTML tag used when specifying metadata?
    * To specify metadata, name and content attributes are often used (i.e. Specify an author's name)

## Miscellaneous

### How to start to design a website

1. What is the first step to designing a Website?
    * Project Ideation - Asking yourself what you want to accomplish, what are the goals, what needs to be done and in what order
1. What is the most important question to answer when designing a Website?
    * "What exactly do I want to accomplish?"

### Semantics

1. Why should you use an `h1` element over a `span` element to display a top level heading?
    * An `<h1>` element automatically gives the "meaning" to the text that wraps around it of a "heading".  A `<span>`element doesn't have the semanic meaning of a heading but may look like one.
1. What are the benefits of using semantic tags in our HTML?
    * Influence search engines to mark the content as important
    *Screen readers use it to help visually impaired navigate page
    * Suggests type of data that will be populated
    * Mirrors proper element/component naming

### What is JavaScript?

1. Describe 2 things that require JavaScript in the Browser?
    * Any dynamic behavior like clicking a button, pop-ups, etc.
    * Geolocation - find your location, maps

1. How can you add JavaScript to an HTML document?
    * You would use the `<script>` element

## Things I want to know more about

* Using a sidebar element (HTML)
* DOM tree (parsed HTML)
* CSSOM structure (parsed CSS)
* Interpreted vs Compiled Code
* Continue to learn about functions like querySelectorAll
* Using addEventListener
