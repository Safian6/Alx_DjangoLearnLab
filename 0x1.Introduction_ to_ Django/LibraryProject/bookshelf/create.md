from bookshelf.models import Book:

book = Book.object.create(title="1984", author="George Orwell", publication_year=1949)
book.save()

Expected output: Book instance created successfully