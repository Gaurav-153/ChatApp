# MERN Real-Time Chat App 💬

A real-time chat application built with the **MERN stack** (MongoDB, Express, React, Node.js) and **Socket.IO** for instant messaging. Users can register, log in, and chat in real time.

---

## 🔧 Tech Stack

- **Frontend**: React, Axios, Context API, Socket.IO Client  
- **Backend**: Node.js, Express, MongoDB, Socket.IO  
- **Auth**: JWT, Bcrypt  
- **Database**: MongoDB + Mongoose

---

## 🚀 Features

- Real-time messaging with Socket.IO  
- JWT-based authentication  
- Chat history stored in MongoDB  
- Online/offline status  
- Responsive React UI

---

## ▶️ Getting Started

### Prerequisites
- Node.js, MongoDB, Git

### Installation

```bash
git clone https://github.com/yourusername/mern-chat-app.git
cd mern-chat-app

# Backend setup
cd backend
npm install

# Frontend setup
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
npm run dev

# Frontend
cd ../frontend
npm start
```
### Access the app at: http://localhost:3000



