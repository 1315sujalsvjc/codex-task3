# codex-task3
Create a REST API to Manage a List of Books Using Node.js and Express.
📚 Book Management REST API
This is a simple RESTful API built using Node.js and Express.js that allows you to create, read, update, and delete (CRUD) books in memory.

🚀 Features
Get all books

Get a single book by ID

Add a new book

Update a book by ID

Delete a book by ID

🛠️ Technologies Used
Node.js

Express.js

📁 Project Structure
pgsql
Copy
Edit
task3/
├── index.js
├── package.json
└── README.md
📦 Installation
Clone the repository (or download the project folder)

Open a terminal and navigate to the project directory:

bash
Copy
Edit
cd task3
Install dependencies:

bash
Copy
Edit
npm install
▶️ Running the Server
Start the server using:

bash
Copy
Edit
node index.js
You should see:

pgsql
Copy
Edit
Server is running on port 5000
The API will be available at:
http://localhost:5000

📬 API Endpoints
Method	Endpoint	Description
GET	/books	Get all books
POST	/books	Add a new book
PUT	/books/:id	Update a book by ID
DELETE	/books/:id	Delete a book by ID

📥 Example Request (POST)
http
Copy
Edit
POST /books
Content-Type: application/json

{
  "title": "The Alchemist",
  "author": "Paulo Coelho"
}
📤 Example Response
json
Copy
Edit
{
  "id": 1,
  "title": "The Alchemist",
  "author": "Paulo Coelho"
}
📝 Notes
This project uses an in-memory array to store books (data will reset on server restart).

No database is connected yet.

📌 License
This project is for educational purposes only.

