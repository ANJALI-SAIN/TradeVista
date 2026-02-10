#TradeVista

A modern stock trading dashboard inspired by real-world brokerage platforms, focused on scalable frontend architecture, clean UX, and production-ready patterns.

#Features

User authentication (JWT-based)

Real-time stock price UI

Dashboard with portfolio overview

Search & filter stocks

Interactive charts

Fully responsive design

Centralized error handling

Tech Stack

#Frontend

React.js

JavaScript (ES6+)

HTML5, CSS3

Chart.js / Recharts

#Backend (Planned / Implemented)

Node.js

Express.js

MongoDB

JWT Authentication

#Tools

Git & GitHub

Postman

VS Code

#System Design (High Level)
Client (React)
   |
   |  HTTPS (REST APIs)
   v
Server (Node + Express)
   |
   |  Mongoose ODM
   v
MongoDB Database

#Auth Flow

User → Login → JWT Issued → Stored in Client
→ Protected APIs → Token Verified → Response

#API Routes (Sample)
POST   /api/auth/register   → Register user
POST   /api/auth/login      → Login user
GET    /api/stocks          → Fetch stock list
GET    /api/portfolio       → User portfolio

Anjali Saini
MERN Developer | Backend-focused
📍 Sonipat, Haryana
🔗 GitHub: https://github.com/ANJALI-SAIN
