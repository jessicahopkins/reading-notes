# Read: Class 02

These topics are important because they review the basics of HTML and CSS and start to build on JavaScript fundamentals.

## Introduction to HTML (continued)

1. Why is it important to use semantic elements in our HTML?
    * Semantic elements, give the content the correct meaning based on our experience of what objects mean (how they function).
1. How many levels of headings are there in HTML?
    * There are 6 heading elements
1. What are some uses for the `<sup>` and `<sub>` elements?
    * `<sup>` = superscript
    * `<sub>` = subscript
    * Both are used in dates, math equations, etc.
1. When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?
    * The element `<abbr>` stands for abbreviation
    * The **title** attribute should be used for abbreviations that need more explanation

Sources:

[HTML text fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)

[Advanced text formating](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

## Learn CSS

1. What are ways we can apply CSS to our HTML?
    * External stylesheet
        * CSS is in a separate file with a .css extension
        * Most commonly used
        * reference using a `<link>` element in HTML file

    * Internal stylesheet
        * Contained in HTML
        CSS is inside a `<style>` element contained inside the HTML `<head>`
    * Inline styles
        * CSS declarations that affect as single HTML element, contained within a **style** attribute
        * Avoid using this method when possible, not best practice

1. Why should we avoid using inline styles?
    * Avoid using inline styles because it is the oppsite of best practice.  It's less efficient and more maintenance.  Also more difficult to read and understand.

1. Review the block of code below and answer the following questions:
    1. What is representing the selector?
        * The HTML element (h2 in this case)
    1. Which components are the CSS declarations?
        *CSS declarations are the property paired with a value (color: blue; and background-color: yellow; in this case)
    1. Which components are considered properties?
        * Properties indicate which style feature you want to change (color: and background-color: in this case)

Sources:

[How CSS is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

## Learn JS

1. What data type is a sequence of text enclosed in single quote marks?

* A String

1. List 4 types of JavaScript operators.
    * Additon (+)
    * Subtractions (-)
    * Multiplication (*)
    * Division (/)
    * Assignment (=) - Assigns a value to a variable

1. Describe a real world Problem you could solve with a Function.
    * Add numbers to get a sum

Sources:

[JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

## Making Decisions in Your Code - Conditionals

1. An if statement checks a __ and if it evaluates to ___, then the code block will execute.
    * Condition / True
1. What is the use of an else if?
    * When you want to include more than 2 choices
1. List 3 different types of comparison operators.
    * Comparison operators are used to test conditions inside conditional statements
        * Value is identical to or not indentical to another
        * Value is less than or greater than another
        * Value is less than or equal to or greater than or equal to another
1. What is the difference between the logical operator && and ||?
    * && = AND
    * || = OR

Sources:

[Making decisions in your code - conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

## Things I Want to Know More About

* Functions, functions, functions
* Conditionals - if...else statement
* Events
* Operators
