# Object-Oriented Programming, HTML Tables

### ***Domain modeling***:-
Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Here's some tips to follow when building your own domain models.

- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- Model its attributes with a constructor function that defines and initializes properties.
- Model its behaviors with small methods that focus on doing one job well.
- Create instances using the new keyword followed by a call to a constructor function.
- Store the newly created object in a variable so you can access its properties and methods from outside.
- Use the this variable within methods so you can access the object's properties and methods from inside.

### ***Tables***:-

*A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.*

***Basic Table Structure***

- table ---> The 'table' element is used to create a table. The contents of the table are written out row by row.
- tr ---> You indicate the start of each row using the opening tag. 'tr' (The tr stands for table row.)
- td ---> Each cell of a table is represented using a 'td' element. (The td stands for table data.)
- th ---> The 'th' element is used just like the 'td' element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading).

***Note*** Even if a cell has no 'td' content, you should still use a or 'td' element to represent the presence of an empty cell otherwise the table will not render correctly
- colspan ---> The colspan attribute can be used on a th or td element and indicates how many columns that cell should run across
- rowspan ---> The rowspan attribute can be used on a th or td element to indicate how many rows a cell should span down the table.
- Long Tables There are three elements that help distinguish between the main content of the table and the first and last rows :
   1. thead ---> The headings of the table should sit inside the 'thead' element.
   2. tbody ---> The body should sit inside the 'tbody'  element.
   3. tfoot --> The footer belongs inside the 'tfoot' element
- Width & Spacing ---> The width attribute was used on the opening tag to 'table' indicate how wide that table should be and on some opening th and td tags to specify the width of individual cells. The value of this attribute is the width of the table or cell in pixels.

### ***Functions, Methods, and Objects***:-

- Functions allow you to group a set of related statements together that represent a single task.
- Functions can take parameters (information required to do their job) and may return a value.
- An object is a series of variables and functions that represent something from the world around you.
- In an object, variables are known as properties of the object; functions are known as methods of the object.
- Web browsers implement objects that represent both the browser window and the document loaded into the browser window.
- JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts. 
- Arrays and objects can be used to create complex data sets (and both can contain the other).
- A JavaScript method is a property containing a function definition.