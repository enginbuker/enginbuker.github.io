## Exercise 1

```js

//This is freecodecamp exercises of JS.

/*The first week Homework is from Comment Your JavaScript Code to Golf Code.
You can find whole lis in Basic JavaScript Exercises List*/
```

## Exercise 2
```js
// JavaScript provides seven different data types which are undefined, null, boolean, string, symbol, number, and object.
var myName;
// Declare myName below this line
    myName = "Engin";
```

## Exercise 3
```js
// Setup
var a;
var b = 2;

// Only change code below this line
    a = 7;
    b = a;
// Note: At a result of this exercise 7 will be assigned to a and b.
```

## Exercise 4
```js
// Example
var ourVar = 19;

// Only change code below this line
var myVar =0;
var a = 9;
```

## Exercise 5
```js
// Initialize these three variables
var a = 5;
var b = 10;
var c = "I am a";

// Do not change code below this line

a = a + 1;
b = b + 5;
c = c + " Web Developer!";

/* The result of this exercise at below.
a = 6
b = 15
c	= "I am a Web Developer!"
```

## Exercise 5
```js
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```

## Exercise 6
```js
var sum = 10 + 10;
// sum is equal to 20.
```

## Exercise 7
```js
var difference = 45 - 33;
// difference is equal to 12.
```

## Exercise 8
```js
var product = 8 * 10;
// product is equal to 12.
```

## Exercise 9
```js
var quotient = 66 / 33;
// quotient is equal to 2.
```

## Exercise 10
```js
var myVar = 87;

// Only change code below this line
myVar++;
````

## Exercise 11
```js
var myVar = 11;

// Only change code below this line
myVar--;
````

## Exercise 12
```js
var ourDecimal = 5.7;

// Only change code below this line
var myDecimal = 1.2;
````

## Exercise 13
```js
var product = 2.0 * 2.5;
````

## Exercise 13
```js
var quotient = 4.4 / 2.0; // Fix this line
````

## Exercise 13
```js
// Only change code below this line

var remainder;
 remainder = 11 %  3;
````

## Exercise 14
```js
var a = 3;
var b = 17;
var c = 12;

// Only modify code below this line

a += 12;
b += 9;
c += 7;
/* Results;
a=15
b=26
c=19 */
````

## Exercise 15
```js
var a = 11;
var b = 9;
var c = 3;

// Only modify code below this line

a -= 6;
b -= 15;
c -= 1;
/* Results;
a=5
b=-4
c=2 */
````

## Exercise 16
```js
var a = 5;
var b = 12;
var c = 4.6;

// Only modify code below this line

a *= 5;
b *= 3;
c *= 10;
/* Results;
a=25
b=36
c=46 */
````

## Exercise 17
```js
var a = 48;
var b = 108;
var c = 33;

// Only modify code below this line

a /= 12;
b /= 4;
c /= 11;
/* Results;
a=4
b=27
c=3 */
````

## Exercise 18
```js
// Example
var firstName = "Alan";
var lastName = "Turing";

// Only change code below this line
var myFirstName = "Engin";
var myLastName = "Buker";
````

## Exercise 19
```js
var myStr = "I am a \"double quoted\" string inside \"double quotes\"."; // Change this line
````

## Exercise 20
```js
var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
````

## Exercise 21
```js
/*Code	Output
\'	single quote
\"	double quote
\\	backslash
\n	newline
\r	carriage return
\t	tab
\b	backspace
\f	form feed
Note that the backslash itself must be escaped in order to display as a backslash.*/

var myStr = "FirstLine\n\tSecondLine\nThirdLine"; // Change this line
````

## Exercise 22
```js

// Example
var ourStr = "I come first. " + "I come second.";

// Only change code below this line

var myStr = "This is the start. " + "This is the end.";
````

## Exercise 23
```js
// Example
var ourStr = "I come first. ";
ourStr += "I come second.";

// Only change code below this line

var myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";
````

## Exercise 24
```js
// Example
var ourName = "freeCodeCamp";
var ourStr = "Hello, our name is " + ourName + ", how are you?";

// Only change code below this line
var myName = "Engin";
var myStr = "My name is " + myName + " and I am well!";
````

## Exercise 25
```js
// Example
var anAdjective = "awesome!";
var ourStr = "freeCodeCamp is ";
ourStr += anAdjective;

// Only change code below this line

var someAdjective = "funny";
var myStr = "Learning to code is ";
myStr += someAdjective;
````

## Exercise 26
```js
// Example
var firstNameLength = 0;
var firstName = "Ada";

firstNameLength = firstName.length;

// Setup
var lastNameLength = 0;
var lastName = "Lovelace";

// Only change code below this line.

lastNameLength = lastName.length;
````

## Exercise 27
```js
// Example
var firstLetterOfFirstName = "";
var firstName = "Ada";

firstLetterOfFirstName = firstName[0];

// Setup
var firstLetterOfLastName = "";
var lastName = "Lovelace";

// Only change code below this line
firstLetterOfLastName = lastName[0];
````

## Exercise 28
```js
// Setup
var myStr = "Jello World";

// Only change code below this line

myStr = "Hello World"; // Fix Me

/* For example, the following code:

var myStr = "Bob";
myStr[0] = "J";
cannot change the value of myStr to "Job", because the contents of myStr cannot be altered. Note that this does not mean that myStr cannot be changed, just that the individual characters of a string literal cannot be changed. The only way to change myStr would be to assign it with a new string, like this:

var myStr = "Bob";
myStr = "Job";*/
````

## Exercise 29
```js
// Example
var firstName = "Ada";
var secondLetterOfFirstName = firstName[1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var thirdLetterOfLastName = lastName[2];
````

## Exercise 30
```js
// Example
var firstName = "Ada";
var lastLetterOfFirstName = firstName[firstName.length - 1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var lastLetterOfLastName = lastName[lastName.length - 1];
````

## Exercise 31
```js
// Example
var firstName = "Ada";
var thirdToLastLetterOfFirstName = firstName[firstName.length - 3];

// Setup
var lastName = "Lovelace";

// Only change code below this line
var secondToLastLetterOfLastName = lastName[lastName.length - 2];
````

## Exercise 32
```js
function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
  // Your code below this line
  var result = myAdjective + myNoun + myVerb + myAdverb;


  // Your code above this line
  return result;
}

// Change the words here to test your function
var result = wordBlanks("dog ", "big ", "ran ", "quickly.");
var result = wordBlanks("cat ", "little ", "hit ", "slowly.");
````

## Exercise 33
```js
// Example
var ourArray = ["John", 23];

// Only change code below this line.
var myArray = ["Engin", 37];
````

## Exercise 34
```js
// Example
var ourArray = [["the universe", 42], ["everything", 101010]];

// Only change code below this line.
var myArray = [["Erhan", 7], ["Burak", 5]];
````

## Exercise 35
```js
// Example
var ourArray = [50,60,70];
var ourData = ourArray[0]; // equals 50

// Setup
var myArray = [50,60,70];

// Only change code below this line.
var myData = myArray[0];
````

## Exercise 36
```js
// Example
var ourArray = [18,64,99];
ourArray[1] = 45; // ourArray now equals [18,45,99].

// Setup
var myArray = [18,64,99];

// Only change code below this line.
myArray[0] = 45;
````

## Exercise 37
```js
// Setup
var myArray = [[1,2,3], [4,5,6], [7,8,9], [[10,11,12], 13, 14]];

// Only change code below this line.
var myData = myArray[2][1];
````

## Exercise 38
```js
// Example
var ourArray = ["Stimpson", "J", "cat"];
ourArray.push(["happy", "joy"]); 
// ourArray now equals ["Stimpson", "J", "cat", ["happy", "joy"]]

// Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.
myArray.push(["dog", 3]);
````

## Exercise 39
```js
// Example
var ourArray = [1,2,3];
var removedFromOurArray = ourArray.pop(); 
// removedFromOurArray now equals 3, and ourArray now equals [1,2]

// Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.
var removedFromMyArray = myArray.pop();
````

## Exercise 40
```js
// Example
var ourArray = ["Stimpson", "J", ["cat"]];
var removedFromOurArray = ourArray.shift();
// removedFromOurArray now equals "Stimpson" and ourArray now equals ["J", ["cat"]].

// Setup
var myArray = [["John", 23], ["dog", 3]];

// Only change code below this line.
var removedFromMyArray = myArray.shift();
````

## Exercise 41
```js
// Example
var ourArray = ["Stimpson", "J", "cat"];
ourArray.shift(); // ourArray now equals ["J", "cat"]
ourArray.unshift("Happy"); 
// ourArray now equals ["Happy", "J", "cat"]

// Setup
var myArray = [["John", 23], ["dog", 3]];
myArray.shift();

// Only change code below this line.
myArray.unshift(["Paul",35]);
````

## Exercise 42
```js
var myList = [["Chocolate Bar", 15],["a", 2], ["b", 3], ["c", 4], ["d", 5]];
````

## Exercise 43
```js
// Example
function ourReusableFunction() {
  console.log("Heyya, World");
}

ourReusableFunction();

// Only change code below this line
function reusableFunction() {
    console.log("Hi World")
}

reusableFunction();
````

## Exercise 44
```js
// Example
function ourFunctionWithArgs(a, b) {
  console.log(a - b);
}
ourFunctionWithArgs(10, 5); // Outputs 5

// Only change code below this line.

function functionWithArgs(x, y) {
  console.log(x + y);
}
functionWithArgs(2, 3);
````

## Exercise 44
```js
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
````

## Exercise 45
```js
function myLocalScope() {
  'use strict'; // you shouldn't need to edit this line
  var myVar = "myVar";
  console.log(myVar);
}
myLocalScope();

// Run and check the console
// myVar is not defined outside of myLocalScope
console.log(myVar);

// Now remove the console log line to pass the test
````

## Exercise 46
```js
// Setup
var outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
  var outerWear = "sweater";

  // Only change code above this line
  return outerWear;
}

myOutfit();
````

## Exercise 47
```js
// Example
function minusSeven(num) {
  return num - 7;
}

// Only change code below this line
function timesFive(num) {
  return num * 5;
}


console.log(minusSeven(10));
console.log(timesFive(5));
console.log(timesFive(2));
console.log(timesFive(0));
````

## Exercise 48
```js
// Example
var sum = 0;
function addThree() {
  sum = sum + 3;
}

// Only change code below this line
function addFive() {
  sum += 5;
}


// Only change code above this line
var returnedValue = addFive();
````

## Exercise 49
```js
// Example
var changed = 0;

function change(num) {
  return (num + 5) / 3;
}

changed = change(10);

// Setup
var processed = 0;

function processArg(num) {
  return (num + 3) / 5;
}

// Only change code below this line
processed = processArg(7);
````

## Exercise 50
```js
function nextInLine(arr, item) {
  // Your code here
  arr.push(item);
  return arr.shift(); // Change this line
}

// Test Setup
var testArr = [1,2,3,4,5];

// Display Code
console.log("Before: " + JSON.stringify(testArr));
console.log(nextInLine(testArr, 6)); // Modify this line to test
console.log(nextInLine([], 5));
console.log(nextInLine([], 1));
console.log(nextInLine([2], 1));
console.log(nextInLine([5,6,7,8,9], 1));
console.log(nextInLine(testArr, 10));
testArr[4];
console.log("After: " + JSON.stringify(testArr));
````
## Exercise 51
```js

function welcomeToBooleans() {

// Only change code below this line.

return true; // Change this line

// Only change code above this line.
}
````

## Exercise 52
```js

// Example
function ourTrueOrFalse(isItTrue) {
  if (isItTrue) { 
    return "Yes, it's true";
  }
  return "No, it's false";
}

// Setup
function trueOrFalse(wasThatTrue) {

  // Only change code below this line.
  if (wasThatTrue) {
      return "Yes, that was true";
  }
  return "No, that was false";
  // Only change code above this line.

}

// Change this value to test
trueOrFalse(true);
````

## Exercise 53
```js

// Setup
function testEqual(val) {
  if (val == 12) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testEqual(10);
testEqual(12);
testEqual("12");

/* 1 == 1 // true
1 == 2 // false
1 == '1' // true
"3" == 3 // true */
````

## Exercise 54
```js
// Setup
function testStrict(val) {
  if (val === 7) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testStrict(10);
testStrict(7);
testStrict("7");
````

## Exercise 55
```js
// Setup
function compareEquality(a, b) {
  if (a === b) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
compareEquality(10, "10");
compareEquality('20', 20);
````

## Exercise 56
```js
// Setup
function testNotEqual(val) {
  if (val != 99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testNotEqual(99);
testNotEqual("99");
testNotEqual(12);
testNotEqual("12");
testNotEqual("bob");
````

## Exercise 56
```js
// Setup
function testStrictNotEqual(val) {
  // Only Change Code Below this Line
  
  if (val !== 17) {

  // Only Change Code Above this Line

    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testStrictNotEqual(17);
testStrictNotEqual('17');
testStrictNotEqual(12);
testStrictNotEqual("bob");
````

## Exercise 57
```js
function testGreaterThan(val) {
  if (val > 100) {  // Change this line
    return "Over 100";
  }
  
  if (val > 10) {  // Change this line
    return "Over 10";
  }

  return "10 or Under";
}

// Change this value to test
testGreaterThan(0);
testGreaterThan(10);
testGreaterThan(11);
testGreaterThan(99);
testGreaterThan(100);
testGreaterThan(101);
testGreaterThan(150);
````

## Exercise 58
```js
function testGreaterOrEqual(val) {
  if (val >= 20) {  // Change this line
    return "20 or Over";
  }
  
  if (val >=10 ) {  // Change this line
    return "10 or Over";
  }

  return "Less than 10";
}

// Change this value to test
testGreaterOrEqual(0);
testGreaterOrEqual(9);
testGreaterOrEqual(10);
testGreaterOrEqual(11);
testGreaterOrEqual(19);
testGreaterOrEqual(100);
testGreaterOrEqual(21);
````

## Exercise 59
```js
function testLessThan(val) {
  if (val < 25) {  // Change this line
    return "Under 25";
  }
  
  if (val < 55) {  // Change this line
    return "Under 55";
  }

  return "55 or Over";
}

// Change this value to test
testLessThan(0);
testLessThan(24);
testLessThan(25);
testLessThan(54);
testLessThan(55);
testLessThan(99);
````

## Exercise 60
```js
function testLessOrEqual(val) {
  if (val <= 12) {  // Change this line
    return "Smaller Than or Equal to 12";
  }
  
  if (val <= 24) {  // Change this line
    return "Smaller Than or Equal to 24";
  }

  return "More Than 24";
}

// Change this value to test
testLessOrEqual(0);
testLessOrEqual(11);
testLessOrEqual(12);
testLessOrEqual(23);
testLessOrEqual(24);
testLessOrEqual(25);
testLessOrEqual(55);
````

## Exercise 61
```js
function testLogicalAnd(val) {
  // Only change code below this line

  if (val <= 50 && val >= 25) {
      return "Yes";
    }


  // Only change code above this line
  return "No";
}

// Change this value to test
testLogicalAnd(0);
testLogicalAnd(24);
testLogicalAnd(25);
testLogicalAnd(30);
testLogicalAnd(50);
testLogicalAnd(51);
testLogicalAnd(75);
testLogicalAnd(80);
````

## Exercise 62
```js
function testLogicalOr(val) {
  // Only change code below this line

  if (val < 10 || val > 20) {
    return "Outside";
  }

  // Only change code above this line
  return "Inside";
}

// Change this value to test
testLogicalOr(0);
testLogicalOr(9);
testLogicalOr(10);
testLogicalOr(15);
testLogicalOr(19);
testLogicalOr(20);
testLogicalOr(21);
testLogicalOr(25);
````

## Exercise 63
```js
function testElse(val) {
  var result = "";
  // Only change code below this line
  
  if (val > 5) {
    result = "Bigger than 5";
  } else {
    result = "5 or Smaller";
  }
  
  // Only change code above this line
  return result;
}

// Change this value to test
testElse(4);
testElse(5);
testElse(6);
testElse(10);
````

## Exercise 64
```js
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  } else if (val < 5) {
    return "Smaller than 5";
  } else {
    return "Between 5 and 10";
  }
}

// Change this value to test
testElseIf(0);
testElseIf(5);
testElseIf(7);
testElseIf(10);
testElseIf(12);
````

## Exercise 65
```js
function orderMyLogic(val) {
  if (val < 5) {
    return "Less than 5";
  } else if (val < 10) {
    return "Less than 10";
  } else {
    return "Greater than or equal to 10";
  }
}

// Change this value to test
orderMyLogic(4);
orderMyLogic(6);
orderMyLogic(11);
````

## Exercise 66
```
function testSize(num) {
  // Only change code below this line
  if (num < 5) {
    return "Tiny";
  } else if (num < 10) {
    return "Small";
  } else if (num < 15) {
    return "Medium";
  } else if (num < 20) {
    return "Large";
  } else {
    return "Huge";
  }
  
  return "Change Me";
  // Only change code above this line
}

// Change this value to test
testSize(0);
testSize(4);
testSize(5);
testSize(8);
testSize(10);
testSize(14);
testSize(15);
testSize(17);
testSize(20);
testSize(25);
````

