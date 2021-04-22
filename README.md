# 🔥 javaScript Guide

### 🔥 javaScript.js

<p align=center>  <img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg" alt="Javascript Logo" width="150px" />  </p>

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

<details>
  <summary>'Basics Of Javascript'</summary>

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
let name = "John"; // String Literal
let age = 20; // Number Literal
let isApproved = true; // Boolean Literal
let firstName = undefined; // 'undefined' not so common
let lastName = null; // Clear the value of a Varaible

// JavaScript is a Dynamic Language
```

### Reference Types -

4. Objects

```javascript
let person = {
  name: "John",
  age: 20,
};
// For selection
// Dot Notation
person.name = "Harry";

// Bracket Notation
person["name"] = "Harry";
```

5. Arrays

```javascript
let selectedColors = ["red", "blue"];

// We can store 🏪 different types in an array
```

5. Functions

```javascript
function greet(name) {
  console.log("Hello " + name); // Body of the function
}

greet("Jonas"); // Calling a function
greet("Martha");

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

</details>

## Operators

<details>
  <summary>'Operators Of Javascript'</summary>

JavaScript Operators

```javascript
// Arithmetic
// Assignment
// Comparison
// Logical
// Bitwise
```

1. Arithmetic Operators

```javascript
let x = 10;
let y = 3;

console.log(x + y);
console.log(x - y);
console.log(x * y);
console.log(x / y);
console.log(x % y);
console.log(x ** y);

// Increment (++)
console.log(x++);

// Decrement (--)
console.log(x--);
```

2. Assignment Operators

```javascript
let x = 10;

x = x + 5;
x += 5;

x = x * 3;
x *= 3;
```

3. Comparison Operators

```javascript
let x = 1;

console.log(x > 0);
console.log(x >= 0);
console.log(x < 0);
console.log(x <= 0);

// Equality
console.log(x === 1);
console.log(x !== 1);
```

4. Equality Operators

```javascript
// Strict Equality (Type + Value)
console.log(1 === 1); // True
console.log("1" === 1); // False

// Lose Equality
console.log(1 == 1); // True
console.log("1" == 1); // True
console.log(true == 1); // True
```

5. Ternary Operators

```javascript
let points = 110;
let type = points > 100 ? "gold" : "silver";

console.log(type);
```

5. Logical Operators with Booleans

```javascript
// Logical AND (&&)
// Returns TRUE if both operands are TRUE
console.log(true && true);

// Logical OR (||)
// Returns TRUE if one of the operands are TRUE
console.log(true || true);

// NOT (!)
let this = !that;
```

6. Logical Operators with Non-Booleans

```javascript
// Falsy (false)
// [undefined, null, 0, false, '', NaN]

// Anything that is not Falsy -> Truthy

// Short-Circuiting
```

7. BitWise Operators

```javascript
// Binary
// 1 = 00000001
// 2 = 00000010
// R = 00000011

console.log(1 | 2); // Bitwise OR
// Result = 3
console.log(1 & 2); // Bitwise AND
// Result = 0
```

</details>
