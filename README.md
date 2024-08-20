# 💬 ChatBuddy

Welcome to **ChatBuddy**! This project is a real-time chat application that supports both group chats and private messaging. Built with Node.js, Express.js, React.js, and Socket.io, ChatBuddy provides a seamless chat experience with instant messaging and an intuitive UI.


---

## 🚀 Features

- **Real-Time Communication:** Instant messaging with the power of Socket.io.
- **Group Chat & Private Messaging:** Chat with friends in groups or have one-on-one conversations.
- **Node.js & Express.js Backend:** Fast and efficient server handling with RESTful APIs.
- **React.js Frontend:** Responsive and dynamic user interface with React.
- **User Authentication:** Secure login and user management.
- **Typing Indicators & Read Receipts:** See when someone is typing and if your message has been read.

---


## 🔧 Technologies Used

- **Frontend:**
  - React.js
  - CSS / SCSS for styling

- **Backend:**
  - Node.js
  - Express.js
  - Socket.io for real-time communication
  - JWT for authentication 

---

## 📂 Project Structure

```bash
chatbuddy/
├── backend/            # Node.js & Express server files
│   ├── config/         # Configuration files (db, jwt, etc.)
│   ├── controllers/    # API controllers
│   ├── models/         # Mongoose models 
│   ├── routes/         # API routes
│   ├── socket/         # Socket.io events and handlers
│   └── ...
├── frontend/           # React.js files
│   ├── public/     # Reusable components
│   ├── src/          # Application pages         
│   └── ...
└── README.md           # This file
