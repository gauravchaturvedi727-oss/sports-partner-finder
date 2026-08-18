# 🏆 Sports Partner Finder

A full-stack web application designed to help people find and connect with suitable sports partners based on their preferred sports, skill level, location, availability, and playing preferences.

The platform allows users to create profiles, discover players, send and manage partner requests, build connections, and participate in sports-related communities.

---

## 🚀 Live Demo

### Frontend

https://sports-partner-finder-frontend.vercel.app

### Backend API

https://sports-partner-finder-backend-1.onrender.com

---

# ✨ Features

## 🔐 Authentication

- User Registration
- User Login
- Password Hashing
- JWT Authentication
- Token-Based Authorization
- Protected Routes

## 👤 User Profile

Users can create and manage their sports profile with details such as:

- Name
- Email
- City
- State
- Preferred Sports
- Skill Level
- Availability
- Playing Location

## 🔍 Find Sports Partners

Users can discover other players based on:

- Sports Preferences
- Skill Level
- Location
- Availability
- Playing Preferences

## 🤝 Partner Requests

Users can:

- Send Partner Requests
- View Incoming Requests
- Accept Requests
- Reject Requests
- View Sent Requests
- Cancel Sent Requests
- View Connected Partners
- Remove Existing Partners

## 🎮 Play Features

Sports-related player interaction and matching functionality.

## 👥 Community

The application includes community-related features that allow users to interact with the platform's sports community.

## 🛡️ Admin Features

Admin functionality for managing application-related operations.

## 🚨 Reports

Report-related functionality for handling user or platform reports.

---

# 🛠️ Tech Stack

## Frontend

- React.js
- Vite
- React Router DOM
- Axios
- CSS

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- CORS
- dotenv

## Deployment

- Frontend: Vercel
- Backend: Render
- Database: MongoDB Atlas

---

# 📁 Project Structure

```text
sports-partner-finder/
│
├── backend/
│   │
│   ├── config/
│   │   └── db.js
│   │
│   ├── controllers/
│   │   ├── auth.controller.js
│   │   ├── profile.controller.js
│   │   ├── request.controller.js
│   │   ├── play.controller.js
│   │   ├── admin.controller.js
│   │   ├── community.controller.js
│   │   └── report.controller.js
│   │
│   ├── middleware/
│   │   └── auth.middleware.js
│   │
│   ├── models/
│   │   ├── User.js
│   │   └── PartnerRequest.js
│   │
│   ├── routes/
│   │   ├── auth.routes.js
│   │   ├── profile.routes.js
│   │   ├── request.routes.js
│   │   ├── play.routes.js
│   │   ├── admin.routes.js
│   │   ├── community.routes.js
│   │   └── report.routes.js
│   │
│   ├── utils/
│   │
│   ├── app.js
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   │
│   └── sports-frontend/
│       │
│       ├── public/
│       ├── src/
│       │   ├── components/
│       │   ├── pages/
│       │   ├── services/
│       │   │   └── api.js
│       │   ├── App.jsx
│       │   ├── main.jsx
│       │   └── index.css
│       │
│       ├── package.json
│       ├── vite.config.js
│       ├── vercel.json
│       └── README.md
│
├── .gitignore
└── README.md
