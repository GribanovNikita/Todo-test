# TODO List

## Description
**TODO List** is a task management web application built with **NestJS** on the backend and **React + TypeScript** on the frontend. It features role-based access control, JWT-based authentication, and a clean separation of responsibilities between managers and team members.


## ✨ Key Features
- ✅ **Task Management**: Create, edit, and delete tasks.
- ✅ **User Roles**: Managers can assign tasks to subordinates; employees can only manage their own.
- ✅ **Smart Filtering & Sorting**: Organize tasks by priority, due date, or status.
- ✅ **Secure Auth**: JWT-based authentication and authorization.
- ✅ **API Documentation**: Fully documented REST API using Swagger (OpenAPI).

## 🛠️ Tech Stack
- **Backend**: NestJS, TypeORM, PostgreSQL  
- **Frontend**: React, TypeScript, Vite, Axios  
- **Database**: PostgreSQL  
- **Authentication**: JWT (access + refresh tokens)  
- **API Docs**: Swagger UI (OpenAPI 3.0)

# Installation & Setup

## Clone the Repository
```
git clone https://github.com/username/project-name.git
cd project-name
```

## Backend
1. Go to backend directory:
```
cd todo-list
```
2. Install dependency:
```
npm install
```
3. Create a .env file:
```
DB_HOST=localhost
DB_PORT=5432
DB_USERNAME=postgres
DB_PASSWORD=your_password
DB_NAME=todoList
```
4. Start the server:
```
npm run start
```

## Frontend
1. Go to frontend directory:
```
cd todo-app-frontend
```
2. Install dependency:
```
npm install
```
3. Start the client:
```
npm run dev
```

## Usage
+ Open the app in your browser: http://localhost:5173
+ Access the interactive Swagger API docs: http://localhost:3000/api
