# BookShelf-API-Node.js-REST-Service-No-Database-
# 📚 Book API – Node.js & Express CRUD REST API

A simple, fully in-memory RESTful API to manage a list of books. Built using Node.js and Express,
it supports full CRUD operations with no database — perfect for learning or lightweight API testing.

This is a simple, fully in-memory RESTful API to manage a list of books. Built using **Node.js** and **Express**, it supports full CRUD operations with no database — perfect for learning or lightweight API testing.


---

## 🚀 Features

- 🔍 `GET /books` – Retrieve all books
- 📘 `GET /books/:id` – Get a book by ID
- ➕ `POST /books` – Add a new book
- ✏️ `PUT /books/:id` – Update an existing book
- ❌ `DELETE /books/:id` – Delete a book by ID

All data is stored in memory, meaning it resets when the server restarts.

---

## 🛠️ Built With

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Postman](https://www.postman.com/) for testing

---

## 📁 Project Structure

📦 book-api/
┣ 📄 package.json
┣ 📄 package-lock.json
┗ 📄 server.js

yaml
Copy
Edit

---

## ⚙️ Getting Started

### 📦 Installation

Installation:
• git clone https://github.com/EVinayKumar89/book-api.git
• cd book-api
• npm install
Run the server:
• npm start
• Server runs at http://localhost:3000

The server will start at:

arduino
Copy
Edit
http://localhost:3000
📬 API Endpoints
Method	Endpoint	Description	Request Body (JSON)
GET	/books	Get all books	–
GET	/books/:id	Get book by ID	–
POST	/books	Add new book	{ "title": "", "author": "" }
PUT	/books/:id	Update book by ID	{ "title": "", "author": "" }
DELETE	/books/:id	Delete book by ID	–

🧪 Test with Postman
Open Postman

Send requests to http://localhost:3000/books

Use GET, POST, PUT, DELETE methods to test functionality

