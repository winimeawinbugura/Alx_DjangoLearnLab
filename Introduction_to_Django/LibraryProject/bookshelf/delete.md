# Delete Operation

This document demonstrates how to delete a Book record using Django’s ORM and confirm that the deletion was successful.

## Command
```python
from bookshelf.models import Book
book = Book.objects.get(title="Nineteen Eighty-Four")
book.delete()
Book.objects.all()
