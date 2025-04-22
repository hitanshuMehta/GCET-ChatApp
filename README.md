# 🗨️ GCET Real-Time Chat Application

A secure and efficient real-time messaging platform for internal faculty communication, built using the **MERN stack** and **Socket.IO**.

---

## 🚀 Project Overview

This application facilitates real-time communication among faculty members of **G H Patel College of Engineering & Technology (GCET)**. Designed with user-friendliness and security in mind, it supports two main roles:

- **Admin**: Manages users, sends credentials, and monitors activity.
- **User**: Faculty member who can chat, update profile, and recover password via OTP.

---

## ⚙️ Tech Stack

- **Frontend**: React.js + TailwindCSS
- **Backend**: Node.js + Express.js
- **Database**: MongoDB
- **Real-time Communication**: Socket.IO
- **Email Services**: Nodemailer
- **Authentication**: JWT & OTP (One-Time Password)

---

## ✨ Key Features

### 🔐 Admin Features
- Secure admin login using a hardcoded password.
- Add new users with auto-generated passwords.
- Send credentials via email.
- View and delete registered users.

### 👥 User Features
- Login using email/password received from admin.
- Real-time one-on-one chat with faculty.
- Online/offline user indicators.
- Message read receipts and timestamps.
- Edit profile details.
- Share image messages.
- Logout securely.

### 🔄 Password Recovery
- OTP-based email verification.
- Secure password reset.

---
