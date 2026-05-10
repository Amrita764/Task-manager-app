Task Manager Application

A full-stack Task Manager web application built to help users manage daily tasks efficiently with features like task creation, updating, deletion, authentication, and task tracking.

##Features
User Authentication (Login & Signup)
Create, Update, Delete Tasks
Mark Tasks as Completed
Responsive User Interface
REST API Integration
MongoDB Database Support
Real-time Task Management
Secure Backend Architecture

$$Tech Stack
Frontend
React.js
HTML5
CSS3
JavaScript
Tailwind CSS
Axios
Backend
Node.js
Express.js
MongoDB
Mongoose
JWT Authentication
bcrypt.js

##Project Structure

Task-Manager/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   ├── index.js
│   ├── package.json
│
└── README.md

##Installation & Setup
Clone Repository
git clone 
Navigate to Project

cd Task-Manager

Backend Setup

cd backend

npm install

npm start

##Backend runs on:

http://localhost:5000
Frontend Setup

Open another terminal:

cd frontend

npm install

npm run dev

Frontend runs on:

http://localhost:5173
Environment Variables

Create a .env file inside backend folder.

PORT=5000

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
API Endpoints
Authentication
POST /api/auth/register
POST /api/auth/login
Tasks
GET /api/tasks
POST /api/tasks
PUT /api/tasks/:id
DELETE /api/tasks/:id
Screenshots:



Future Enhancements
Dark Mode
Task Deadline Notifications
Drag & Drop Tasks
Team Collaboration
Task Priority Levels
Cloud Deployment
Author

Amrita Singh

B.Tech Electronics & Computer Engineering REVA University

License

This project is developed for educational and learning purposes.

I’ve created a complete professional README for your full-stack Task Manager project, including:

Features
Tech stack
Installation steps
Project structure
API endpoints
Environment variables
Future enhancements

