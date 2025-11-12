🌀 Kepapro – Anime Streaming Platform

A full-stack anime streaming web application built with the MERN architecture (MongoDB, Express.js, React.js, Node.js).
The platform allows users to stream anime content securely with authentication, real-time updates, and optimized API performance.

🌐 Project Overview

Kepapro is a production-ready streaming system designed to deliver smooth, responsive, and secure video playback experiences.
It includes a frontend for users and a backend for authentication, content management, and data delivery.

🧩 Architecture

The project follows a Modular MERN Architecture:

Frontend (React + Redux)
        ↓
Backend API (Node.js + Express)
        ↓
Database Layer (MongoDB + Mongoose)
        ↓
Authentication (JWT + Bcrypt)

🔁 Data Flow

Frontend (React) handles UI rendering, routing, and state management via Redux.

Backend (Express + Node.js) serves RESTful APIs for content, authentication, and user management.

MongoDB stores all structured data — users, anime metadata, playlists, and favorites.

JWT Authentication ensures secure session-based access between frontend and backend.

⚙️ Tech Stack
🧠 Frontend (/kepapro)

React.js – Component-based UI and routing

Redux – Centralized state management

Axios – API communication layer

Tailwind CSS – Responsive and modern UI

React Router – SPA navigation

JWT Auth Handling – Login/session management in client state

⚙️ Backend (/kepapro_back_updaeted)

Node.js – Server runtime

Express.js – RESTful API framework

MongoDB + Mongoose – NoSQL data storage and schema modeling

Bcrypt.js – Password hashing

JSON Web Tokens (JWT) – Authentication and secure route access

CORS + dotenv – Environment management and API access control

🧱 Core Features

✅ User authentication (Register/Login)
✅ Protected routes and JWT token validation
✅ Anime list and detail pages with dynamic content
✅ Real-time user state with Redux
✅ Responsive design (mobile-friendly)
✅ Secure API communication between frontend and backend

🗂️ Folder Structure

Frontend (/kepapro)

src/
 ├── components/     # Reusable UI components
 ├── pages/          # Main pages (Home, Login, AnimeDetail, etc.)
 ├── redux/          # Redux slices and store setup
 ├── utils/          # Helper functions (API calls, auth)
 └── App.js          # Root app component


Backend (/kepapro_back_updaeted)

src/
 ├── config/         # Database and environment setup
 ├── controllers/    # Request logic and business layer
 ├── middleware/     # JWT verification, error handling
 ├── models/         # MongoDB schemas (User, Anime, etc.)
 ├── routes/         # API endpoints
 ├── server.js       # Express server entry point
 └── .env            # Environment variables

🚀 How to Run the Project Locally
🔧 Prerequisites

Node.js and npm installed

MongoDB local instance or Atlas URI

Git

1️⃣ Clone Both Repositories
git clone https://github.com/kanishk1122/kepapro.git
git clone https://github.com/kanishk1122/kepapro_back_updaeted.git

2️⃣ Install Dependencies
# Frontend
cd kepapro
npm install

# Backend
cd ../kepapro_back_updaeted
npm install

3️⃣ Configure Environment Variables (Backend)

Create a .env file in /kepapro_back_updaeted:

PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key

4️⃣ Start Servers
# Backend
npm run dev

# Frontend (in separate terminal)
npm start


Access the app at: http://localhost:3000

📡 API Overview
Method	Endpoint	Description
POST	/api/auth/register	Register new user
POST	/api/auth/login	Login existing user
GET	/api/anime	Fetch all anime data
GET	/api/anime/:id	Fetch single anime detail
POST	/api/favorites	Add anime to favorites
GET	/api/favorites/:userId	Fetch user’s favorite list
🔐 Security & Optimization

JWT-based session handling for secure authentication

Passwords encrypted via Bcrypt

CORS and environment variable protection

Optimized MongoDB queries using indexing and lean()

API-level validation and structured error handling

🧠 Future Improvements

Integration of live video streaming service

Admin dashboard for content upload and management

User profile and playlist features

AI-based anime recommendations

👨‍💻 Developer

Kanishk Soni
Full Stack Developer | MERN Stack | Next.js | Node.js | Redis | Kafka (Learning)
📧 kanishk21soni@gmail.com

🌐 Portfolio
 │ GitHub
 │ LinkedIn
