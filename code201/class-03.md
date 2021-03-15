# HTML Lists, Control Flow with JS, and the CSS Box Model



## **Lists**:-

- There are three types of HTML lists: ordered, unordered, and definition
- Ordered lists use numbers.
- Unordered lists use bullets.
- Definition lists are used to define terminology.
- Lists can be nested inside one another.


## **Boxes**:-

#### *In CSS, the term "box model" is used when talking about design and layout.*

***The CSS box model is essentially a box that wraps around every HTML element. 
It consists of: margins, borders, padding, and the actual content. The image 
below illustrates the box model:***

  [img](https://htmlcss.learn.uno/html-and-css/css-box-model/css-box-model-73a525.png)

Explanation of the different parts:

- Content - The content of the box, where text and images appear
- Padding - Clears an area around the content. The padding is transparent
- Border - A border that goes around the padding and content
- Margin - Clears an area outside the border. The margin is transparent
- The box model allows us to add a border around elements, and to define space between elements. 

###### ***Example:-***
Demonstration of the box model:

div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}


## **JavaScript:-**

### ***if...else***
*The if statement executes a statement if a specified condition is truthy. If the 
condition is falsy, another statement can be executed.*

***Syntax***:-

if (condition)
   statement1
[else
   statement2]


##### ***condition***
An expression that is considered to be either truthy or falsy.
##### ***statement1***
A statement that is executed if the condition is truthy. Can be any statement, 
including further nested if statements. To execute multiple statements, use a 
block statement ({ ... }) to group those statements. To execute no statements, 
use an empty statement.
##### ***statement2***
A statement that is executed if the condition is falsy and the else clause 
exists. Can be any statement, including block statements and further nested if 
statements.

### ***Switch Statement***:-

*Use the switch statement to select one of the many code blocks to be executed.*

***Syntax***

switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}

#### This is how it works:

- The switch expression is evaluated once.
- The value of the expression is compared with the values of each case.
- If there is a match, the associated block of code is executed.
- If there is no match, the default code block is executed.

### The break Keyword

*When JavaScript reaches a break keyword, it breaks out of the switch block.
This will stop the execution inside the switch block.*

**It is not necessary to break the last case in a switch block. The block breaks 
(ends) there anyway.**

***Note*** If you omit the break statement, the next case will be executed even 
if the evaluation does not match the case.

#### The default Keyword

The default keyword specifies the code to run if there is no case match