# 🎥 Video Conferencing App using PeerJS, Socket.io & EJS

A simple video conferencing application using **PeerJS** for WebRTC connections, **Socket.io** for real-time communication, and **EJS** for templating.

## 🚀 Features
- 📹 **Real-time video/audio communication**
- 🌍 **Unique room IDs for each session**
- 🔗 **Peer-to-Peer Connection via WebRTC**
- 📡 **Socket.io for signaling**
- ❌ **Handles User Disconnections**
- 🎨 **EJS Templating** for dynamic room IDs

---

## 🛠️ **Installation & Setup**

### 1️⃣ Clone the repository
```bash
git clone https://github.com/AayushKP/Peer-JS.git
cd Peer-JS
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Start the server
```bash
node server.js
```

---

## 🏗️ **Project Structure**
```
/video-conferencing-app
│── /public
│   ├── script.js
│── /views
│   ├── room.ejs
│── server.js
│── package.json
│── README.md
```

---

## 🏗️ **How It Works**
1. A user visits the home route `/` and is redirected to a unique room ID.
2. When a user joins a room, their video stream is captured using `getUserMedia()`.
3. The app uses **PeerJS** to create
