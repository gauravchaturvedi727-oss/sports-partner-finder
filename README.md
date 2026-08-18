# 🏆 Sports Partner Finder

A full-stack web application that helps users find sports partners based on their preferred sports, skill level, location, availability, and playing preferences.

Users can create an account, build their sports profile, discover other players, send partner requests, manage requests, and connect with suitable sports partners.

---

## 🚀 Live Demo

### Frontend
https://sports-partner-finder-frontend.vercel.app

### Backend API
https://sports-partner-finder-backend-1.onrender.com

---

## 📸 Features

### 👤 Authentication
- User Registration
- User Login
- JWT Authentication
- Protected Routes
- Token-based Authorization

### 🏃 Player Profile
- Create and manage player profile
- Select preferred sports
- Choose skill level
- Select state and city
- Add availability
- Set preferred playing location

### 🤝 Partner Requests
- Search for sports partners
- Send partner requests
- View incoming requests
- Accept requests
- Reject requests
- Cancel sent requests
- View connected partners
- Remove partners

### 🎮 Sports Matching
Users can find players based on:
- Preferred Games
- Skill Level
- Location
- Availability
- Playing Preferences

### 👥 Community
- Community-related functionality
- User interaction features

### 🛡️ Admin & Reports
- Admin routes
- Report management functionality

---

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- React Router DOM
- Axios
- CSS

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- CORS
- dotenv

### Deployment

- Frontend: Vercel
- Backend: Render
- Database: MongoDB Atlas

---

## 📂 Project Structure

```text
sports-partner-finder/
│
├── backend/
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
│   ├── app.js
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── public/
│   │
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   │   └── api.js
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   ├── package.json
│   ├── vite.config.js
│   └── vercel.json
│
├── .gitignore
└── README.md
