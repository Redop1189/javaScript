# 🔥 javaScript Guide
### 🔥 javaScript.js

<img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg" alt="Javascript Logo" width="150px" />

### Including JavaScript in an HTML Page
```javascript
<script type="text/javascript">
//JS code goes here
</script>
```
### Call an External JavaScript File
```javascript
<script src="myscript.js"></script><code></code>
```

### Including Comments
```javascript
// comment here
Single line comments
/* comment here */
Multi-line comments
```

### Printing 'Hello World' in javaScript console
```javascript
console.log('Hello World');
```

## Basics

1. Variables
```javascript
// This is Example of Variables
let carName = "Volvo";
```

2. Constants
```javascript
const carName = "Koenigsegg";
```
### Primitive Types -
3. Primitive Types
```javascript
let name = "John";          // String Literal
let age = 20;               // Number Literal
let isApproved = true;      // Boolean Literal
let firstName = undefined;  // 'undefined' not so common
let lastName = null;        // Clear the value of a Varaible 

// JavaScript is a Dynamic Language
```
### Reference Types -
4. Objects
```javascript
let person = {
  name: 'John',
  age: 20
};
// For selection
// Dot Notation
person.name = 'Harry';

// Bracket Notation
person['name'] = 'Harry';
```

5. Arrays
```javascript
let selectedColors = ['red', 'blue'];

// We can store 🏪 different types in an array
```

5. Functions
```javascript
function greet(name) {
  console.log('Hello ' + name);     // Body of the function
}

greet('Jonas');                     // Calling a function
greet('Martha');

// Functions are Fundamental building block
```

6. Types of Functions
```javascript
// Performing a task

// calculating a value
function square(number) {
  return number * number;
}

console.log(square(2));
```
