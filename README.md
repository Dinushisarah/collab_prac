# 📝 Task Manager - Full-Stack CRUD Application

A collaborative full-stack task management application built with MongoDB, Express, and vanilla JavaScript.


## 🎯 Project Purpose

This project was created by me as a **learning exercise to practice professional Git collaboration and team-based development workflows**. The goal was to simulate real-world team collaboration by:

- Working as two separate developers on the same codebase
- Practicing branching strategies and pull requests
- Learning to merge code and resolve conflicts
- Understanding full-stack integration
- Preparing for real team projects in academic and professional settings

This hands-on practice helped me to build confidence in:
- Git version control and GitHub workflows
- Code collaboration and communication
- Full-stack development practices
- Professional software development processes

## 🚀 Features

- ✅ Create new tasks with title, description, and status
- ✅ View all tasks in a beautiful UI
- ✅ Update task status (pending, in-progress, completed)
- ✅ Delete tasks
- ✅ Persistent storage with MongoDB Atlas
- ✅ RESTful API backend
- ✅ Responsive frontend design

## 🛠️ Technologies Used

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- CORS
- dotenv

### Frontend
- HTML5
- CSS3
- Vanilla JavaScript
- Fetch API

## 📦 Installation & Setup

### Prerequisites
- Node.js installed
- MongoDB Atlas account

### Backend Setup

1. Clone the repository:
```bash
git clone https://github.com/Dinushisarah/collab_prac.git
cd collab_prac/backend
```

2. Install dependencies:
```bash
npm install
```

3. Create `.env` file:
```
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

4. Start the server:
```bash
npm run dev
```

Server runs on `http://localhost:5000`

### Frontend Setup

1. Navigate to frontend folder:
```bash
cd frontend
```

2. Open `tasks.html` in your browser or use Live Server

## 🎯 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/tasks` | Get all tasks |
| GET | `/api/tasks/:id` | Get single task |
| POST | `/api/tasks` | Create new task |
| PUT | `/api/tasks/:id` | Update task |
| DELETE | `/api/tasks/:id` | Delete task |


## 👥 Team(Myself-Dinushisarah)

- **Developer 1**: Backend API & MongoDB Integration
- **Developer 2**: Frontend UI & JavaScript
