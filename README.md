# 📚 Library Management System (LMS)

A full-stack **Library Management System** built using **Node.js**, **Express**, **MongoDB**, and **React.js**.  
This application allows administrators to manage books, users, and borrowing records, while users can browse, borrow, and return books online.

---

## 🚀 Features
### 👨‍💻 User
- User registration and login  
- Browse available books  
- Search books by title, author, or category  
- Borrow and return books  
- View borrowing history  

### 🛠 Admin
- Add, update, and delete books  
- Manage users  
- View all borrow/return transactions  
- Track overdue books  

---

## 🏗 Tech Stack
**Frontend**  
- React.js  
- Redux (for state management)  
- Material UI / CSS styling  

**Backend**  
- Node.js  
- Express.js  
- MongoDB (Mongoose ODM)  

---

## 📂 Project Structure
```
LMS-main/
│── client/         # React frontend
│── models/         # Mongoose schemas
│── routes/         # API routes
│── middleware/     # Authentication & error handling
│── server.js       # Express app entry point
│── package.json    # Backend dependencies
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/library-management-system.git
cd library-management-system
```

### 2️⃣ Install backend dependencies
```bash
npm install
```

### 3️⃣ Install frontend dependencies
```bash
cd client
npm install
```

---

## ▶️ Running the Application

### Run backend
```bash
npm start
```

### Run frontend
```bash
cd client
npm start
```

---

## 🔐 Environment Variables
Create a `.env` file in the backend root:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

---

## 📌 API Endpoints
| Method | Endpoint          | Description          |
|--------|-------------------|----------------------|
| POST   | /api/auth/register| Register user        |
| POST   | /api/auth/login   | Login user           |
| GET    | /api/books        | Get all books        |
| POST   | /api/books        | Add new book (admin) |

---

## 📜 License
This project is licensed under the MIT License.
