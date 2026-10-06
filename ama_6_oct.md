## 1. What is `get_object_or_404()`?
`get_object_or_404()` tries to get an object from the database. If it exists, it returns it; otherwise, Django returns a **404 Not Found** response.

## 2. What is the use of the `Path` class in `settings.py`?
`Path` is used to work with file and folder paths.

```python
BASE_DIR = Path(__file__).resolve().parent.parent
```

## 3. In a project, where do we use one-to-one and many-to-many relationships?
A **One-to-One** relationship is used when one record is connected to only one other record, such as a user and profile.

A **Many-to-Many** relationship is used when many records can be connected to many other records, such as user - user.

## 4. What is the event loop in JavaScript?
The event loop helps JavaScript handle asynchronous tasks without blocking the main thread.

It checks the call stack and queues and moves waiting callbacks to the stack when it is free.

## 5. What is the `F` class in Django?
`F` is used to refer to the value of a database field inside a query.

It is useful for calculations using existing database values.

```python
from django.db.models import F

Product.objects.update(price=F("price") + 10)
```

## 6. When we load a website, are the frontend and backend both handled by Django?

Django mainly handles the **backend**, such as URLs, views, business logic, and database operations. HTML, CSS, and JavaScript mainly run in the browser.

## 7. Why do we use `set_password()` when storing a password?
`set_password()` hashes the password before storing it in the database.

```python
user.set_password("mypassword")
user.save()
```

If we store the password directly, it may be stored as plain text and Django's password authentication will not work correctly.

## 8. What is `models.CASCADE`?
`models.CASCADE` is used with relationships such as `ForeignKey`.

It means that when the referenced parent object is deleted, the related objects are also deleted.

```python
user = models.ForeignKey(
    User,
    on_delete=models.CASCADE
)
```

## 9. What is the `reverse()` function in Django?
`reverse()` generates a URL using the name of a URL pattern instead of writing the URL manually.

```python
from django.urls import reverse

url = reverse("home")
```

This makes URL handling easier when URL paths change.

## 10. What will be returned when we write .first() for a query?

`.first()` returns the first object from the QuerySet.

```python
Student.objects.all().first()
```
It returns the first Student object, or None if the QuerySet is empty.
