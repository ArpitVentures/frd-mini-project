# ORBIQ — Modern Productivity Workspace

ORBIQ is a productivity-focused workspace designed to help users organize, manage, monitor, and understand their work through task management, deadlines, analytics, and intelligent productivity features.

The project initially started as **TaskFlow**, a conventional task management application, and was later evolved into **ORBIQ**, with a broader productivity-focused interface, analytics, subscription-related functionality, and an AI-ready architecture.

---

## ✨ Features

- 🔐 Secure User Authentication
- 👤 User Profile Management
- 🎯 Mission / Task Management
- 📋 Task Board with multiple task states
- ⚡ Priority and Deadline Management
- 📊 Analytics and Productivity Telemetry
- ⏱️ Deadline and Productivity Tracking
- 💳 Subscription and Plan Management
- 📧 Email-based functionality
- 🤖 HORIZON — AI-ready productivity assistant layer
- 🧠 PULSAR — Intelligence layer for the ORBIQ ecosystem
- 🎨 Modern dark-themed responsive interface
- 🔎 Workspace-oriented navigation and user experience

---

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- React Router
- Axios
- Recharts
- Framer Motion
- Lucide React
- React Hot Toast
- HTML5
- CSS3

### Backend

- Node.js
- Express.js
- REST APIs
- JWT Authentication
- bcrypt
- Nodemailer
- CORS
- dotenv
- Cron Jobs

### Database

- MongoDB
- Mongoose
- MongoDB Atlas

### Deployment

- Vercel — Frontend
- Render — Backend

### Development Tools

- Git
- GitHub
- WebStorm
- npm

---

## 🏗️ System Architecture

ORBIQ follows a client-server architecture in which the frontend communicates with the backend through REST APIs, while the backend handles application logic, authentication, and database operations.

```text
                    ┌─────────────────┐
                    │      User       │
                    └────────┬────────┘
                             │
                             ▼
                ┌────────────────────────┐
                │     React + Vite       │
                │       Frontend         │
                │        Vercel          │
                └───────────┬────────────┘
                            │
                       REST APIs
                            │
                            ▼
                ┌────────────────────────┐
                │    Node.js + Express   │
                │        Backend         │
                │         Render         │
                └───────────┬────────────┘
                            │
                            ▼
                ┌────────────────────────┐
                │      MongoDB Atlas     │
                │        Database        │
                └────────────────────────┘
```

---

## 📁 Project Structure

```text
ORBIQ/
│
├── Backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── ...
│
├── Frontend/
│   ├── src/
│   ├── public/
│   └── ...
│
├── docs/
│
├── .gitignore
└── README.md
```

> The internal project structure may evolve as development continues.

---

## 🎯 Core Modules

### Mission Control

Mission Control acts as the main workspace dashboard of ORBIQ. It brings together task information, productivity metrics, system telemetry, deadlines, and other workspace elements in a single interface.

### Task Management

ORBIQ provides task management functionality for creating, organizing, updating, prioritizing, and completing tasks.

Tasks can be organized into different states:

- To Do
- In Progress
- Completed

### Analytics & Telemetry

The Analytics and Telemetry section provides productivity-related metrics and visualizations, including task completion, pending tasks, productivity information, and activity trends.

### Authentication

The application includes user registration, login, protected routes, password handling, and JWT-based authentication.

### Profile Management

Users can manage profile-related information within the application.

### Subscription & Plans

ORBIQ includes a foundation for subscription and plan-related functionality, including plan management and expiration handling through scheduled backend processes.

### HORIZON

**HORIZON** represents the user-facing intelligent assistant layer of ORBIQ.

It is designed as part of the broader intelligent productivity architecture of the project.

### PULSAR

**PULSAR** stands for:

**P.U.L.S.A.R. — Productive Unified Logic & Smart Adaptive Response**

It represents the intelligence layer behind the broader ORBIQ ecosystem and is intended to support contextual productivity and intelligent application behaviour.

---

## 🔐 Authentication

ORBIQ uses a backend authentication system based on:

- JWT
- bcrypt
- Protected API routes
- Password-based authentication
- User session handling
- Password reset functionality

Authentication-related functionality is handled through the Node.js and Express.js backend.

---

## 📊 Analytics

The ORBIQ analytics dashboard provides visual information related to productivity and task activity.

The dashboard includes metrics such as:

- Completed Tasks
- Pending Tasks
- Productivity
- Current Streak
- Weekly Productivity
- Activity Trends

Charts and visualizations are implemented using **Recharts**.

---

## 🎨 User Interface

ORBIQ uses a modern dark-themed interface with a space-inspired visual identity.

The interface uses technologies and libraries such as:

- CSS
- Framer Motion
- Lucide React
- React Hot Toast
- Recharts

The goal is to provide a clean and interactive workspace while keeping the application practical for everyday task management.

---

## 🚀 Deployment

The frontend of ORBIQ is deployed using **Vercel**, while the backend is deployed using **Render**.

The production frontend communicates with the deployed backend through environment-based API configuration.

### Live Application

**ORBIQ:**  
https://orbiq-by-arpit.vercel.app/

---

## 🧪 Development & Debugging

During development, the project went through multiple iterations involving:

- Feature implementation
- Frontend and backend integration
- API debugging
- Authentication testing
- Database integration
- Deployment configuration
- Environment variable configuration
- UI improvements
- Production debugging

The development process involved identifying issues, testing possible solutions, and refining the application based on observed behaviour.

---

## 📚 Project Evolution

ORBIQ evolved through multiple stages.

### Stage 1 — TaskFlow

The project initially started as **TaskFlow**, a conventional task management application based on the assigned functional requirements.

### Stage 2 — ORBIQ

The project was later expanded and redesigned as **ORBIQ**, introducing a broader productivity-focused experience with:

- Mission-based terminology
- Analytics and telemetry
- Productivity tracking
- Subscription-related functionality
- Modern workspace design
- HORIZON
- PULSAR

This evolution transformed the original task management concept into a more comprehensive productivity workspace.

---

## 📂 Repository Contents

This repository contains the major components of the ORBIQ project:

- `Backend/` — Server-side application and APIs
- `Frontend/` — React-based client application
- `docs/` — Project documentation and supporting material
- `.gitignore` — Git ignore configuration
- `README.md` — Project documentation

---

## 🌐 Links

### Live Application

https://orbiq-by-arpit.vercel.app/

### GitHub Repository

https://github.com/ArpitVentures/orbiq-by-arpit

---

## 👨‍💻 Author

**Arpit Srivastava**

B.Tech — Computer Science and Engineering  
IILM University, Greater Noida

GitHub:  
https://github.com/ArpitVentures

---

## 📌 Project Status

ORBIQ is a personal software project focused on building a modern productivity workspace using the MERN stack.

The project has evolved from a basic task management application into a broader productivity-focused system with task management, analytics, subscription-related functionality, and an AI-ready architecture.

---

## 📄 License

This project is developed as a personal software project and learning initiative.
