Full-Stack To-Do List Application with FastAPI

This is a full-stack Todo List app where users can create, edit, complete, and delete tasks. The frontend is built with Vite + React, and the backend is powered by FastAPI using SQLite for data storage


🚀 Technologies Used

- React (Vite)
- FastAPI
- SQLite (Note: Used instead of PostgreSQL due to Render's one free DB limit)
- Axios
- SQLAlchemy


⚙️ Setup Instructions

Frontend (React):
1. Clone the repo: git clone https://github.com/your-username/your-frontend-repo.git
2. Install dependencies: npm install
3. Update the API URL in your code to point to your deployed backend (e.g., on Render)
4. Run the app

Backend (FastAPI):

1. CLone the repo: git clone https://github.com/your-username/your-backend-repo.git
2. Create a virtual environment and install dependencies:
    python -m venv env
    source env/bin/activate   # or `env\Scripts\activate` on Windows
    pip install -r requirements.txt
3. Run the server: uvicorn main:app --reload



🌐 API Endpoints

Base URL: https://fastapi-backend-f2k4.onrender.com/

Method


1. GET	https://fastapi-backend-f2k4.onrender.com/api/todos/ Description: Get all todos
2. POST	https://fastapi-backend-f2k4.onrender.com/api/todos/ Description: Create a new todo
3. PATCH	https://fastapi-backend-f2k4.onrender.com/api/todos/id}/ Description:Update todo (status)
4. PATCH	https://fastapi-backend-f2k4.onrender.com/api/todos/id}/ Description:Edit description
5. DELETE	https://fastapi-backend-f2k4.onrender.com/api/todos/id}/ Description:Delete a todo


🌐 Live Links

1. Frontend (Github repo): https://github.com/Reige06/FastAPI_frontend
2. Frontend page (Github page) : https://reige06.github.io/FastAPI_frontend/
3. Backend (Render): https://fastapi-backend-f2k4.onrender.com/docs
