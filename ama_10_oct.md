## 1. What is Elasticsearch?
Elasticsearch is a search and analytics tool that helps find information quickly, even in large amounts of data.

## 2. What is Redis?
Redis is an in-memory data store often used for caching and fast data access. It can also be used as a message broker for background tasks.

## 3. What is the difference between `HttpResponse` and `HttpResponseForbidden`?
`HttpResponse` sends a response to the browser, usually with status code **200** by default. `HttpResponseForbidden` sends a **403 Forbidden** response when the user is not allowed to access something.

## 4. What does `@login_required` mean?
`@login_required` is a Django decorator that allows a view to be accessed only by logged-in users. If the user is not logged in, Django redirects them to the login page.

## 5. What is Celery?
Celery is a tool for running tasks in the background. For example, an application can use it to send emails or process data without making the user wait for the task to finish.

## 6. What is the difference between `render()` and `HttpResponse`?
`render()` combines a template with context data and returns an HTTP response. `HttpResponse` sends the response content directly, such as plain text or HTML.

## 7. What is the difference between a primary key and a unique key?
A **primary key** uniquely identifies each row and cannot contain `NULL`. A **unique key/constraint** prevents duplicate values, and whether it allows `NULL` depends on the database.

## 8. What is the difference between authentication and authorization?
**Authentication** checks who a user is, usually through login. **Authorization** checks what that user is allowed to access or do.

## 9. What is the difference between `var`, `let`, and `const`?
`var` is function-scoped and can be redeclared. `let` is block-scoped and can be reassigned. `const` is block-scoped and cannot be reassigned after initialization.

## 10. What is middleware?
Middleware is a layer that processes requests before they reach a view and responses before they are sent to the browser. In Django, it is commonly used for security, sessions, authentication, and other shared tasks.
