 Online Voting System
Overview

This project is a web-based Online Voting System that allows users to securely participate in elections, cast votes, and view results digitally. It eliminates the need for physical polling and ensures efficient and transparent voting.

🎯 Features
User Registration & Login
Admin Dashboard
Candidate Management
Secure Voting System (one vote per user)
Real-time Result Display
Election Management
🧠 Tech Stack
Frontend: React.js
Backend: Spring Boot
Database: MySQL
API: REST APIs
📂 Project Structure

online-voting-system/
│
├── frontend/ # React application
├── backend/ # Spring Boot APIs
├── database/ # SQL scripts
└── README.md

🔄 Workflow

User Registration → Login → View Elections → Vote → Store in DB → Display Results

👥 User Roles
🔹 Admin
Manage elections
Add/Edit candidates
View results
🔹 User (Voter)
Register/Login
Cast vote
View results
🌐 Key Modules
Authentication Module
Voting Module
Admin Panel
Results Dashboard
▶️ Run Locally
Backend

cd backend
mvn spring-boot:run

Frontend

cd frontend
npm install
npm start

📊 Features Highlights
Secure and scalable voting system
Role-based access control
Real-time vote counting
User-friendly interface
🚀 Future Enhancements
OTP-based authentication
Blockchain-based voting
Face recognition verification
Cloud deployment
