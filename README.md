# KT_3_Task
This is repository containing the code for the task for Knowledge Transfer conducted by IBM for Internship



📚 School Management System
📌 Project Description


The School Management System is a simple backend-based application developed using Node.js and Express.js.

It is used to manage student details such as Student ID, Name, Class, and Fees Status.

The project performs basic CRUD operations using REST APIs and stores data in a JSON file.

🛠️ Technologies Used
Node.js
Express.js
JavaScript
JSON
Postman
Git & GitHub
HTML, CSS, JavaScript (Frontend)


📁 Project Structure

School-Management
│
├── app.js
├── students.json
├── package.json
├── package-lock.json
├── routes
│   └── students.js
└── frontend
    ├── index.html
    ├── style.css
    └── script.js

    
⚙️ Installation & Setup

Step 1: Clone the Repository
Bash
git clone <your-github-repository-link>

Step 2: Navigate to Project Folder
Bash
cd School-Management

Step 3: Install Dependencies
Bash
npm install

Step 4: Start the Server
Bash
node app.js

The server will run at:
http://localhost:3000

🔗 API Endpoints
Method
Endpoint

Description

GET
/students
Get all students
GET
/students/:id
Get student by ID

POST
/students/batch
Add new students

PUT
/students/batch
Update student details

DELETE
/students/batch
Delete students

🧪 Testing
APIs are tested using Postman
CRUD operations are verified for correct responses

🌐 Frontend
Developed using HTML, CSS, and JavaScript
Uses fetch() API to communicate with backend
Displays student details dynamically

✅ Features
Add student details
View all students
Update student information
Delete student records
Simple and user-friendly design


📌 Conclusion
This project demonstrates the implementation of a School Management System backend using Node.js and Express with REST APIs and JSON-based data storage.
