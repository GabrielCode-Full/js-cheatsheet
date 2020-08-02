# Js-cheatsheet

## Comments
```javascript
// This is an in-line comment.

/* This is a
multi-line comment */
```
## Variables
The **`var`** statement declares a **function-scoped or globally-scoped variable,** optionally initializing it to a value.

The **`let`** statement declares a **block-scoped local variable**, optionally initializing it to a value.

Constants **`const`** are **block-scoped**, much like variables defined using the let keyword. The value of a constant can't be changed through reassignment, and it can't be redeclared.



```javascript
var myName = "Gabriel";
let age = 20;
const BIRTHDAY = "January 7, 2000";
```

## Data Types 
The latest ECMAScript standard defines nine types:

`
The 6 primitives data types are undefined,string,boolean,bigint,object and symbol.
`
Data Types | Example | Description
------------ | ------------- |  -------------
`Undefined` | `var myName;` | A variable that has `not been assigned a value is of type undefined`. 
`String` | `var greet = "Hello, World!";` | The String object is `used to represent and manipulate a sequence of characters`.
`Number` | `const MATH_PI = 3.14159;` | Number is a primitive wrapper object `used to represent and manipulate numbers like 37 or -9.25`.
`Boolean` | `const bool = true;` | The value passed as the first parameter is converted to a boolean value, if necessary. `If the value is omitted or is 0, -0, null, false, NaN, undefined, or the empty string (""), the object has an initial value of false.` All other values, including any object, an empty array ([]), or the string "false", create an object with an initial value of true.
`BigInt` | `const theBiggestInt = 9007199254740991n;` | BigInt is a built-in object that provides a way to represent` whole numbers larger than 253 - 1,` which is the largest number JavaScript can reliably represent with the Number primitive and represented by the Number.MAX_SAFE_INTEGER constant. BigInt can be used for arbitrarily large integers.
`Symbol` | Represents a unique identifier. | The data type symbol is a primitive data type. The Symbol() function returns a value of type symbol, has static properties that expose several members of built-in objects, has static methods that expose the global symbol registry, and resembles a built-in object class, but is incomplete as a constructor because it does not support the syntax "new Symbol()".
`Object` | `var arr = ["123"];` | Special non-data but structural type for any constructed object instance also used as data structures: new Object, new Array, new Map, new Set, new WeakMap, new WeakSet, new Date and almost everything made with new keyword;
`Null` | `var noValue = "";` | Special primitive type having additional usage for its value: if object is not inherited, then null is shown;
`Function` | `function greet(){};` | This answer is done as a special shorthand for Functions, though every Function constructor is derived from Object constructor.

## Strings

##  Escape sequences

```
 
Code	Output

\'	single quote (')
\"	double quote (")
\\	backslash (\)
\n	newline
\r	carriage return
\t	tab
\b	backspace
\f	form feed
             
```
```javascript

      // escape literal quotes
      var sampleStr = 'Alan said, "Peter is learning JavaScript".'; //Alan said, "Peter is learning JavaScript"
     
      // concatenating strings
      var ourStr = "I come first. " + "I come second."; //I come first. I come second.

      // concatenating strings with +=
      var ourStr = "I come first. ";
      ourStr += "I come second."; //I come first. I come second.

      // constructing strings with variables
      var ourName = "freeCodeCamp";
      var ourStr = "Hello, our name is " + ourName + ", how are you?"; //Hello, our name is freeCodeCamp, how are you?

      // appending variables to strings
      var anAdjective = "awesome!";
      var ourStr = "freeCodeCamp is ";
      ourStr += anAdjective; //freeCodeCamp is awesome!

```
