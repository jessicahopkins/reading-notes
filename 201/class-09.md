# Read: Class 09

Web forms are important because they are a powerful tool for interacting with users on a website.  They collect data and allow the user to interact with the user interface.

## HTML Forms

1. Why are forms so important in web development?
    * Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data and interact with the user interface.
1. When designing a form, what are some key things to keep in mind when it comes to user experience?
    * Keep it simple
    * Use clear labels
    * Arrange fields in logical order
    * Use proper spacing
    * Error handling
1. List 5 form elements and explain their importance.
    * Form element - All forms start with this element.  It formally defines a form (added to body).
    * Label element -labels the text entry field
    * Input element - a field where text is entered (i.e. single-line text, email input fields)
    * Textarea element - a multi-line text field (i.e. for a message)
    * Button element - allow users to send or submit data

Sources:

[Web Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

[Your First Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

[How to Structure a Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

## Learn JS - Intro to Events

1. How would you describe events to a non-technical friend?
    * Answer courtesy of ChatGPT
    * Sure, I'd describe JavaScript events to a non-technical friend like this:

"Imagine you're throwing a party, and you want to make it fun for your guests. You plan different activities and games for them to enjoy. In the world of websites and apps, JavaScript events are like those planned activities.

Think of a web page or app as a big party where things happen. Events in JavaScript are like triggers that start these things. They can be compared to invitations to different activities at your party.

For example, when someone clicks a button on a website, it's like your friend saying, 'Hey, I want to play a game!' That click is an event, and JavaScript helps you respond to it. You can make something happen, like showing a message or playing a video, when that event occurs.

Events can also be like your party's schedule. You plan when each activity or game starts. JavaScript helps you set up a schedule for what should happen when certain events occur. It makes your website or app interactive and engaging, just like planning a fun party for your friends."

2. When using the addEventListener() method, what 2 arguments will you need to provide?
    * Event Type (or Event Name) - This is a string that tells what kind of an event you want to listen for (i.e. click, submit, mouseover)
    * Event Listener - This is a JS function that you want to be executed when the even occurs
3. Describe the event object. Why is the target within the event object useful?
    * Answer courtesy of ChatGPT:

The ***event object in JavaScript is an object that contains information about an event that has occurred, such as a user's interaction with a web page. It provides details about the event, including the type of event, the target element that triggered the event, and additional data related to the event.*** The event object is automatically passed to event handler functions when an event occurs.

One key property of the event object is event.target. This property is especially useful because it refers to the DOM element that triggered the event. Here's why the target property within the event object is useful:

Identification of the Triggering Element:

The ***target property allows you to identify the specific element that was interacted with, whether it's a button, a link, an input field, or any other HTML element.
This is essential for knowing which part of the page the event originated from and enables you to respond appropriately.***
Dynamic Event Handling:

It's helpful for dynamically generated content or elements. You can set up event listeners on a parent container and use event.target to determine which child element was clicked. This is useful when elements are added or removed from the page dynamically.
Delegation:

Event delegation is a technique where you attach a single event handler to a common ancestor of multiple elements and then use event.target to figure out which specific element triggered the event. This reduces the number of event listeners and can improve performance.

4. What is the difference between event bubbling and event capturing?
    * Summary via ChatGPT

The key differences between event bubbling and event capturing are:

Event Bubbling:

Starts at the target element and bubbles up to the root of the document.
Default behavior for most DOM events.
Innermost (target) element's event handler is executed first, followed by ancestor elements.
Allows catching events on specific elements before handling them at higher levels.
Event Capturing (or Trickling):

Starts at the root of the document and trickles down to the target element.
Less commonly used but can be helpful for intercepting events at higher levels before reaching the target.
Event handlers on elements higher in the hierarchy are invoked first, followed by the target element.

Sources:

[Intro to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

## Bookmarks

[HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

[Event Reference](https://developer.mozilla.org/en-US/docs/Web/Events)

## Things I Want to Know More About

* Practice creating and syling a form and buttons
