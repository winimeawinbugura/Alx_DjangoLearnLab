# Retrieve Operation

This document demonstrates how to retrieve and display all attributes of a Book instance using the Django ORM.

## Command
```python
from bookshelf.models import Book
Book.objects.all().values()
