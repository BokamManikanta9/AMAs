## 1. How do you connect a database in Django?

We connect a database using the `DATABASES` setting in `settings.py`.

Example for PostgreSQL:

```python
DATABASES = {
    "default": {
        "ENGINE": "django.db.backends.postgresql",
        "NAME": "mydb",
        "USER": "postgres",
        "PASSWORD": "password",
        "HOST": "localhost",
        "PORT": "5432",
    }
}
```

Django then uses the database through its ORM.

## 2. What is the difference between `position: absolute` and `position: relative`?

`relative` keeps the element in the normal page flow and allows us to move it from its original position.

`absolute` removes the element from the normal flow and positions it relative to its nearest positioned ancestor.

## 3. What is the Django request-response flow?

The basic flow is:

```text
Browser → URL → urls.py → View → Model/Database → Template → Response → Browser
```

The browser sends a request, Django finds the correct view, the view processes it, and Django sends a response back.

## 4. Is Django middleware server-side or client-side?

Django middleware is **server-side**.

It runs on the Django server and processes requests and responses.

## 5. What is WSGI?

WSGI stands for **Web Server Gateway Interface**.

It is a standard interface between a Python web application and a web server. Django provides a `wsgi.py` file for this purpose.

## 6. What is the difference between `models` and `Model` in Django?

`models` is the Django module that provides classes and functions for creating database models.

`Model` is a class inside `django.db.models` that we inherit from when creating our own model.

```python
from django.db import models

class Student(models.Model):
    name = models.CharField(max_length=100)
```

Here, `models` is the module and `Model` is the base class.

## 7. What are objects in Django?

Objects are instances of Python classes.

For example:

```python
student = Student.objects.get(id=1)
```

Here, `student` is an object containing the data of that particular student.

## 8. What is the use of `admin.py`?

`admin.py` is used to register models with Django's admin panel.

```python
from django.contrib import admin
from .models import Student

admin.site.register(Student)
```

After registering it, we can manage `Student` records through the Django admin site.

## 9. What is the full form of UTF?

UTF stands for **Unicode Transformation Format**.

It is used to represent Unicode characters in formats such as UTF-8 and UTF-16.

## 10. Where should we store our keys in Django?

Secret keys and other sensitive values should not be written directly in the source code.

They are commonly stored in **environment variables** or a secure secrets manager.

Example:

```python
import os

SECRET_KEY = os.environ.get("SECRET_KEY")
```
