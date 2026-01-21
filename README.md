<h1 align="center">✨ Fullstack Chat & Video Calling App ✨</h1>


<p align="center">
  <img src="/frontend/public/screenshot-for-readme.png" alt="Demo App" width="700">
</p>

---

## 🚀 Overview

A modern **real-time communication platform** that combines **chat, video calling, and language exchange features** into one elegant application.  
Built using the **MERN stack (MongoDB, Express.js, React, Node.js)** and **Stream API**, this project offers seamless video calls, message reactions, screen sharing, and multi-theme support.

---

## ✨ Key Highlights

- 🌐 **Real-Time Messaging** with typing indicators & emoji reactions  
- 📹 **1-on-1 & Group Video Calls** with screen sharing and recording support  
- 🔐 **JWT Authentication** with protected user routes  
- 🌍 **Language Exchange Platform** featuring 32 dynamic UI themes  
- ⚡ **Tech Stack:** React, Express, MongoDB, Tailwind CSS, TanStack Query  
- 🧠 **Global State Management** with Zustand  
- 🚨 **Full Error Handling** (frontend & backend)  
- 🎯 **Integration with Stream** for scalable video and chat APIs  
- 🚀 **Free Deployment-Ready** (supports services like Vercel, Render, or Sevalla)  
- ⏳ **Built for Scalability & Performance**

---

## ⚙️ Environment Variables Setup

### 🧩 Backend (`/backend`)

Create a `.env` file inside the **backend** directory with the following:
```bush
PORT=5001
MONGO_URI=your_mongo_uri
STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

🧩 Frontend (/frontend)
Create a `.env` file inside the frontend directory:
```bush
VITE_STREAM_API_KEY=your_stream_api_key
```


🧱 Installation & Setup
1️⃣ Run the Backend
```bush
cd backend
npm install
npm run dev
```
2️⃣ Run the Frontend
```bush
cd frontend
npm install
npm run dev
```




