#  Book API (Node.js + Express)

A simple RESTful API for managing a list of books using Node.js and Express. This project demonstrates basic CRUD operations (Create, Read, Update, Delete) with in-memory data storage (no database).

##  Features

- GET all books
- POST a new book
- PUT (update) an existing book by ID
- DELETE a book by ID

## 🛠 Tech Stack

- Node.js
- Express.js
- Postman (for testing)

##  Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/nagarajhegde18/book-api.git
   cd book-api
   
npm install

Start the server
node index.js
Server will run on: http://localhost:3000

1.GET:
http://localhost:3000/books


2.POST:
{
    "message": "Book added successfully",
    "book": {
        "id": "1",
        "title": "Java",
        "author": "James"
    }
}

3.PUT:
http://localhost:3000/books/1
{
    "message": "Book updated successfully",
    "book": {
        "id": "1",
        "title": "Java",
        "author": "James"
    }
}

4.DELETE:
http://localhost:3000/books/1
{
    "message": "Book deleted successfully"
}

