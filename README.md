# ConnectUs

**ConnectUs** is a full-featured real-time communication platform where users can:

- 💬 Chat instantly with friends (1-on-1 and group chat)
- 📷 Share **images**, 🎥 **videos**, 🎵 **audio**, and 📁 **files**
- 👥 Send, accept, and manage **friend requests**
- 🧑‍🤝‍🧑 Create and manage **groups**
- 🔔 Receive **real-time notifications** for chats, requests, and group updates

Built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js), **Socket.IO** for real-time communication, and **Cloudinary** for media upload and delivery.

Whether it's staying in touch, collaborating with a group, or sharing rich media — **ConnectUs** makes it fast, secure, and seamless.
## 🔗 Live Demo

> Coming soon...

---

## 📌 Features

- 🔐 **Authentication**
  - Signup and Login with secure JWT-based authentication
  - Password hashing using bcrypt
  - Profile fields: username, name, bio, profile picture

- 💬 **Real-time Chat**
  - 1-on-1 messaging
  - Group chat support
  - Live message updates using **Socket.IO**

- 👥 **Friend Management**
  - Send/Accept/Reject friend requests
  - Friend list management

- 🔔 **Notifications**
  - Real-time notifications for friend requests, messages, and group activity

- 📂 **Media Support**
  - Upload and share **images, videos, audio, and files**
  - Media uploaded using **Cloudinary**

- 🧑‍🤝‍🧑 **Group Management**
  - Create, update, and delete groups
  - Add or remove group members
  - Group admin controls

- 📊 **Admin Panel**
  - Manage users and groups
  - View platform stats (optional)

---

## ⚙️ Tech Stack

### Frontend

- **React.js**
- **Mantine UI** for components
- **React Hook Form** for form handling
- **Axios** for API requests
- **Socket.IO-client** for real-time communication

### Backend

- **Node.js**
- **Express.js**
- **MongoDB** (Mongoose ODM)
- **Socket.IO**
- **Cloudinary SDK**
- **JWT** for authentication
- **Bcrypt.js** for password hashing

---

## 📁 Folder Structure (Backend)

backend/
├── config/ # DB and cloudinary setup
├── controllers/ # Business logic
├── models/ # Mongoose schemas
├── routes/ # Express routes
├── sockets/ # Socket.IO logic
├── middleware/ # Auth middlewares
├── utils/ # Utility functions
└── server.js # Entry point

## 📁 Folder Structure (Frontend)

frontend/
├── components/ # Reusable components
├── pages/ # Pages like Home, Chat, Login, etc.
├── services/ # Axios API calls
├── contexts/ # Global contexts (Auth, Socket)
└── App.js

---

## 🚀 Getting Started

### Backend

cd backend
npm install
npm run dev

### Frontend

cd frontend
npm install
npm start
