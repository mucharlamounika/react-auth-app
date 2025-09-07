# React & Node.js Authentication System

This is a simple full-stack application that implements a user authentication system with features for user registration, login, and logout. The frontend is built with React.js, and the backend API is built with Node.js and Express, using SQLite for the database.

## 🚀 Features

* **User Registration:** Create a new account with a unique email and password.
* **User Login:** Authenticate using registered credentials.
* **Session-based Authentication:** Maintains a user's logged-in state using secure sessions and cookies.
* **Logout:** Clears the user session and logs them out.
* **Password Security:** Passwords are securely hashed using `bcrypt` before being stored in the database.
* **Client-Server Communication:** The React frontend makes API calls to the Node.js backend to handle authentication requests.

## 🛠️ Technologies Used

### **Frontend**
* **React.js:** A JavaScript library for building user interfaces.
* **Axios:** A promise-based HTTP client for making API requests.
* **React Router:** For handling client-side navigation.

### **Backend**
* **Node.js:** A JavaScript runtime for building the server-side application.
* **Express.js:** A minimal and flexible Node.js web application framework.
* **SQLite:** A lightweight, file-based SQL database.
* **Bcrypt:** For securely hashing and comparing passwords.
* **Express-session:** Middleware for managing user sessions.
* **CORS:** To handle Cross-Origin Resource Sharing between the frontend and backend.

## 📂 Project Structure

The project is divided into two main directories: `client` for the React application and `server` for the Node.js API.

react-node-auth-app/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── Login.js
│   │   │   ├── Register.js
│   │   │   └── Home.js
│   │   ├── App.css
│   │   └── App.js
│   └── package.json
└── server/                 # Node.js backend
├── db.sqlite           # SQLite database file (created automatically)
├── db.js               # Database connection and schema setup
├── server.js           # Main Express server and API routes
└── package.json
