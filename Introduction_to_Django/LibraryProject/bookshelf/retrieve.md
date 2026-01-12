# Retrieve Operation

This document demonstrates how to retrieve a Book record using Django’s ORM.

## Command
```python
from bookshelf.models import Book
book = Book.objects.get(title="1984")
book
