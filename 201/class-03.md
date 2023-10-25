# Read: Class 03

These topics are important because they review the basics of HTML and CSS and start to build on JavaScript fundamentals.

## Learn HTML - Ordered and Unordered lists

1. When should you use an unordered list in your HTML document?
    * Use unordered lists when the order of the list is meaningless and does not need a numerical ordering.
1. How do you change the bullet style of unordered list items?
    * Use the `type` attribute
1. When should you use an ordered list vs an unorder list in your HTML document?
    * Use an ordered list when you need the order to be ***meaningful*** for example when giving specific directions or following a recipe.
1. Describe two ways you can change the numbers on list items provided by an ordered list?

    * You can change the numbers by using attributes such as `start` and `type`.  You can also change them my nesting lists (ordered and unordered can be mixed)

Sources:

[Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

[The Ordered List element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

[The Unordered List element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

## Learn CSS - The Box Model

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
    * The story "The Box Model" is about a little moving box that got lost from it's family moving to a new home.  Inside it stored an expensive vase.
        * Padding is the newspaper that protects the expensive, fancy vase (content) that is packed neatly into the moving box.
        * The missing moving box gets found and is transported all by itself in a moving van.  The Margin would be the space between the little moving box and the moving van.
1. List and describe the four parts of an HTML elements box as referred to by the box model.
    * Content box - Area where content is displayed
    * Padding box - Padding sits around the content as white space.  Between content and border
    * Border box - Border box wraps the content and any padding
    * Margin box - Margin is the outermost later, wrapping the content, padding and boarder as whitespace between the box and other elements

Sources:

[Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

[The box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

## Learn JS - Arrays, Operators and Expressions, Conditionals, Loops

1. What data types can you store inside of an Array?
    * strings, numbers, objects, and other arrays
    * You can also mix data types in a single array
1. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
    * Yes, it is a valid array.  It's an array inside and array.  You can access it by chaining the square brackets together.
1. List five shorthand operators for assignment in javascript and describe what they do.
    * Assignment = the basic assignment operator. Assigns value to a variable
    * Addition assignment +=
    * Subtraction assignment -=
    * Multiplication assignment *=
    * Division assignment /=
1. Read the code below and evaluate the last expression and explain what the result would be and why.
    * Used Chat GPT for this one...
    * (a + c) attempts to add the value of a (which is 10) to the value of c (which is false). In JavaScript, when you add a number to a boolean, the boolean is implicitly converted to a number. false is equivalent to 0, and true is equivalent to 1 in numeric contexts. So, (a + c) evaluates to 10 + 0, which is 10.

    * Then, we add the string 'dog' to the numeric result (10). This operation performs type coercion and converts the number to a string and concatenates it with the string 'dog'. So, (a + c) + b results in the string '10dog'.

    * So, the final result of the expression (a + c) + b is the string '10dog'.
1. Describe a real world example of when a conditional statement should be used in a JavaScript program.
    * Weather App
1. Give an example of when a Loop is useful in JavaScript.
    * A loop is used to coplete repetitive tasks

Sources:

[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

[Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)

[Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

[Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

[Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

## Things I Want to Know More About

* Functions, functions, functions
* Loops
* Events
* Operators
