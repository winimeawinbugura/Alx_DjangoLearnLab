# Update Operation

This document demonstrates how to update an existing Book record using the Django ORM.

## Command
```python
from bookshelf.models import Book
book = Book.objects.get(title="1984")
book.title = "Nineteen Eighty-Four"
book.save()
book
