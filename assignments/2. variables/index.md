1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
```
<!-- Answer: Name is a "string"; -->


2. Find the error if any
```js
  var product cost = 3.45;
```
<!-- Answer: Variable name cannot have spaces. -->
3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" 
  // Answer: Right
  'Hello World"
  // Answer: Wrong
  "Hello World'
  // Answer: Wrong
  'Hello World'
  // Answer: Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man;
// Answer: Valid
var 1girl;
// Answer: Invalid, cannot start with a digit.
var woman3;
// Answer: Valid
var -girl;
// Answer: Invalid, hyphens not allowed.
var blackDog;
// Answer: Valid
var 42;
// Answer: Invalid, first character cannot be a digit.
var $42;
// Answer: Valid
var userName;
// Answer: Valid
var x, y, z;
// Answer: Valid. However, such names should be avoided as they do not have a clean, obvious meaning, describing the data that it stores.
var x = 5, y = 6, z = 7;
// Answer: Valid
var x = 5 + 10 + 2;
// Answer: Valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var amountLess = amount - 80;
alert (amountLess);
// Define a new variable and store the value that is 200 more then the value of amount.
var amountMore = amount + 200;
alert (amountMore);
// Define a new variable and store the value that is 4 times the value of amount.
var amountFourTimes = amount*4;
alert (amountFourTimes);
// Define a new variable and store the reminder when the value of amount is  divided by 21.
var newVar = amount%21;
alert(newVar);



```
Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js

var johnAge = 45;
var markAge = 35;

// Check who is older either John or Mark
// Check who is younger
// Check if their age is equal
// Create a new variable and assign the age of john to new variable.
// Check if john is equal to or greater then mark.
// Check if john is less then or equal to mark.

// Calculate the average age of john and mark and assign to a new variable.
if (johnAge > markAge) {
  alert ("John is older. Mark is younger.");
} else {
  alert ("Mark is older. John is younger.")
}
if (johnAge == markAge) {
  alert ("They are of same age.")
}
var newAgeVar = johnAge;
if (newAgeVar >= markAge) {
  alert ("John's age is equal to or more than that of Mark");
}
if (newAgeVar <= markAge) {
  alert ("John's age is equal to or less than that of Mark")
}
var avgAge = (newAgeVar+markAge)/2;
alert (`The average age is ${avgAge}`);