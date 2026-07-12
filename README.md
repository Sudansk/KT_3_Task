# School Management System

A backend-based application for managing student records, developed as part of an IBM-led Knowledge Transfer (KT) session for internship training.

## 📌 Project Description

The School Management System is a simple backend application built with Node.js and Express.js. It manages student details — Student ID, Name, Class, and Fees Status — through REST APIs, with data stored in a JSON file. A lightweight HTML/CSS/JS frontend consumes these APIs to display and manage records dynamically.

## 🛠️ Technologies Used

- Node.js
- Express.js
- JavaScript
- JSON (data storage)
- HTML, CSS, JavaScript (frontend)
- Postman (API testing)
- Git & GitHub

## 📁 Project Structure
KT_3_Task/
├── Backend/
│   ├── app.js
│   ├── package.json
│   └── students.json
├── Frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
└── README.md

## ⚙️ Installation & Setup

```bash
# 1. Clone the repository
git clone <your-github-repository-link>

# 2. Navigate to the Backend folder
cd KT_3_Task/Backend

# 3. Install dependencies
npm install

# 4. Start the server
node app.js
```

The server will run at `http://localhost:3000`.

## 🔗 API Endpoints

| Method | Endpoint            | Description             |
|--------|----------------------|--------------------------|
| GET    | `/students`          | Get all students         |
| GET    | `/students/:id`      | Get student by ID        |
| POST   | `/students/batch`    | Add new students         |
| PUT    | `/students/batch`    | Update student details   |
| DELETE | `/students/batch`    | Delete students          |

## 🧪 Testing

- APIs tested using Postman
- CRUD operations verified for correct responses and status codes

## 🌐 Frontend

- Built with HTML, CSS, and JavaScript
- Uses the `fetch()` API to communicate with the backend
- Dynamically displays and updates student details

## ✅ Features

- Add student details
- View all students
- Update student information
- Delete student records
- Simple, user-friendly interface

## 📌 Conclusion

This project demonstrates a functional School Management System backend built with Node.js and Express, using REST APIs and JSON-based data storage — completed as part of IBM's Knowledge Transfer internship training.
