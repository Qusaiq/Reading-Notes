# Operators and Loops 

| Operators | Description | Example | O/P |
| --------- | ----------   | -------- | --------- |
|  ==       | this operator compare two values | 'hello' == 'GoodBye' | false |
| !=        | this opreator compares two values to see if they are not the same| 'hello' == 'GoodBye'| true |
| ===       | this operator compares two values to check that both the data type and the value are the same | '3' === 3 | false 
| !==      | this operator compares two values to check that both the data type and the value are not the same | '3' !== 3  | true |
| > | this operator checks if the number on the left side greater than the right side |  4 > 3  | true |
| <  | this operator checks if the number on the left side smaller than the right side  | 4 < 3  | false |
| >=   | this operator checks if the number on the left is greater than or equal to the number on the right  | 4 >= 3 | true | 
|   <=  | this operator checks if the number on the left is smaller than or equal to the number on the right  | 4 <= 3 | false |




------------------------------------

# Logical Operators 

> Comparison operator usally returns single values of true or false.<br> Logical operators allow you to compare the result of more than one<br> Comparison operator.
>> example : (( 5 < 2) && (2 >= 3))
> first side = false and the other side is false then the result is false.

<br><br>


| Logical  Operators | Description | Example | O/P |
| --------- | ----------   | -------- | --------- |
|  &&      | this operator test more than one condition | (( 5 < 2) && (2 >= 3)) | false |
|    or operator     | this operator tests at least one condition  | (( 2 < 5)||( 2 < 1)) | true |
| !      | this operator takes a single Boolean value and inverts it. | !( 2 < 1) | true |

---------------------------------------------- 



# Loops 

> ### loops check a condition . if it returns true a code block will run.<br>
>### then the condition will be checked again and if still returns true the code block will run again . <br>
>### it repeats until the condition returns false .
<br>
<br>

# FOR
>if you need to run code a specifc number of times , use a *for* loop.

> for (var i = 0 ; i < 10 ; i++);

>> first part befor the ; is the initialization : create a variable and set it to zero;
>> secound part is the condition : the loop should continue to run until the counter .
>> the last part is the update part : every time the loop has run the statement in the curly braces , it adds one to the counter.


# WHILE 
> if you do not know how many times the code should run m you can use a *while* loop.

> here is an example of awhil e 
loop. It writes out the 5 times 
table. Each time the loop is run, 
another calculation is written 
into the variable called msg. 
This loop will continue to run 
for as long as the condition in 
the parentheses is true. That 
condition is a counter indicating 
that, as long as the variable 
i remains less than 10, the 
statements in the subsequent 
code block should run. 
Inside the code block there are 
two statements: 
The first statement uses the+= 
operator, which is used to add 
new content to the msg variable. 
Each time the loop runs, a new 
calculation and line break is 
added to the end of the message 
being stored in it. So+" works as 
a shorthand for writing: 
msg = msg + 'new msg' 
(See bottom of the next page for 
a breakdown of this statement.) 
The second statement 
increments the counter variable 
by one. (This is done inside 
the loop rather than with the 
condition.) 
When the loop has finished, the 
interpreter goes to the next line 
of code, which writes the msg 
variable to the page. 


