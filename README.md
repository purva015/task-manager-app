# Task Manager App

## 📌 Overview
This is a simple full-stack Task Manager application that allows users to create, view, update, and delete tasks.

---

## 🚀 Features

### Frontend
- Display list of tasks
- Add new task
- Mark task as completed
- Delete task
- Loading and error handling

### Backend
- REST API with Express
- Basic validation
- JSON responses
- In-memory data storage

---

## 🛠 Tech Stack
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express

---

## 📡 API Endpoints

- GET /tasks → Fetch all tasks
- POST /tasks → Create a new task
- PATCH /tasks/:id → Update task status
- DELETE /tasks/:id → Delete a task

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/purva015/task-manager-app.git
cd task-manager-app



#  4. Adding Assumptions / Trade-offs 


- Used in-memory storage to keep the project simple and within the given time constraint.
- No authentication implemented as it was not required.
- UI is kept minimal to focus more on functionality and API integration.
- No database used, so data is not persistent after server restart.