# 🎓 College Management System (MERN)

[![MERN Stack](https://img.shields.io/badge/Stack-MERN-blue)](https://www.mongodb.com/mern-stack)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-v14+-green)](https://nodejs.org)
[![React](https://img.shields.io/badge/React-v17+-blue)](https://reactjs.org)

A complete **MERN Stack College Management System** built to streamline academic operations, manage student/faculty data, track branches, subjects, timetables, notices, study materials, and more.  
This system provides role-based dashboards for **Admin, Faculty, and Students**.

---

## ✨ Features Overview

---

## 🔐 Admin Panel

- Manage faculty accounts with profiles & emergency contact info  
- Manage student accounts (enrollment, semester, academic data)  
- Add/update/delete branches  
- Subject/course management by semester & branch  
- Create & manage notices  
- Upload/manage timetables  
- Profile update + password change  
- Centralized control dashboard  

---

## 👨‍🏫 Faculty Panel

- Manage personal profile  
- Upload study materials (notes, assignments, syllabus)  
- Filter materials by semester, branch, subject  
- View/manage timetables  
- Search students (enrollment, name, semester)  
- Read & respond to notices  
- Update password and profile information  

---

## 🎓 Student Panel

- View profile and academic info  
- Access study materials  
- View/download class timetable  
- Read notices & announcements  
- Update profile  
- Manage password  

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Context API  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Auth:** JWT  
- **Email Service:** Nodemailer  

---

## 📦 Prerequisites

Ensure you have installed:

- Node.js  
- MongoDB  
- npm / yarn  

---

## 🚀 Project Setup (Full Guide)

📺 **Setup Video Tutorial:**  
https://youtu.be/gw4jh4RHzuo

### 1️⃣ Clone the Repository

```bash
git clone <repository-url>
cd College-Management-System
```

### 2️⃣ Install Dependencies

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

---

## 📄 Environment Setup

### 3️⃣ Backend `.env`

```
MONGODB_URI=mongodb://127.0.0.1:27017/College-Management-System
PORT=4000
FRONTEND_API_LINK=http://localhost:3000
JWT_SECRET=THISISSECRET

NODEMAILER_EMAIL=
NODEMAILER_PASS=
```

### 4️⃣ Frontend `.env`

```
REACT_APP_APILINK=http://localhost:4000/api
REACT_APP_MEDIA_LINK=http://localhost:4000/media
```

---

## ▶️ Start the Servers

```bash
# Backend (inside backend folder)
npm run dev

# Frontend (inside frontend folder)
npm start
```

---

## 🧩 Initial Admin Setup

Seed the database:

```bash
cd backend
npm run seed
```

Default Admin Login:

- **Employee ID:** 123456  
- **Password:** admin123  
- **Email:** admin@gmail.com  

---

## 📁 Project Structure

```
college-management-system/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── utils/
│   ├── media/
│   └── README.md
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── utils/
│   └── public/
└── README.md
```

---

## 📞 Support / Contact

For any doubts or issues, feel free to reach out:

- 🌐 Website: **(https://sachinbodare-portfolio.netlify.app/)**  
- 📧 Email: **sachinbodare2@gmail.com**  
- 🔗 LinkedIn: **https://linkedin.com/in/sachin-bodare**

---

## 🤝 Contributing

Contributions are welcome!  
- Fork the repo  
- Create a feature branch  
- Commit changes  
- Open a Pull Request  

---

## 📜 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

