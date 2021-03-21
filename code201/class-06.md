# Problem Domain, Objects, and the DOM

### ***Object Literals***

*A JavaScript object literal is a comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package. This minimizes the use of global variables which can cause problems when combining code.*

##### **Object Literal Syntax**

Object literals are defined using the following syntax rules:-
- A colon separates property name from value.
- A comma separates each name-value pair from the next.
- A comma after the last name-value pair is optional.

*If any of the syntax rules are broken, such as a missing comma or colon or curly brace, a JavaScript error will be triggered. Browser error messages are helpful in pointing out the general location of object literal syntax errors, but they will not necessarily be completely accurate in pointing out the nature of the error.*

### ***Document Object Mode***

##### **Decision and Loops:-**
- Conditional statements allow your code to make decisions about what to do next.
- Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>) are used to compare two operands.
- Logical operators allow you to combine more than one set of comparison operators.
- if ... else statements allow you to run one set of code if a condition is true, and another if it is false.
- switch statements allow you to compare a value against possible outcomes (and also provides a default option if none match).
- Data types can be coerced from one type to another.
- All values evaluate to either truthy or falsy.
- There are three types of loop: for, while, and do ... while. Each repeats a set of statements.

### ***The Document Object Model (DOM)***
- It is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content
- DOM trees have four types of nodes: document nodes, element nodes, attribute 
nodes, and text nodes..

[photo](https://www.w3schools.com/js/pic_htmltree.gif)
- You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax.
- An element node can contain multiple text nodes and child elements that are siblings of each other.
- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).


***What is the hardest thing about writing code?***
- Learning a new technology
- Naming things
- Testing your code
- Debugging
- Fixing bugs
- Making software maintainable

###### ***Why problem domains are hard?***
is because you can’t really see what you are trying to build very clearly.  Normally when you put together a jigsaw puzzle you follow steps that might look something like this:

- Figure out what the major components of the picture are
- Sort the pieces by color or component
- Put together all the border pieces
- Put together each component of the picture from the piles you created

***What can you do about it?***
If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:
1. Make the problem domain easier
2. Get better at understanding the problem domain
### *You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.*
#### **Programming is easy if you understand the problem domain**