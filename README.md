# Library Books Management System

A full-stack CRUD application for managing library book records, built with 
React, Node.js, Express, and MongoDB — developed as part of an IBM Knowledge 
Transfer internship task.

## 📌 Project Description

This project implements a Library Books Management System where users can 
create, read, update, and delete book records through a React-based 
dashboard, backed by a RESTful Express API connected to MongoDB via Mongoose.

## 🛠️ Technologies Used

- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Frontend:** React (JSX), CSS
- Git & GitHub

## 📁 Project Structure
KT_4_Task/
├── Backend/
│   ├── index.js          # Express server + MongoDB connection setup
│   ├── book.js            # Mongoose schema for books
│   ├── routes.js          # API routes for book CRUD operations
│   ├── package.json
│   └── package-lock.json
├── Frontend/
│   ├── index.html
│   ├── app.jsx             # Library book management functionality
│   ├── dashboard.jsx       # Dashboard component for library CRUD
│   ├── index.css
│   ├── app.css
│   ├── package.json
│   └── package-lock.json
└── README.md
## ⚙️ Installation & Setup

### Backend

```bash
# 1. Clone the repository
git clone <your-github-repository-link>

# 2. Navigate to the backend folder
cd KT_4_Task/Backend

# 3. Install dependencies
npm install

# 4. Start the server
node index.js
```

Make sure MongoDB is running locally (or update the connection string in 
`index.js` to point to your MongoDB Atlas / remote instance).

### Frontend

```bash
# 1. Navigate to the frontend folder
cd KT_4_Task/Frontend

# 2. Install dependencies
npm install

# 3. Start the frontend
npm start
```

## ✅ Features

- Add new books to the library
- View all book records via the dashboard
- Update existing book details
- Delete book records
- MongoDB-backed persistent storage via Mongoose schema

## 🧪 Testing

- API routes tested for correct CRUD behavior
- Frontend dashboard verified against live backend responses

## 📌 Conclusion

This project demonstrates a complete full-stack CRUD workflow — a React 
frontend communicating with an Express/MongoDB backend — built as part of 
IBM's Knowledge Transfer internship training.
