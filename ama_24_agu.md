## 1. Where do we use the `git push` command?

The `git push` command is used to upload committed changes from the local Git repository to a remote repository such as GitHub or GitLab.

```bash
git push origin main
```

---

## 2. Which command is used to display the username and email configured in Git?

```bash
git config --global --list
```

---

## 3. What are CROSS JOIN and INNER JOIN?

### CROSS JOIN

A `CROSS JOIN` returns every possible combination of rows from two tables.

If one table has 3 rows and another has 4 rows, the result can contain `3 × 4 = 12` rows.

### INNER JOIN

A `INNER JOIN` returns only matching columns from two tables.

---

## 4. What is `__init__` in Python?

`__init__` is a special method that is automatically called when an object is created. It is commonly used to initialize object attributes.

---

## 5. What is the difference between Selection and Projection?

Both are relational database operations.

### Selection

Selection chooses **rows** that satisfy a condition.

### Projection

Projection chooses **columns** from a table.

---

## 6. Why do we use the `yield` and `return` keywords in Python?

### `return`

`return` sends a value back from a function and ends the function execution.

### `yield`

`yield` is used to create a generator. It produces values one at a time and pauses the function.

---

## 7. How can we move changes from the staging area back to the working area?

Use:

```bash
git restore --staged <file>
```

To unstage all files:

```bash
git restore --staged .
```

---

## 8. How do you exit the PostgreSQL server?

If you are inside the PostgreSQL `psql` terminal, use:

```sql
\q
```

This exits `psql` and returns to the normal terminal.

---

## 9. What is SRP in Python?

**SRP stands for Single Responsibility Principle.**

It is the first principle of SOLID. It means a class should have **one main responsibility and one reason to change**.

---

## 10. What is Runtime Polymorphism?

Runtime polymorphism occurs when the method to be executed is determined at runtime based on the object being used.

---

## 11. How can you find the IP address of Google?

You can use:

```bash
ping google.com
```

You can also use:

```bash
nslookup google.com
```

---

## 12. What is a method in Python?

A method is a function defined inside a class that performs an operation related to an object or class.

---

## 13. What is the difference between Git and GitLab?

### Git

Git is a **distributed version control system** used to track changes in source code.

### GitLab

GitLab is a **platform for hosting Git repositories** and provides additional development and collaboration features such as merge requests, and project management.

---
