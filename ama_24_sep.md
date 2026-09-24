# Technical Questions and Answers

## 1. What is `JSON.stringify()`?
`JSON.stringify()` converts a JavaScript value or object into a JSON string. It is commonly used when sending data to an API or storing it as text.

## 2. What is the `document` object in JavaScript?
The `document` object represents the HTML page loaded in the browser. We use it to access and change HTML elements.

## 3. What is JavaScript?
JavaScript is a programming language mainly used to make web pages interactive. It can handle events, change the DOM, and work with APIs.

## 4. Why do we use DOM?
DOM stands for **Document Object Model**. It allows JavaScript to access and modify HTML elements dynamically.

## 5. Why do we use Promises?
Promises are used to handle asynchronous operations. They make tasks like API calls easier to manage.

## 6. What are the status codes in APIs?
API status codes tell us what happened with a request.

- **2xx** – Success
- **3xx** – Redirection
- **4xx** – Client error
- **5xx** – Server error

## 7. What happens when the browser encounters a CSS `<link>` tag while rendering?
The browser starts downloading the CSS file. CSS is generally render-blocking, so the browser may wait for it before painting the page.

## 8. What are the types of web applications?
Some common types are:

- Static web applications
- Dynamic web applications
- Single Page Applications (SPA)
- Multi Page Applications (MPA)
- Progressive Web Apps (PWA)

## 9. What is the difference between `setTimeout()` and `setInterval()`?
`setTimeout()` runs a function once after a specified delay. `setInterval()` runs a function repeatedly after a specified interval.

## 10. What is `stopPropagation()`?
`stopPropagation()` stops an event from moving to its parent elements. It is mainly used to prevent event bubbling.

## 11. What is the full form of DDL in SQL, and what are the DDL commands?
DDL stands for **Data Definition Language**. It is used to create or change the structure of database objects.

Common DDL commands are:
- `CREATE`
- `ALTER`
- `DROP`
- `TRUNCATE`

## 12. What are the states of Promises?
A Promise has three states:

- **Pending** – The operation is still running.
- **Fulfilled** – The operation completed successfully.
- **Rejected** – The operation failed.

## 13. How do you target an element's style in JavaScript?
We can select an element and use its `style` property.

Example:
```js
const heading = document.querySelector("h1");
heading.style.color = "blue";
```
