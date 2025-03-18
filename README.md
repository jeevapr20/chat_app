# MERN Chat Application

A real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js). This app allows users to send and receive messages in real-time with a sleek and responsive interface.

---

## Features
- **User Authentication**: Secure login and registration with JWT (JSON Web Tokens).
- **Real-Time Messaging**: Messages delivered instantly using Socket.IO.
- **Modern UI**: Responsive and mobile-friendly design using React and Tailwind CSS frameworks.
- **Database Integration**: All user data and messages stored securely in MongoDB.

---

## Technologies Used
- **Frontend**: React, React Router, Axios
- **Backend**: Node.js, Express, Socket.IO
- **Database**: MongoDB (using Mongoose)
- **Authentication**: JWT (JSON Web Tokens) and bcrypt.js for secure password hashing

---

## Installation Instructions

1. Clone the Repository
  ```bash
  git clone https://github.com/jeevapr20/chat_app.git

2. Navigate to the Project Directory
  ```bash
  cd chat_app

3. Install Dependencies for Backend
Navigate into the backend folder and install dependencies:

  ```bash
  cd backend
  npm install

4. Install Dependencies for Frontend
Navigate into the frontend folder and install dependencies:

  ```bash
  cd ../frontend
  npm install

5. Set Up Environment Variables
Create a .env file in the backend folder and configure the following:

  MONGO_URI=your_mongodb_connection_string
  JWT_SECRET=your_jwt_secret
  SOCKET_PORT=your_socket_port

6. Run the Backend Server
  ```bash
  cd backend
  npm start

7. Run the Frontend
In another terminal, run the frontend:

  ```bash
  cd frontend
  npm start

8. Open the Application
Visit http://localhost:3000 in your browser to use the chat app.
