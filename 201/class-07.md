# Read: Class 07

These topics are important because they teach you how to add styling and life to websites.  Make websites more appealing to the user.

## Domain Modeling

1. Explain why we need domain modeling.
    * Domain modeling can validate the understanding of a problem among various stakeholders.  It also defines vocabulary that can be used within and between both technical and business teams.

Sources:

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

## HTML Table Basics

1. Why should tables not be used for page layouts?
    * Layout tables reduce accessibility for visually impaired users.
    * Tables produce tag soup
    * Tables are not automatically responsive
2. List and describe 3 different semantic HTML elements used in an HTML <table>.
    * Caption - provides a title or description for the table
    * th - define header cells within the table
    * thead, tbody, tfoot - elements are used to divide the table into primary sections

Sources:

[HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

## JavaScript Object Basics - Introducing Constructors

1. What is a constructor and what are some advantages to using it?
    * A constructor is a special method in object-oriented programming that is used to initialize and setup the initial state of an object when it is created.  
1. How does the term this differ when used in an object literal versus when used in a constructor?
    * When you use this within an object literal, it typically refers to the object itself. It represents the current instance of the object you are defining. 
    * When you use this in a constructor function, it refers to the object being created by that constructor. Constructors are typically used to create instances of a particular type or class.
1. Explain prototypes and inheritance via an analogy from your previous work experience.
    * Example courtesy of ChatGPT
    * Analogy: The Office Hierarchy

Imagine you work in a corporate office with a hierarchical structure. In this setting, you can use the office hierarchy as an analogy for prototypes and inheritance in programming.

Objects as Employees:
Think of objects in programming as employees in the office. Each employee has their own set of skills and responsibilities.

Prototypes as Job Descriptions:
Now, consider prototypes as job descriptions. Job descriptions define the common responsibilities and skills required for a particular role in the office. For example, you might have a "Manager" job description, a "Developer" job description, and so on. Each job description outlines what that role should be capable of doing.

Inheritance as Promotions:
Inheritance can be likened to promotions within the office. When an employee gets promoted, they inherit not only the responsibilities of their new role but also all the responsibilities of their previous role. For instance, if a "Developer" gets promoted to a "Team Lead," they now have both the responsibilities of a "Team Lead" and a "Developer." This reflects how inheritance allows objects to inherit properties and behaviors from their prototypes.

Overriding as Customization:
Sometimes, employees may customize their job responsibilities to suit their specific needs or to better align with the new role. This customization is like method overriding in programming, where an object can provide its own implementation of a method inherited from a prototype.

Here's how this analogy relates to prototypes and inheritance:

Prototype: The job descriptions (e.g., "Manager" or "Developer") serve as prototypes. They define the common properties (responsibilities and skills) for employees in those roles.

Inheritance: When an employee is promoted, they inherit the job description of their new role. This mirrors how objects inherit properties and methods from their prototypes.

Overriding: If an employee customizes their responsibilities or skills, it's like method overriding in programming, where an object provides its own implementation of a method.

Just as in programming, this office analogy illustrates how prototypes (job descriptions) and inheritance (promotions) provide a way to create a hierarchy of roles with shared and inherited responsibilities while allowing customization as needed.

[JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

[Object Prototypes Using a Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)

## Bookmarks

[HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)

## Things I Want to Know More About

* Practice building a table
* Constructors - how to write/use them
