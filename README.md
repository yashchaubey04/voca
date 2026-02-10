<p align="center">
  <img src="./frontend/src/assets/chatlogo.png" alt="VocaChat Logo" width="120" />
</p>

<h1 align="center">VocaChat</h1>

<p align="center">
  A real-time multilingual chat application built with the MERN stack, Socket.io, and Redis
</p>

<p align="center">
  <b>Live Translation • Real-time Messaging • Scalable Architecture</b>
</p>

---

## 📖 About the Project

**VocaChat** is a real-time multilingual chat application that allows users to communicate instantly with **live message translation** across different languages.

It is designed with a strong focus on **low latency**, **scalability**, and a **smooth real-time user experience**.

---

## 🎥 Demo Video

<p align="center">
  <a href="https://youtu.be/GmMqWdp7G9c">
    <img src="https://img.youtube.com/vi/GmMqWdp7G9c/0.jpg" alt="VocaChat Demo Video" width="600" />
  </a>
  <br/>
  ▶️ Watch Demo on YouTube
</p>

---

## 📸 Screenshots

<p align="center">
  <img src="./frontend/src/assets/login.png" width="45%" />
  <img src="./frontend/src/assets/chat.png" width="45%" />
</p>

<p align="center">
  <img src="./frontend/src/assets/language.png" width="45%" />
</p>

---

## 🚀 Features

- Real-time messaging using Socket.io
- Live message translation between users
- JWT / Google OAuth authentication
- One-to-one chat
- Online / offline user presence
- Typing indicator
- Message timestamps
- Redis-powered socket & cache management
- Fully responsive UI

---

## 🛠️ Tech Stack

**Frontend**
- React
- Tailwind CSS
- Socket.io-client

**Backend**
- Node.js
- Express.js
- Socket.io
- MongoDB + Mongoose
- Redis (Upstash)
- JWT Authentication
- Open-source Translation API

**Deployment**
- Frontend: Vercel  
- Backend: Render  
- Database: MongoDB Atlas  
- Cache: Redis  

---

## ⚙️ Installation & Setup

```bash
# Clone repository
git clone https://github.com/viveksingh62/chatter.git
cd chatter

# Backend setup
cd backend
npm install

# Create backend/.env
PORT=8080
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
REDIS_URL=your_redis_url
TRANSLATION_API_KEY=your_translation_api_key
CLIENT_URL=http://localhost:5173

# Run backend
node index.js

# Frontend setup
cd ../frontend
npm install

# Create frontend/.env
VITE_BACKEND_URL=http://localhost:8080

# Run frontend
npm run dev



    Developed by Vivek Singh ✨
   
