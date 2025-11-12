🌀 Kepapro – Anime Streaming Platform

A full-stack anime streaming web application built with the MERN architecture (MongoDB, Express.js, React.js, Node.js).
The platform enables users to explore and stream anime content securely with authentication, real-time updates, and optimized API performance.

🌐 Project Overview

Kepapro is a production-grade streaming platform that combines a powerful backend API with a responsive frontend interface.
It focuses on security, scalability, and real-time user experience.

🧩 Architecture Overview
Frontend (React + Redux)
        ↓
Backend API (Node.js + Express)
        ↓
Database Layer (MongoDB + Mongoose)
        ↓
Authentication (JWT + Bcrypt)

🔁 Data Flow

Frontend (React) handles UI rendering, routing, and state management via Redux.

Backend (Express + Node.js) serves RESTful APIs for authentication, data, and video content.

MongoDB stores users, anime data, and favorites using schema-based models.

JWT ensures secure session-based access and protected routes.

⚙️ Tech Stack
🧠 Frontend

Repository: GitHub – Kepapro Frontend

Built With:

React.js

Redux Toolkit (State Management)

Axios (API Handling)

React Router DOM

Tailwind CSS (Responsive UI)

JWT Authentication (Client-Side Validation)

⚙️ Backend

Repository: GitHub – Kepapro Backend

Built With:

Node.js

Express.js

MongoDB + Mongoose

JWT (Authentication)

Bcrypt.js (Password Hashing)

dotenv + CORS (Environment Config & Security)

🧱 Core Features

✅ User Registration & Login (JWT Authentication)
✅ Secure Password Hashing (Bcrypt)
✅ Protected Routes for Authorized Access
✅ Dynamic Anime List and Detail Pages
✅ User Favorites and Watchlist
✅ Fully Responsive UI (Desktop & Mobile)
✅ Real-Time Updates using Redux

🗂️ Folder Structure
Frontend (/kepapro)
src/
 ├── components/     # Reusable UI components
 ├── pages/          # Core pages (Home, Login, AnimeDetail)
 ├── redux/          # Redux slices & store
 ├── utils/          # Helper functions & API handlers
 ├── App.js          # Root app component
 └── index.js        # React DOM entry point

Backend (/kepapro_back_updaeted)
src/
 ├── config/         # Database connection setup
 ├── controllers/    # Business logic and request handlers
 ├── middleware/     # JWT auth, error handling
 ├── models/         # Mongoose schemas (User, Anime, etc.)
 ├── routes/         # API endpoints
 ├── server.js       # Main server entry point
 └── .env            # Environment variables

🚀 Setup & Installation
🔧 Prerequisites

Node.js (v16+)

MongoDB (Local or Atlas)

Git

🧩 Step 1: Clone Both Repositories
git clone https://github.com/kanishk1122/kepapro.git
git clone https://github.com/kanishk1122/kepapro_back_updaeted.git

🧩 Step 2: Install Dependencies
# Frontend
cd kepapro
npm install

# Backend
cd ../kepapro_back_updaeted
npm install

🧩 Step 3: Configure Environment (Backend)

Create a .env file inside /kepapro_back_updaeted:

PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key

🧩 Step 4: Run Servers
# Run Backend
npm run dev

# Run Frontend (in new terminal)
npm start


➡️ App runs on http://localhost:3000

📡 API Endpoints (Backend)
Method	Endpoint	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	Login existing user
GET	/api/anime	Fetch anime list
GET	/api/anime/:id	Fetch anime details
POST	/api/favorites	Add anime to favorites
GET	/api/favorites/:userId	Get user favorites
🔐 Security & Optimization

JWT-based secure sessions

Password encryption using Bcrypt

Optimized MongoDB queries (lean + indexing)

CORS configuration for safe API communication

Environment-based configurations using dotenv

🧠 Future Enhancements

Admin Dashboard for content management

Real-time video streaming module

User profile and activity tracking

Recommendation engine using AI-based filtering

👨‍💻 Developer

Kanishk Soni
Full Stack Developer | MERN | Next.js | Redis | Kafka (Learning)
📧 kanishk21soni@gmail.com

🌐 Portfolio
 │ GitHub
 │ LinkedIn
