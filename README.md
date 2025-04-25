Todo Application - Readme
--------------------------
Overview
This is a collaborative Todo application built by a team of developers with distinct roles. The application provides a complete solution for managing tasks with a frontend interface, backend API, and state management.

Team Members & Responsibilities
--------------------------------
Anshad: Frontend development (UI/UX implementation)
Afeefa: API integration (connecting frontend to backend)
Abhinand: Backend development (server-side logic)
Razik: Backend development (database & API structure)
Salman: State management (application data flow)

Features
---------
Create, read, update, and delete todos
Mark tasks as complete/incomplete
User-friendly interface
Responsive design (works on mobile and desktop)
Persistent data storage

Technical Stack
----------------
Frontend
React.js
Tailwind
State management (Redux)
Backend
Node.js with Express 
Database (MongoDB)
REST API 
Setup Instructions

Frontend Setup
--------------
Navigate to frontend directory: cd frontend
Install dependencies: npm install
Start development server: npm start

Backend Setup
--------------
Navigate to backend directory: cd backend
Install dependencies: npm install
Create .env file with required environment variables
Start server: npm run dev

APIs
-----
POST /api/todos - Create new todo

GET /api/todos - Get all todos

PUT /api/todos/:id - Update todo

DELETE /api/todos/:id - Delete todo


Create your feature branch: git checkout -b develop
Commit your changes: git commit -m 'feat: Add some feature'
Push to the branch: git push origin develop
Open a pull request

License
MIT License (or specify your preferred license)