# JavaScript Developer Interview Questions and Answers (2 Years of Experience)

This repository contains 25 commonly asked JavaScript interview questions and answers for a developer with 2 years of experience. These questions cover various JavaScript concepts such as ES6 features, asynchronous programming, data structures, and more.

## Table of Contents
1. [Difference Between `var`, `let`, and `const`](#1-difference-between-var-let-and-const)
2. [Arrow Functions](#2-what-are-arrow-functions-in-javascript)
3. [Promises](#3-what-is-a-promise-in-javascript)
4. [Template Literals](#4-what-are-template-literals)
5. [Destructuring](#5-explain-destructuring-in-javascript)
6. [Spread and Rest Operator](#6-what-are-the-spread-and-rest-operators)
7. [Difference Between `==` and `===`](#7-what-is-the-difference-between--and-)
8. [Hoisting](#8-what-is-hoisting-in-javascript)
9. [Closures](#9-explain-closures-in-javascript)
10. [Event Delegation](#10-what-is-event-delegation-in-javascript)
11. [Async/Await](#11-how-does-asyncawait-work-in-javascript)
12. [What is a Callback Function](#12-what-is-a-callback-function-in-javascript)
13. [JavaScript Object Notation (JSON)](#13-what-is-json)
14. [JavaScript Event Loop](#14-explain-the-event-loop-in-javascript)
15. [Higher-Order Functions](#15-what-are-higher-order-functions-in-javascript)
16. [Difference Between `null` and `undefined`](#16-what-is-the-difference-between-null-and-undefined)
17. [Immutability in JavaScript](#17-what-is-immutability-in-javascript)
18. [Difference Between `forEach` and `map`](#18-explain-the-difference-between-foreach-and-map-methods)
19. [Prototypal Inheritance](#19-what-is-prototypal-inheritance-in-javascript)
20. [Deep and Shallow Copy](#20-what-is-the-difference-between-a-deep-and-shallow-copy)
21. [Strict Mode](#21-what-is-strict-mode-in-javascript)
22. [IIFE (Immediately Invoked Function Expression)](#22-what-is-an-iife)
23. [Debouncing and Throttling](#23-explain-debouncing-and-throttling-in-javascript)
24. [Modules in JavaScript](#24-how-do-modules-work-in-javascript)
25. [Type Coercion](#25-what-is-type-coercion-in-javascript)

---

### 1. Difference between `var`, `let`, and `const`?
- `var` has function scope, whereas `let` and `const` have block scope.
- `let` allows variable reassignment, but `const` does not.
- `var` is hoisted and initialized with `undefined`, while `let` and `const` are hoisted but not initialized.

### 2. What are arrow functions in JavaScript?
Arrow functions are a concise syntax for writing functions. They don't have their own `this` context, making them ideal for callbacks.

### 3. What is a promise in JavaScript?
A promise is an object representing the eventual completion or failure of an asynchronous operation. It has three states: pending, fulfilled, and rejected.

### 4. What are template literals?
Template literals are a way to include variables and expressions in strings using backticks (`), supporting multi-line strings and string interpolation with `${}`.

### 5. Explain destructuring in JavaScript.
Destructuring is a syntax for extracting values from arrays or objects into distinct variables.

### 6. What are the spread and rest operators?
The spread operator (`...`) allows an iterable (array or object) to be expanded, while the rest operator is used to bundle remaining elements into an array.

### 7. What is the difference between `==` and `===`?
- `==` performs type coercion before comparison, whereas `===` checks both value and type without coercion.

### 8. What is hoisting in JavaScript?
Hoisting is JavaScript's default behavior of moving declarations to the top of the current scope before code execution. Variables declared with `var` are hoisted with `undefined`.

### 9. Explain closures in JavaScript.
A closure is a function that remembers its lexical scope even when the function is executed outside of that scope, allowing access to variables in the outer scope.

### 10. What is event delegation in JavaScript?
Event delegation allows us to attach a single event listener to a parent element and handle events from child elements, leveraging event bubbling.

### 11. How does `async`/`await` work in JavaScript?
`async`/`await` is a syntax for writing asynchronous code that looks synchronous. It is built on Promises, where `await` pauses code execution until a promise is resolved.

### 12. What is a callback function in JavaScript?
A callback is a function passed as an argument to another function and is executed after the completion of that function.

### 13. What is JSON?
JSON (JavaScript Object Notation) is a lightweight data interchange format that is easy for humans to read and write and easy for machines to parse and generate.

### 14. Explain the event loop in JavaScript.
The event loop allows JavaScript to perform non-blocking operations by offloading tasks like I/O to the browser and executing the callback once the task is completed.

### 15. What are higher-order functions in JavaScript?
Higher-order functions are functions that can take other functions as arguments or return them as results, such as `map()`, `filter()`, and `reduce()`.

### 16. What is the difference between `null` and `undefined`?
- `undefined` means a variable has been declared but not assigned a value.
- `null` is an assignment value that represents no value or an empty object.

### 17. What is immutability in JavaScript?
Immutability means that once an object or variable is created, it cannot be changed. This concept is often applied to arrays and objects in functional programming.

### 18. Explain the difference between `forEach` and `map` methods.
- `forEach` iterates over an array and executes a provided function for each element but does not return anything.
- `map` creates and returns a new array by applying the function to each element.

### 19. What is prototypal inheritance in JavaScript?
Prototypal inheritance is a feature where objects can inherit properties and methods from other objects. Every object has a prototype object from which it inherits.

### 20. What is the difference between a deep and shallow copy?
- A shallow copy only copies the top-level properties of an object.
- A deep copy recursively copies all levels of the object and its nested objects.

### 21. What is strict mode in JavaScript?
Strict mode is a way to opt into a stricter version of JavaScript, catching common coding errors like undeclared variables and preventing the use of certain JavaScript features.

### 22. What is an IIFE (Immediately Invoked Function Expression)?
An IIFE is a function that runs as soon as it is defined. It helps create a private scope and avoid polluting the global scope.

### 23. Explain debouncing and throttling in JavaScript.
- Debouncing limits the execution of a function by delaying its execution until after a certain period of time has passed since the last time it was invoked.
- Throttling ensures that a function is executed at most once during a specified time interval.

### 24. How do modules work in JavaScript?
Modules are pieces of reusable code that can be imported or exported between files using `export` and `import` syntax. They help organize code and avoid namespace pollution.

### 25. What is type coercion in JavaScript?
Type coercion is the automatic or implicit conversion of values from one data type to another, such as converting a string to a number during a comparison with `==`.

---
