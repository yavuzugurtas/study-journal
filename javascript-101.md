# Javascript 101
This is just a study place for me! Credit to freecodecamp.org and Mozilla, Special thanks to HYF Belgium Team.

## Exercise 1

```js 

// Example of in-line

/* This is en example for multi-line comment */
```

## Exercise 2 - Variables

```js 

/*  In computer science, data is anything that is meaningful to the computer. 
JavaScript provides seven different data types which are undefined,
null, boolean, string, symbol, number, and object. 

For example, computers distinguish between numbers, such as the number 12, 
and strings, such as "12", "dog", or "123 cats", which are collections of characters. 
Computers can perform mathematical operations on a number, but not on a string.

Variables allow computers to store and manipulate data in a dynamic fashion. 
They do this by using a "label" to point to the data rather than using the data itself. 
Any of the seven data types may be stored in a variable. */

// Example

var myName;

```
## Exercise 3 - Storing Values with the Assignment Operator

```js


var a = 7;
var b = a;


```
## Exercise 4 - Initializing Variables with the Assignment Operator

```js

/* Eg : 

It is common to initialize a variable to an initial value in the same line as it is declared.

var myVar = 0;

Creates a new variable called myVar and assigns it an initial value of 0.

*/ 

var a = 9;

```

## Exercise 5 - Understanding Uninitialized Variables

```js

/*NaN means Not a Number  

When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". If you concatenate a string with an undefined variable, you will get a literal string of "undefined".

*/
Assignment: a should be 6, b should be 15, c should be "I am a String"

// Initialize these three variables
var a = 5;
var b = 10;
var c = "I am a";

// Do not change code below this line
a = a + 1;
b = b + 5;
c = c + " String!";


```

## Exercise 6 - Understanding Case Sensitivity in Variables

```js

/*MYVAR is not the same as MyVar nor myvar. 
It is possible to have multiple distinct variables with the same name but different casing.
It is strongly recommended that for the sake of clarity, you do not use this language feature. 


Write variable names in JavaScript in camelCase. 

Examples:

var someVariable;
var anotherVariableName;
var thisVariableNameIsSoLong;


*/

```

## Exercise 7 - Add Two Numbers and Subtract One Number from Another and Multiply Two Numbers  and Divide One Number by Another with JavaScript


```js

myVar = 5 + 10; // assigned 15

eg:  sum should equal 20

var sum = 10 + 10;


myVar = 12 - 6; // assigned 6

eg: Make the variable difference equal 12.

var difference = 45 - 33;


myVar = 13 * 13; // assigned 169

eg: Make the variable product equal 80

var product = 8 * 10;

myVar = 16 / 2; // assigned 8

eg: Make the variable quotient equal to 2.

var quotient = 66 / 33;



```


## Exercise 8 - Increment a Number with JavaScript

```js

/*You can easily increment or add one to a variable with the ++ operator.

i++;

is the equivalent of

i = i + 1; 

*/

eg: myVar should equal 88

var myVar = 87;

// Only change code below this line

myVar++;


```
## Exercise 9 - Decrement a Number with JavaScript

```js

/*You can easily decrement or decrease a variable by one with the -- operator.

i--;

is the equivalent of

i = i - 1;

*/




eg: myVar should equal 10

var myVar = 11;

// Only change code below this line

myVar--;


```

## Exercise 10 -  Create Decimal Numbers / Multiply and Divide Two Decimals with JavaScript

```js

/* We can store decimal numbers in variables too. 
Decimal numbers are sometimes referred to as floating point numbers or floats. */

var product = 5.0 * 1.0; // 5.0

eg: The variable quotient should equal 2.2

var quotient = 4.4 / 2; 

```
## Exercise 11 - Finding a Remainder

```js

// The remainder operator % gives the remainder of the division of two numbers.
/*17 % 2 = 1 (17 is Odd)
48 % 2 = 0 (48 is Even)*/

eg: remainder should 2
var remainder = 11 % 3;

```
## Exercise 12 -  (+=, -=, *=, /=)

```js
myVar = myVar + 5;

to add 5 to myVar. Since this is such a common pattern, 
there are operators which do both a mathematical operation and assignment in one step.

One such operator is the += operator.


var myVar = 1;
myVar += 5;
console.log(myVar); // Returns 6

eg:
a should equal 15
b should equal 26
c should equal 19

var a = 3;
var b = 17;
var c = 12;

// Only modify code below this line

a += 12;
b += 9;
c += 7;

--


Like the += operator, -= subtracts a number from a variable.

myVar = myVar - 5;

will subtract 5 from myVar. This can be rewritten as:

myVar -= 5;

eg:
a should equal 5
b should equal -6
c should equal 2

var a = 11;
var b = 9;
var c = 3;

// Only modify code below this line

a -= 6;
b -= 15;
c -= 1;

--

myVar = myVar * 5;

will multiply myVar by 5. This can be rewritten as:

myVar *= 5;

eg:
a should equal 25
b should equal 36
c should equal 46

var a = 5;
var b = 12;
var c = 4.6;

// Only modify code below this line

a *= 5;
b *= 3;
c *= 10;

--



The /= operator divides a variable by another number.

myVar = myVar / 5;

Will divide myVar by 5. This can be rewritten as:

myVar /= 5;

eg:
a should equal 4
b should equal 27
c should equal 3

var a = 48;
var b = 108;
var c = 33;

// Only modify code below this line

a /= 12;
b /= 4;
c /= 11;



```

## Example 13 - Declare String Variables

```js


```

