# JavaScript and Python Questions & Answers

## 1. Name some methods of array?
Some common array methods are `map()`, `filter()`, `reduce()`, `push()`, `pop()`, `shift()`, and `unshift()`.  
They are used to transform, filter, add, remove, or process array elements.

## 2. What is reduce in array?
`reduce()` is used to process all elements of an array and return one final value.  
For example, it can be used to calculate the total salary of all employees.

## 3. What is init method in Python?
`__init__()` is a special method in Python classes.  
It runs automatically when an object is created and is mainly used to initialize the object's properties.

## 4. What is catch block in promises?
`.catch()` is used to handle errors or rejected Promises.  
If a Promise fails, the error can be received inside the `.catch()` block.

## 5. What is the difference between `Promise.any()` and `Promise.race()`?
`Promise.any()` returns the first Promise that successfully completes and ignores rejected Promises until one succeeds.  
`Promise.race()` returns the first Promise that settles, whether it is fulfilled or rejected.

## 6. What is call stack?
The call stack is a place where JavaScript keeps track of function calls.  
When a function starts, it is added to the stack, and when it finishes, it is removed.

## 7. How to handle errors in Promise?
We can handle Promise errors using `.catch()`.  
With `async/await`, we normally use `try...catch` to handle errors.

## 8. What is hoisting?
Hoisting is JavaScript's behavior of processing declarations before the code is executed.  
Because of this, some variables and functions can be referenced before their declaration, depending on how they are declared.

## 9. What is closure?
A closure happens when an inner function remembers and can access variables from its outer function.  
Even after the outer function has finished, the inner function can still use those variables.

## 10. What is `throw` in JS?
`throw` is used to create and send an error manually.  
It stops the normal execution and passes the error to an error handler such as `catch`.

## 11. What is a higher-order function?
A higher-order function is a function that takes another function as an argument or returns a function.  
Examples include `map()`, `filter()`, and `reduce()`.

## 12. What is `null` and `undefined`?
`null` means we intentionally set a variable to have no value.  
`undefined` usually means a variable has been declared but no value has been assigned to it.
