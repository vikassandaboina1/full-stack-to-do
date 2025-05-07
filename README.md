
Full Stack To-Do List Application
Developer:vicky
Tech Stack: React, Django REST Framework, MySQL

Overview:
This is a full-stack To-Do List application that allows users to create, read, update, and delete (CRUD) tasks. It includes user authentication, persistent data storage using MySQL, and a responsive interface built with React.

Features:
- User Authentication (Sign Up, Log In, Log Out)
- Add, Edit, Delete Tasks
- Mark Tasks as Complete/Incomplete
- Track Creation Dates
- Real-time updates via RESTful API
- Responsive UI using React

Project Structure:
/todo-react-django-app/
├── backend/                   # Django Project
│   ├── manage.py
│   ├── backend/
│   └── todo/
├── frontend/                  # React Project
│   ├── public/
│   └── src/
└── README.md

Setup Instructions:

Backend Setup (Django):
1. Navigate to backend folder
2. Create virtual environment & activate it
3. Install dependencies
4. Create Django project and app
5. Configure settings.py and connect to MySQL
6. Run migrations
7. Create superuser
8. Run server

Frontend Setup (React):
1. Create React app with create-react-app
2. Install Axios and React Router
3. Start React app

Connect Frontend to Backend:
- Use Axios to connect to Django REST API
- Enable CORS in Django

Testing:
- Test all CRUD functionalities via React UI and Django APIs

Deployment:
Backend:
- Use Heroku/Render
- Configure gunicorn, static files, and cloud MySQL

Frontend:
- Use Netlify/Vercel
- Or serve from Django build

API Endpoints:
GET    /api/tasks/        - List all tasks
POST   /api/tasks/        - Create new task
GET    /api/tasks/<id>/   - Get task by ID
PUT    /api/tasks/<id>/   - Update task
DELETE /api/tasks/<id>/   - Delete task



