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
/*

Previously we have used the code

var myName = "your name";

"your name" is called a string literal. 
It is a string because it is a series of zero or more characters enclosed 
in single or double quotes.*/


// Example
var firstName = "Alan";
var lastName = "Turing";

// Only change code below this line

var myFirstName = "Yavuz"
var myLastName = "Ugurtas"


---

/*In JavaScript, you can escape a quote from considering it as an end of
string quote by placing a backslash (\) in front of the quote.*/

eg: var myStr = "Edward Said said, \"My surname is strange\" and added \"Javascript is my passion\".";


```
## Example 14 - Escape Sequences in Strings

```js

We learned this in the previous challenge.

Code	Output
\'	single quote
\"	double quote
\\	backslash
\n	newline
\r	carriage return
\t	tab
\b	word boundary
\f	form feed

Note that the backslash itself must be escaped in order to display as a backslash.
eg: var myStr = "FirstLine\n\t\\SecondLine\nThirdLine";

```
## Example 15 - Concatenating Strings with Plus Operator

```js
/*it is called the concatenation operator. You can build a new
string out of other strings by concatenating them together. */

Examples

'My name is Alan,' + ' I concatenate.' 

eg: Build myStr from the strings "This is the start. " and "This is the end." using the + operator.

var myStr = "This is the start." + " This is the end."

var myStr= "This is the first sentence."  
myStr += " This is the second sentence."

var myName = "Yavuz";
var myStr = "My name is" + myName + " and I am well"

var someAdjective = "cool cool cool"
var myStr = "Learning to code is ";
myStr = myStr += someAdjective


```

## Example 16 -  Find the Length of a String

```js
/* 

You can find the length of a String value by writing .length after the string variable or string literal.

"Alan Peter".length; // 10

For example, 
if we created a variable var firstName = "Charles", 
we could find out how long the string "Charles" is by using the firstName.length property.*/

// Setup
var lastNameLength = 0;
var lastName = "Lovelace";

// Only change code below this line.

lastNameLength = lastName.length;


```
## Example 17 - Understand String Immutability

```js
/*In JavaScript, String values are immutable, which means that they cannot be altered once created.

For example, the following code:

var myStr = "Bob";
myStr[0] = "J";

cannot change the value of myStr to "Job",
because the contents of myStr cannot be altered. Note that this does not mean that myStr cannot be changed,
just that the individual characters of a string literal cannot be changed. 
The only way to change myStr would be to assign it with a new string, like this:

var myStr = "Bob";
myStr = "Job";
*/

```

## Remember : "computers start counting at 0, so the first character is actually the zeroth character."


## Example 18 - Use Bracket Notation to Find the Last Character in a String

```js
/*For example, if var firstName = "Charles", you can get the value of the last letter of the string by using firstName[firstName.length - 1].*/
 // Setup
var lastName = "Lovelace";

// Only change code below this line.
var lastLetterOfLastName = lastName[lastName.length-1];


```

## Example 19 - Word Blanks

```js
var myNoun = "dog";
var myAdjective = "big";
var myVerb = "ran";
var myAdverb = "quickly";

var wordBlanks = "My " + myAdjective + " " + myNoun +"," + myVerb + " away " + myAdverb + "."; // Only change this line;

```

## Example 20 - Store Multiple Values in one Variable using JavaScript Arrays

```js

/* 

With JavaScript array variables, we can store several pieces of data in one place.

You start an array declaration with an opening square bracket, 
end it with a closing square bracket, and put a comma between each entry, like this:

var sandwich = ["peanut butter", "jelly", "bread"].*/ 

eg: 

Modify the new array myArray so that
it contains both a string and a number (in that order).
var myArray = ["Yavuz", 7];


```

## Example 21 -  Access Array Data with Indexes

```js

Example

/*var array = [50,60,70];
array[0]; // equals 50
var data = array[1];  // equals 60*/

eg: Create a variable called myData and set it 
to equal the first value of myArray using bracket notation.

var myArray = [50,60,70];
var myData = myArray[0];
---

eg;
Using bracket notation select an element from myArray such that myData is equal to 8.
// Setup
var myArray = [[1,2,3], [4,5,6], [7,8,9], [[10,11,12], 13, 14]];

// Only change code below this line.
var myData = myArray[2][1];




```
## Example 22 - Manipulate Arrays With push() ,pop(), shift()

```js
/*An easy way to append data to the end of an array is via the push() function.

.push() takes one or more parameters and "pushes" them onto the end of the array.

var arr = [1,2,3];
arr.push(4);
// arr is now [1,2,3,4]*/

eg: Push ["dog", 3] onto the end of the myArray variable.
// Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.
myArray.push(["dog",3])

---
 .pop() removes the last element from an array and returns that element.
 // Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.
var removedFromMyArray = myArray.pop();

---

 .shift() comes in. It works just like .pop(),
 except it removes the first element instead of the last.
eg:Use the .shift() function to remove the first item from myArray, 
assigning the "shifted off" value to removedFromMyArray.

// Setup
var myArray = [["John", 23], ["dog", 3]];

// Only change code below this line.
var removedFromMyArray = myArray.shift();

```

## Example 23 - Shopping List

```js
Create a shopping list in the variable myList. 
The list should be a multi-dimensional array containing several sub-arrays.
i.e.

["Chocolate Bar", 15]
eg: var myList = [["Gala",1905],["yellow",10],["red",7],["Cimbom",1905],["Gs",2019]];
```

## Example 24 - Write Reusable JavaScript with Functions

```js
/*

In JavaScript, we can divide up our code into reusable parts called functions.

Here's an example of a function:

function functionName() {
  console.log("Hello World");
}
*/

eg:    Create a function called reusableFunction 
which prints "Hi World" to the dev console.
    Call the function.
    
function reusableFunction() {
     console.log("Hi World")
}
  reusableFunction();


```

## Example 25 - Passing Values to Functions with Arguments

```js
/* Here is a function with two parameters, param1 and param2:
function testFun(param1, param2) {
  console.log(param1, param2);
  
  Then we can call testFun: testFun("Hello", "World"); 
  We have passed two arguments, "Hello" and "World".
  Inside the function, param1 will equal "Hello" and param2 will equal "World". 
  Note that you could call testFun again with different arguments and the
  parameters would take on the value of the new arguments.
*/

function functionWithArgs(a,b)  {
  console.log(a + b);
}

functionWithArgs(1,2);
functionWithArgs(7,9);
```
## Example 26 - Global Scope and Functions

```js

/*Variables which are used without the var keyword are automatically 
created in the global scope. This can create unintended consequences elsewhere in your code 
or when running a function again. You should always declare your variables with var. */
// Declare your variable here

var myGlobal = 10;

function fun1() {
  // Assign 5 to oopsGlobal Here
oopsGlobal = 5;
}

// Only change code above this line
function fun2() {
  var output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}
running tests
// tests completed
// console output

"myGlobal: 10 oopsGlobal: 5"

---
// Setup
var outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
var outerWear = "sweater";


  // Only change code above this line
  return outerWear;
}

myOutfit();



----


function timesFive(num)  {
   return num * 5;
}

console.log(timesFive(5));


```

## LAst example from class js3 


```js



  class clock {
    constructor(template) {
        this.template = 'template';
        this.timer = 0;

    render: function() {
      let date = new Date();

      let hours = date.getHours();
      if (hours < 10) hours = '0' + hours;

      let mins = date.getMinutes();
      if (mins < 10) mins = '0' + mins;

      let secs = date.getSeconds();
      if (secs < 10) secs = '0' + secs;

      let output = this.template
        .replace('h', hours)
        .replace('m', mins)
        .replace('s', secs);

      console.log(output);
    },

    stop: function() {
      clearInterval(this.timer);
    },

    start: function() {
      this.render();
      timer = setInterval(this.render.bind(this), 1000);
    },

  }
     
     const newClock = new clock('h');
     const secondClock = new clock('h:m');
     


```
