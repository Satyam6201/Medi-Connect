<div align="center">

# 🏥 Medi-Connect — Doctor Appointment Booking System

<p align="center">

<a href="https://prescripto.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/🌐 Live%20Demo-Visit%20Website-22c55e?style=for-the-badge" />
</a>

<a href="https://github.com/Satyam6201/Medi-Connect" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-Repository-000000?style=for-the-badge&logo=github&logoColor=white" />
</a>

</p>

</div>

---

## 📌 Project Overview

**Medi-Connect** is a full-stack Doctor Appointment Booking Web Application built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.
The platform allows patients to book appointments with doctors online, doctors to manage their schedules and earnings, and administrators to manage the entire system.

This system can be used by:

* Hospitals
* Clinics
* Individual Doctors

The application provides **3-level authentication** and a complete workflow from appointment booking to online payment.

---

## 🚀 Features

### 👤 Patient Panel

* User Registration & Login (JWT Authentication)
* Browse doctors by specialization
* View doctor profile & availability
* Book appointments
* Online payment for appointment fees
* View & manage booked appointments
* Cancel appointments

### 🩺 Doctor Dashboard

* Secure doctor login
* View patient appointments
* Track earnings
* Update profile details
* Manage availability
* Accept / reject appointments

### 🛠 Admin Dashboard

* Manage all doctors
* Add / remove doctors
* Manage appointments
* Monitor users
* Control platform data

---

## 🔐 Authentication System

The application contains **3 different authentication systems:**

| Role    | Access                       |
| ------- | ---------------------------- |
| Patient | Book and manage appointments |
| Doctor  | View appointments & earnings |
| Admin   | Manage doctors & platform    |

Authentication is implemented using:

* JWT (JSON Web Token)
* Protected Routes
* Role-based authorization

---

## 💳 Online Payment Integration

* Secure online appointment payment
* Payment status tracking
* Booking confirmation after payment

---

## 🧰 Tech Stack

### Frontend

* React.js
* React Router DOM
* Axios
* CSS / Modern UI
* Responsive Design

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB
* Mongoose ODM

### Authentication & Tools

* JWT Authentication
* bcrypt password hashing
* Cloudinary (for images)
* Payment Gateway Integration

---

## 📂 Project Structure

```
Medi-Connect
│
├── frontend/          # React Frontend
│   ├── pages/
│   ├── components/
│   ├── assets/
│   └── context/
│
├── backend/           # Node + Express Backend
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── config/
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Satyam6201/Medi-Connect.git
cd Medi-Connect
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside **backend/** and add:

```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

CLOUDINARY_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_SECRET_KEY=your_secret

PAYMENT_GATEWAY_KEY=your_payment_key
```

Run backend:

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd ../frontend
npm install
npm start
```

---

## 🌐 API Modules

* Authentication APIs
* Doctor APIs
* Appointment APIs
* Payment APIs
* Admin Management APIs

---

## 📸 Screenshots

> Add screenshots here (Home Page, Doctor List, Booking Page, Admin Dashboard)

---

## 📈 Future Improvements

* Video consultation (WebRTC)
* Email/SMS appointment reminders
* Prescription download PDF
* Doctor ratings & reviews
* Multi-hospital support

---

## 👨‍💻 Author

**Satyam Kumar Mishra**

* LinkedIn: https://www.linkedin.com/in/satyam-kumar-mishra-9bb980291/
* GitHub: https://github.com/Satyam6201

---

## ⭐ Support

If you like this project, please **star ⭐ the repository** — it really helps and motivates me to build more projects!

---

## 📄 License

This project is created for learning and portfolio purposes.
