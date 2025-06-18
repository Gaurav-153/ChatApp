<h1 align="center">💬 MERN Real-Time Chat App</h1>

<p align="center">
  A full-stack real-time chat application built using the <strong>MERN Stack</strong> (MongoDB, Express, React, Node.js) and <strong>Socket.IO</strong> for seamless live messaging.
</p>

---

## 🛠️ Tech Stack

| Layer       | Technology                     |
|-------------|--------------------------------|
| **Frontend**| React, Axios, Context API, Socket.IO Client |
| **Backend** | Node.js, Express, Socket.IO    |
| **Database**| MongoDB + Mongoose             |
| **Auth**    | JWT, Bcrypt                    |

---

## ✨ Features

✅ Real-time messaging using Socket.IO  
✅ User authentication with JWT  
✅ Chat history saved in MongoDB  
✅ Online/offline user indicators  
✅ Clean & responsive React UI  

---

## 🚀 Getting Started

### 🔧 Prerequisites

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- Git

---

### 📥 Installation

```bash
# Clone the repository
git clone https://github.com/Gaurav-153/mern-chat-app.git
cd mern-chat-app
```
# Backend setup
```bash
cd backend
npm install
```
# Frontend setup
```bash
cd ../frontend
npm install
```
### Environment Variables
Create .env in backend 
```bash
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret
```
### Run the App
```bash
# Backend
cd backend
node index.js

# Frontend
cd ../frontend
npm run dev
```
### Access the app at: http://localhost:3000



