# Read: 05 - Design web pages with CSS

## What is the purpose of CSS?

* CSS (Cascading Style Sheets) allows you to create great-looking web pages.
* Controls exactly how HTML elements look in the browser

## What are the three ways to insert CSS into your project?

1. **External CSS**
    * With an external style sheet, you can change the look of an entire website by changing just one file
    * Each HTML page must include a reference to the external style sheet file inside the link element, inside the head section
    * An external style sheet can be written in any text editor, and must be saved with a .css extension
    * The external .css file should not contain any HTML tags
1. **Internal CSS**
    * An internal style sheet may be used if one single HTML page has a unique style
    * The internal style is defined inside the style element, inside the head section
1. **Inline CSS**
    * An inline style may be used to apply a unique style for a single element
    * To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property

## Write an example of a CSS rule that would give all paragraph elements red text

`p {
    color: red;
}`