# Build-a-RESTful-API-using-Node.js-and-Express-Assign-1

# 👨‍💻 Node JS RESTful API

This is a simple RESTful API built using **Node.js** and **Express** to manage a list of users.  
It demonstrates basic CRUD operations, middleware usage, error handling, and in-memory data storage.

---

## 🔧 Features

- Get all users
- Get a specific user by ID
- Add a new user
- Update a user (full or partial)
- Delete a user
- Middleware for request logging
- Validation middleware for required fields
- In-memory data source (no database required)

---

## 🛠 Technologies Used

- Node.js
- Express.js
- ThunderClient (for testing)

---

## 📦 Setup & Installation

```bash
# Clone the repository
git clone "https://github.com/Omkar0210/Build-a-RESTful-API-using-Node.js-and-Express-Assign-1.git"

# Navigate to the project directory
cd RESTful-API-using-Node.js-and-Express.git

# Install dependencies
npm install

# Start the server
npm start

🚀 API Endpoints

Method	Endpoint	  Description
GET	    /users	    Get all users
GET	    /users/:id	Get a user by ID
POST	  /user	      Add a new user
PUT	    /user/:id	  Update a user (full)
PATCH	  /user/:id	  Update a user (partial)
DELETE	/user/:id	  Delete a user by ID


📂 Sample User Object
{
  "id": 1,
  "firstName": "omkar",
  "lastName": "gunjal",
  "hobby": "Riding"
}
