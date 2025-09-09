🚗 GoShare - MERN Stack Ride Sharing Platform

GoShare is a full-stack ride-sharing application built with the **MERN stack** (MongoDB, Express.js, React.js, and Node.js). It allows users to register, log in, search for rides, post rides, and connect with other travelers going the same way. It is designed to make carpooling easy, efficient, and eco-friendly.

---

## 🌐 Live Demo

🚀 LIVE Demo: https://share-ride-git-main-dhanush-javvadhis-projects.vercel.app/

[GoShare API Documentation](https://documenter.getpostman.com/view/32434659/2s9YymFjCa#e3c94f2d-c0eb-424a-982c-fc94fef0d286)

---

## 🛠️ Tech Stack

**Frontend:**  
- React.js (with Vite)  
- Tailwind CSS  
- Axios  
- React Router

**Backend:**  
- Node.js  
- Express.js  
- MongoDB (via Mongoose)  
- JWT Authentication  
- bcrypt for password hashing  
- CORS

**Other Tools:**  
- Git & GitHub  
- Vercel (Frontend Hosting)  
- Render (Backend Hosting)  
- Postman (for API Testing)


---

## 🔐 Features

### 👤 Authentication
- Register new users
- Login with JWT
- Secure password hashing with bcrypt
- Protected routes

### 🚙 Ride Features
- Post a ride (source, destination, date, available seats, etc.)
- Browse all available rides
- Filter rides by location or date
- Contact driver (feature pending)

### 👥 User Features
- Profile management
- View posted rides
- Delete or update a ride

---

## 🗂️ Project Structure

```bash
ShareRide/
├── client/               # Frontend (React + Vite)
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── server/               # Backend (Express + MongoDB)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── .env
│   ├── server.js
│   └── package.json
│
└── README.md
