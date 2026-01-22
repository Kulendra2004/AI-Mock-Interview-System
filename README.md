# 🎯 AI Mock Interview Preparation Platform

An AI-powered interview preparation web application built using the MERN stack and Gemini API.  
This platform helps users practice interviews by generating role-based and experience-based questions and storing interview data for future practice.

---

## 🚀 Features

- User authentication (Login & Signup)
- AI-generated interview questions using Gemini API
- Role-based and experience-based question generation
- Interview questions and study data stored in MongoDB
- Secure backend with JWT authentication
- Full-stack MERN application

---

## 🛠 Tech Stack

### Frontend
- React.js
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### AI Integration
- Gemini API

### Authentication
- JWT (JSON Web Tokens)

---

## ⚙️ How the System Works

1. User registers or logs in to the application.
2. User selects job role and experience level.
3. Backend sends details to Gemini API.
4. AI generates interview questions dynamically.
5. Questions and responses are stored in the database.
6. Users can review and practice interview questions anytime.

---

## 📂 Project Structure
AI-Mock-Interview-System/
│
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── authController.js
│   │   └── interviewController.js
│   ├── models/
│   │   ├── User.js
│   │   └── Question.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── interviewRoutes.js
│   ├── middleware/
│   │   └── authMiddleware.js
│   ├── .env
│   ├── package.json
│   └── server.js
│
├── frontend/
│   └── interview-prep-ai/
│       ├── public/
│       │   └── vite.svg
│       │
│       ├── src/
│       │   ├── Pages/
│       │   ├── components/
│       │   ├── context/
│       │   ├── assets/
│       │   ├── utils/
│       │   ├── App.jsx
│       │   ├── main.jsx
│       │   └── index.css
│       │
│       ├── .gitignore
│       ├── README.md
│       ├── eslint.config.js
│       ├── index.html
│       ├── package.json
│       ├── package-lock.json
│       ├── vite.config.js
│       └── vercel.json
│
├── .gitignore
├── package.json
└── README.md


