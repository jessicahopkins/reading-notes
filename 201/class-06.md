# Read: Class 06

These topics are important because they teach you how to add styling and life to websites.  Make websites more appealing to the user.

## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?
    * ***Example provided by ChatGPT:***

Imagine a JavaScript object like a digital backpack that you can use to carry around different items. In this digital backpack, you can store all kinds of things, just like you do in a real backpack.

Each item you put in this digital backpack has two parts: a label and the actual thing itself. The label helps you find and organize your stuff. For example, you might have a label called "water bottle" for your water bottle, and another label called "book" for your book. These labels are like the names of the items in your digital backpack.

Now, here's the cool part: you can not only store regular things like water bottles and books but also more complex things like a bunch of smaller bags inside your backpack. These smaller bags can have their own labels and contain even more stuff.

In JavaScript, these labels are called "properties," and the things inside your digital backpack are called "values." You can use the labels to find and access the values. So, if you want to get your water bottle from your digital backpack, you'd look for the "water bottle" label, and you'll find the water bottle as the value associated with that label.

Objects in JavaScript are like these digital backpacks, where you can keep things organized with labels (properties) and store different types of stuff (values) all in one place. It's a handy way to keep track of information and organize it just like you would with a real backpack.

2. What are some advantages to creating object literals?
    * More efficient as you are sedning a single object versus sending several items individually
    * Easy to create and understand (you define an object by placing key-value pairs inside curly braces) as code is more concise and readable.
1. How do objects differ from arrays?
    * Objects use the name associated with each member's value instead of the index number to access items.
1. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
    * If an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation.
1. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
    * "This" refers to the dog (object)
    * The advantage is that you can reuse the code.  It makes i easy to work with multiple instance of similar objects.

Sources:

[JavaScript object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

## Introduction to the DOM

1. What is the DOM?
    * Document Object Model (DOM) is a programming inerface for web documents.  It represents the page so that programs can change the document structure, style, and content.
1. Briefly describe the relationship between the DOM and JavaScript.
    * DOM is the webpage and JavaScript interacts with the DOM to update or change web content and behavior.  They work together to create web pages and applications.

Sources:

[Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

## Bookmarks

[Understanding the problem domain is the hardest part of programming](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

[What's the difference between Primitive Values and Object References in JavaScript](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

## Things I Want to Know More About

* DOM
* Objects
    1. properties
    2. methods
    3. proper syntax
