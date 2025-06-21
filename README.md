# My Chat App 💬

A real-time chat application built using **React**, **Node.js**, and **Socket.io**, with a responsive interface styled using **Tailwind CSS** and **DaisyUI**. This app allows users to communicate instantly, offering a smooth and modern chat experience.

---

## 🚀 Features

- Real-time messaging using **Socket.io**
- Persistent chat history stored in **MongoDB**
- File sharing support (images, documents, etc.)
- Responsive UI with **React**, **Tailwind CSS**, and **DaisyUI**
- Backend communication with **Node.js** and **Express**
- Easy-to-use interface for chat rooms or private messaging
- Scalable folder structure with clear separation of frontend and backend

---

## 🧱 Tech Stack

| Layer     | Technologies                                  |
|-----------|-----------------------------------------------|
| Frontend  | React, Tailwind CSS, DaisyUI, Socket.io-client|
| Backend   | Node.js, Express, Socket.io                   |
| Database  | MongoDB                                       |    

---

## 📁 Project Structure
MY_CHAT_APP/
─ frontend/ # React frontend using Tailwind + DaisyUI
    ─ src/
    ─ public/
─ backend/ # Node.js backend with Socket.io
    ─ index.js / server.js
─ README.md
─ package.json


---

## 🔧 Getting Started

### 1. Clone the repository

git clone https://github.com/ShyamSalekar/Chat_app.git
cd My_Chat_app

### 2. Install dependencies
# For backend: 
    cd backend
    npm install

# For frontend:
    cd ../frontend
    npm install

### 3. Set environment variables
# Create a .env file inside the backend directory with the following content:
MONGO_URI=your-mongodb-connection-string
PORT=5000


### 4. Start the application
# In frontend:
    run command "npm run dev"

# In backend:
    run command "npm run dev"

## 👤 Author
Shyam Salekar


