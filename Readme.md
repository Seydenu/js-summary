# JAVASCRIPT ASSIGNMENT

## SUMMARY
Javascript is a high level intepreted programming language. Unlike other programming languages, you're not demanded to write JavaScript in stactic way. JavaScript is a language for the browser but you can also run it on a server like (node.js).

### WHY LEARN JAVASCRIPT?
1. You can build user interface.

2. It's used in building very fast server site and full stack applications.

3. It's used in mobile development.

4. It's used in desktop application development.

Mdn is the best developer network for JavaScript and it's great for debugging.

### VARIABLES

There are three ways to setr variables in JavaScript, they are: var, let, & const.

Var & let create variables that can be reassigned values, while const creates "constant" variables that can't be reassigned another value

### DATA TYPES

The different types of data types are: string, number, boolean, null, undefines, & symbol.

### String- 
Are used with single or double quotes. ex: const name = 'John';

### Number-
Are basically the normal numbers we use. ex: const age = 30;

### Bolean- 
Are True or False without quotes. ex: const isCool: true;

### Null- 
Means there's nothing i it. ex: const x = null;

### Undefined- 
Can be defined as const y = undefined; or just initialize something with no value, itbwill be undefined. ex: let z;

Concatinating: Which means adding two or more strings together, can be done by adding a plus(+) between the strings.

## ARRAYS

Vaariables that hold multiple values.

ex: const numbers = newArray (1,2,3,4,5) or 

const fruits = ["apples", "oranges", "pears:].

-In JavaScript, you can have multiple data types in a single array unlike some other programming languages.

-You can add items at the end of an array by calling the array and the index number and assign the item name.

-Or incase you don't know the length of the array, you can use the .push method. ex: fruits.push("oranges"); and that will be added at the end of the array.

-But if you want to add items at the beginning, you can use the unshiift method. ex: fruits.unshift('strawberries").

-Also if you want to remove he last character from the array then you can use the pop method. ex: fruits.pop().

-You can indexOf method to know the position of a partcular item in the array. ex: console.log(fruits.indexOf('oranges'));

## OBJECTS 

Normally talk about something tha holds a key value pairs. ex: const person = {
    first name : 'John';
    last name : 'Doe';
    age : 30;
    hobbies : ['music', 'movies', 'sports']
}

Array of objects means you will initialize an array and in that array you will have different objects,  which simply means in the array you'll have objects with each of them holding key value pairs.

## LOOPS

Loops are used in JavaScript to perform repeated taskbased on conditions.

There are different kinds of loops:
- For Loop: for(let i = 0; i<10; i++){
    
    console.log(i);

}

In this, the code is going to run until the prefered condition is met, and the condition is that it should keep running until the number either less than or equal to 10.

- While loop: The difference with this loop is that we set the variable  outside the loop.

ex: let i = 0 

     while(i < 10){
        
        console.log('while loop Number: ${i}');
        i++;
     }

## CONDITIONALS

Conditional statements control behavior in JavaScript and determine whether or not pieces of codes can run. Under conditionals we have:

- 'If' Statement: Where if a conditional is true it's used to specify execution for a block of code.

- 'Else' statement: Where if the same conditional is false it specifies the execution for a block of code.

- 'Else if' statement: This specifies a new test if the first condition is false.

## FUNCTIONS

A function in JavaScript is similar to procedure, a set of statement that performs a task or calculate a value.

A function is always written with the 'function' key word folllowed by your desired function name and then place a parameter in a parenthesis that follow the desired function name. 

ex: function addNums(num1, num2){

    console.log num1 + num2;
}

addNums(5,5);

## D.O.M 

Document Object Model, it,s like a tree structure of your whole document.

There are some methods we can use to display items in the DOM, they are:

**These are used for single elements:**

- console.log(document.getElementById)
- console.log(document.querySelector)

**These are used for mutliple elements**

- console.log(document.querySelectorAll)
- console.log(document.getElementByClassName)
- console.log(document.getElementByTagName)

There is something in JavaScript called **'setTimeout'.** It is used to set a specific time for something to either happen or stop happening. And it normally takes in milliseconds as the time for which you want to execute your desired action.