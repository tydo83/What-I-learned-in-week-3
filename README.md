# What I learned in week 3

## JavaScript Hoisting
---
In JavaScript, a variable can be used before it has been declared since JavaScript **moves all declarations to to the top of the current script or the current function.** 

## Debugging in VS code
---
VS code has a great debugging support tool. It helps you easily visualize your code without using Quokka or console.log();

* breakpoint: It is an intentional stopping or pausing place\
 for debugging purposes.
* step over: Test the code by the line. If the line contains a function,\
 the function will be executed but It won't debug lines in the function.
* step into: It works same as step over but it will enter the called\
 function and continue line-by-line debugging
* watch: Show the value of variable line-by-line

## Front-end and Back-end
* Front-end: User interface
* Back-end: Server, application and database\
that work behind the scenes 

## Node input
---
```
let variable = process.argv[num]
```
It is used to take arguments from the terminal by typing after node filename.js. But, [num] cannot be 0 or 1. O takes the location of node and 1 takes location of file. You can also use two-dimensional array.

## Find a specified string 
---
```
str.endsWith('string value')
```
The endsWith() method determines whether a string ends with the characters of a specified string, returning true or false as appropriate.
```
str.startsWith('string value')
```
The startsWith() method determines whether a string begins with the characters of a specified string, returning true or false as appropriate.
```
indexOf('string value')
```
If there is no string value, indexOf method return -1, and if there is,it will return the first index number of the string value. 

## Another way to declare function in JavaScript
---
=> is the new syntax to tell JS that we're writing a function instead of keyword function

## if and else if 
---
Conditional statements which are used to perform different actions based on different conditions.
```
if(expression1) {
    statement1 
    // if expression1 is true, executes statement1.
    }
else if(expression2) { 
    statement2
    // if expression1 is false, check expression2 and if it is true, executes statement2.
    }    
```
![if and else if](https://www.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-if-else-statment.png)

## while loop  
---
The JavaScript while statement creates a loop that executes a block of code as long as the test condition evaluates to true.
```
while(expression) {
    statement;
    //if expression is true, execute the statement until expression becomes false.
}
```
![chart](https://www.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-while-loop.png)


