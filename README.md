# 🏥 MedEase - Full Stack Hospital Management System (MERN)

![React](https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Material UI](https://img.shields.io/badge/MaterialUI-007FFF?style=for-the-badge&logo=mui&logoColor=white)

MedEase is a **Full Stack Hospital Management System** built using the **MERN Stack**.  
It provides a complete hospital workflow including **doctor appointment booking, prescription PDF generation, lab report uploads, billing, and medical history tracking**.

This project includes **role-based dashboards** for **User, Doctor, and Admin** with a modern and responsive UI.

# 🌐 Live Demo

## 👤 User Website
🔗 https://medease-user.vercel.app/

## 🛠️ Admin Website
🔗 https://medease-admin.vercel.app/

# 🚀 Key Features

## 👤 User Dashboard
* User authentication (Login/Register)
* Browse doctors by specialization
* Book doctor appointments
* View appointment history
* View prescriptions (PDF)
* View uploaded lab reports
* Medical history tracking

## 🩺 Doctor Dashboard
* View patient appointments
* Confirm and manage appointments
* Generate prescriptions in PDF format
* Add medicine details (dosage, days, before/after food)
* View patient medical history
* Access uploaded lab reports

## 🛠️ Admin Dashboard
* Manage doctors and users
* Approve and manage appointments
* Upload lab reports (PDF)
* Billing management
* View all prescriptions and reports
* Dashboard monitoring and analytics

## 🌟 Additional Features
* Role-based authentication (User / Doctor / Admin)
* Real-time doctor availability & appointment updates
* Prescription PDF generation
* Lab report upload & download support
* Multi-language support
* Fully responsive UI (Mobile + Desktop)

# 🛠️ Tech Stack

## Frontend
* React.js
* Tailwind CSS
* Material UI (MUI)
* Axios

## Backend
* Node.js
* Express.js

## Database
* MongoDB (Mongoose)

## Tools & Libraries
* JWT Authentication
* Multer (File Upload)
* PDF Generation (PDFKit / jsPDF)

---

# 🔐 Authentication & Role Management

The project uses **JWT-based authentication** and provides role-based access:

* **User** → Book appointments, view prescriptions, lab reports  
* **Doctor** → Manage appointments, generate prescriptions  
* **Admin** → Full access to hospital management system  

# 📂 Project Structure

Hospital-Management-System/
│── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── utils/
│   └── server.js
│
│── frontend-user/
│   ├── src/
│   └── package.json
│
│── frontend-admin/
│   ├── src/
│   └── package.json

⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2️⃣ Backend Setup
cd backend
npm install
Create a .env file inside the backend folder:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
Run backend:

npm start
3️⃣ User Frontend Setup
cd frontend-user
npm install
npm start
4️⃣ Admin Frontend Setup
cd frontend-admin
npm install
npm start
📌 Environment Variables
  Backend requires the following environment variables:

    Variable	Description
    PORT	Backend server port
    MONGO_URI	MongoDB database connection string
    JWT_SECRET	JWT secret key
📄 Modules Implemented
  Doctor Appointment Booking System
  Doctor Availability Tracking
  Prescription Management (PDF)
  Lab Report Upload and Viewing (PDF)
  Medical History Tracking
  Billing System
  Role-Based Dashboards (User / Doctor / Admin)

👨‍💻 Author
Muhammad Suhail
Full Stack Developer (MERN)

⭐ Support
If you like this project, please give it a ⭐ on GitHub!
