# Drawing Board App

A collaborative online whiteboard application built with React, Node.js, Express, and MongoDB. This app allows users to create, edit, and share canvases in real-time, making it ideal for brainstorming, teaching, and remote teamwork.

---

## 🚀 Overview

The Drawing Board App provides a seamless experience for users to:
- Register and log in securely
- Create and manage multiple canvases
- Draw, erase, and manipulate elements on a canvas
- Share canvases with other users for collaborative editing
- See real-time updates as others draw
- Manage access and permissions for each canvas

---

## ✨ Features

- **User Authentication:**  
  Secure registration and login using JWT tokens.

- **Canvas Management:**  
  - Create new canvases  
  - List all canvases owned or shared with you  
  - Delete canvases

- **Drawing Tools:**  
  - Freehand drawing  
  - Eraser  
  - Real-time updates using WebSockets (Socket.io)

- **Collaboration:**  
  - Share canvases with other users by email  
  - Control who can edit each canvas  
  - Only owners or shared users can edit a canvas

- **Access Control:**  
  - Only authenticated users can access the app  
  - Owners can share/unshare canvases  
  - Unauthorized users are prevented from editing

- **Responsive UI:**  
  - Built with React  
  - Sidebar for canvas management  
  - Main area for drawing

---

## 🛠️ Tech Stack

- **Frontend:** React, Axios, Context API
- **Backend:** Node.js, Express, Socket.io
- **Database:** MongoDB (Mongoose)
- **Authentication:** JWT
- **Deployment:** Render (backend), Vercel (frontend)

---

## 📦 Getting Started

### Prerequisites

- Node.js & npm
- MongoDB Atlas account

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/cybesama/Drawing_board.git
   cd drawing_board
   ```

2. **Backend Setup:**
   ```bash
   cd whiteboard_az/backend
   npm install
   # Add your MongoDB URI to .env as MONGO_URL
   npm run dev
   ```

3. **Frontend Setup:**
   ```bash
   cd ../whiteboard-tutorial
   npm install
   npm start
   ```

4. **Access the app:**  
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

- [React](https://reactjs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Socket.io](https://socket.io/)

---

**Enjoy collaborating on
