# Comparison and logical operators
![img](https://images.slideplayer.com/26/8591629/slides/slide_5.jpg)

###### CALCULAT E ANO WRITE OUT THE EX PIRY DETAILS FOR THE OFFER 
- [x] var expiryMsg; II Message displ ayed t o users 
- [x] var today ; II Today's dat e 
- [x] var el Ends ; II The element that shows the message about the offer endi ng


###### Functions allow you to group a set of related  statements together that represent a single task. 

###### Functions can take parameters (informatiorJ required  to do their job) and may return a value. 
###### An object is a series of variables and functions that  represent something from the world around you. 

###### 0JavaScript also has several built-in objects such as  String, Number, Math, and Date. Their properties and  methods offer functionality that help you write scripts. 
###### Arrays and objects can be used to create complex data  sets (and both can contain the other). 

## Evaluating conditions and conditional statements

###### Summary
No|----
--|----
1|The if-else and if statements
2|Block of statements
3| Conditional expression
4|Comparison between objects
5|The switch statement






***The if-else and if statements***
~ 
if (condition )
then-statement
else
else-statement
• condition is an expression of type boolean, i.e., a conditional expression that is evaluated to true or
false
• then-statement is a single statement (also called the then-branch of the if-else statement)
• else-statement is a single statement (also called the else-branch of the if-else statement)~




### Evaluating conditions
![nw](https://slideplayer.com/slide/7786392/25/images/4/Logical+Comparison+Operators.jpg)


###### one of the comparison operators (==, !=, >, <, >=, or <=) applied to variables (or expressions) of a primitive type;

>Example:
int a, b, c;
...
if (a > b + c)

###### a complex boolean expression, obtained by applying the boolean operators !, &&, and || to simpler expressions;
>Example:
int a, b, c, d;
String answer;
...
if ((a > (b+c)) || (a == d) && !answer.equalsIgnoreCase("YES"))



### else-statement

> condition is an expression of type boolean, i.e., a conditional expression that is evaluated to true or
false

> then-statement is a single statement (also called the then-branch of the if-else statement)
 else-statement is a single statement (also called the else-branch of the if-else statement)





### Different Kinds of LoopsJavaScript supports different kinds of loops:

1. for - loops through a block of code a number of times
2. for/in - loops through the properties of an object
3. for/of - loops through the values of an iterable object
4. while - loops through a block of code while a specified condition is true
5. do/while - also loops through a block of code while a specified condition is true

~~~
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
~~~~

###### Statement 1 is executed (one time) before the execution of the code block.

###### Statement 2 defines the condition for executing the code block.

###### Statement 3 is executed (every time) after the code block has been executed.



