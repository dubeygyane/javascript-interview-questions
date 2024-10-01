# JavaScript Interview Questions for 4-Year Experience

This document contains commonly asked JavaScript interview questions and answers for developers with 4 years of experience.

## Table of Contents
1. [What is the event loop in detail?](#1-what-is-the-event-loop-in-detail)
2. [What are Promises and how are they different from callbacks?](#2-what-are-promises-and-how-are-they-different-from-callbacks)
3. [What is the difference between synchronous and asynchronous code?](#3-what-is-the-difference-between-synchronous-and-asynchronous-code)
4. [What is memoization in JavaScript?](#4-what-is-memoization-in-javascript)
5. [What is tail call optimization?](#5-what-is-tail-call-optimization)
6. [What are generator functions?](#6-what-are-generator-functions)
7. [What is the `this` keyword and how is it scoped?](#7-what-is-the-this-keyword-and-how-is-it-scoped)
8. [Explain JavaScript prototypes and inheritance?](#8-explain-javascript-prototypes-and-inheritance)
9. [What are WeakMap and WeakSet in JavaScript?](#9-what-are-weakmap-and-weakset-in-javascript)
10. [How does JavaScript garbage collection work?](#10-how-does-javascript-garbage-collection-work)
11. [What is functional programming in JavaScript?](#11-what-is-functional-programming-in-javascript)
12. [What are the differences between `Object.create()` and `new Object()`?](#12-what-are-the-differences-between-objectcreate-and-new-object)
13. [What is event delegation?](#13-what-is-event-delegation)
14. [Explain the concept of closures in JavaScript.](#14-explain-the-concept-of-closures-in-javascript)
15. [What is the `bind` method in JavaScript?](#15-what-is-the-bind-method-in-javascript)
16. [What are module patterns?](#16-what-are-module-patterns)
17. [What is destructuring and how is it used?](#17-what-is-destructuring-and-how-is-it-used)
18. [What is a service worker?](#18-what-is-a-service-worker)
19. [Explain how the `fetch` API works.](#19-explain-how-the-fetch-api-works)
20. [What are the differences between `Array.map()` and `Array.forEach()`?](#20-what-are-the-differences-between-arraymap-and-arrayforeach)
21. [What is a higher-order function?](#21-what-is-a-higher-order-function)
22. [How does `setTimeout` work?](#22-how-does-settimeout-work)
23. [What is the difference between shallow copy and deep copy?](#23-what-is-the-difference-between-shallow-copy-and-deep-copy)
24. [What is the purpose of the `async`/`await` syntax?](#24-what-is-the-purpose-of-the-asyncawait-syntax)
25. [What is a polyfill in JavaScript?](#25-what-is-a-polyfill-in-javascript)

---

### 1. What is the event loop in detail?
The event loop is a crucial mechanism that allows JavaScript to perform non-blocking operations. It continuously checks the call stack and the message queue to manage asynchronous operations. When the call stack is empty, the event loop pushes the first message from the queue to the stack, executing it.

### 2. What are Promises and how are they different from callbacks?
Promises are objects representing the eventual completion (or failure) of an asynchronous operation, providing a cleaner alternative to callbacks by allowing chaining of `.then()` for success and `.catch()` for errors. They avoid callback hell and provide better error handling.

### 3. What is the difference between synchronous and asynchronous code?
Synchronous code executes sequentially, blocking further execution until the current operation completes. Asynchronous code allows other operations to continue while waiting for a response, improving efficiency and user experience.

### 4. What is memoization in JavaScript?
Memoization is an optimization technique that caches the results of expensive function calls and returns the cached result when the same inputs occur again, improving performance.

### 5. What is tail call optimization?
Tail call optimization is a feature that allows a function to call another function as its last operation without growing the call stack, reducing memory consumption and preventing stack overflow errors.

### 6. What are generator functions?
Generator functions are special functions that can be paused and resumed, allowing you to iterate over a sequence of values. They use the `function*` syntax and `yield` keyword to return values incrementally.

### 7. What is the `this` keyword and how is it scoped?
The `this` keyword refers to the context in which a function is called. Its value can vary based on how the function is invoked (e.g., as a method, constructor, or event handler).

### 8. Explain JavaScript prototypes and inheritance.
JavaScript uses prototypal inheritance, where objects can inherit properties and methods from other objects through the prototype chain, allowing for reusable and shared behavior.

### 9. What are WeakMap and WeakSet in JavaScript?
- **WeakMap**: A collection of key-value pairs where keys are objects and values can be any value. WeakMap does not prevent garbage collection of the keys, making it memory efficient.
- **WeakSet**: A collection of objects, similar to a Set, where the objects can be garbage collected if there are no other references to them.

### 10. How does JavaScript garbage collection work?
JavaScript uses automatic garbage collection to reclaim memory by identifying and disposing of objects that are no longer reachable from the root references. The most common algorithm used is Mark-and-Sweep.

### 11. What is functional programming in JavaScript?
Functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing state or mutable data. Key concepts include first-class functions, higher-order functions, and immutability.

### 12. What are the differences between `Object.create()` and `new Object()`?
- `Object.create()` creates a new object with the specified prototype object and properties, allowing for better control over inheritance.
- `new Object()` creates a new object but initializes it as an empty object with no prototype chain.

### 13. What is event delegation?
Event delegation is a technique that allows a single event listener to manage events for multiple child elements. It leverages event bubbling to handle events at a higher level in the DOM hierarchy.

### 14. Explain the concept of closures in JavaScript.
Closures are functions that have access to their outer lexical scope even when the function is executed outside that scope. They enable data encapsulation and can be used to create private variables.

### 15. What is the `bind` method in JavaScript?
The `bind` method creates a new function that, when called, has its `this` keyword set to a specified value. It can also take any number of arguments to pre-fill for the new function.

### 16. What are module patterns?
Module patterns are a way to encapsulate private and public members in JavaScript, promoting better organization and reusability of code. They often use closures to keep private variables hidden.

### 17. What is destructuring and how is it used?
Destructuring is a syntax that allows unpacking values from arrays or properties from objects into distinct variables, making code cleaner and more concise.

### 18. What is a service worker?
A service worker is a script that the browser runs in the background, separate from a web page, enabling features like offline capabilities, background sync, and intercepting network requests.

### 19. Explain how the `fetch` API works.
The `fetch` API provides a modern way to make HTTP requests in JavaScript, returning a Promise that resolves to the Response object representing the response to the request.

### 20. What are the differences between `Array.map()` and `Array.forEach()`?
- `Array.map()` creates a new array by applying a function to each element, while `Array.forEach()` executes a function for each element without returning a new array.

### 21. What is a higher-order function?
A higher-order function is a function that takes one or more functions as arguments or returns a function as its result, allowing for greater abstraction and reusability.

### 22. How does `setTimeout` work?
`setTimeout` is a built-in function that executes a specified function after a certain delay in milliseconds. It is often used for scheduling tasks or creating timeouts.

### 23. What is the difference between shallow copy and deep copy?
- A shallow copy duplicates only the top-level properties of an object. Nested objects are still referenced.
- A deep copy recursively duplicates all levels of the object, creating a completely independent copy.

### 24. What is the purpose of the `async`/`await` syntax?
The `async`/`await` syntax simplifies asynchronous programming by allowing developers to write asynchronous code that appears synchronous, improving readability and maintainability.

### 25. What is a polyfill in JavaScript?
A polyfill is code that provides functionality that is not natively supported in certain browsers, allowing developers to use modern features without worrying about compatibility.

---

## License
This content is open source and available under the [MIT License](LICENSE).
