# 🔐 PassVault – Credential Management Web Application

PassVault is a credential management web application built using **React.js**, **Tailwind CSS** and **MongoDB**.  
It allows users to securely store, view, and manage website credentials including URLs, usernames, and passwords through a clean and interactive interface.

---

## 🚀 Features

### 🌍 Frontend
- Built using **React.js** with a modern, responsive UI
- Animated action icons for copy, edit, and delete operations
- Hover effects on interactive components to improve visual feedback and usability
- Clickable website URLs that redirect directly to the saved site
- Password visibility toggle for secure viewing
- Clean table-based layout for easy credential management

### 🔧 Backend & Data Handling
- Credential data stored using **MongoDB** (managed locally via MongoDB Compass)
- REST-style API integration for data operations
- Secure handling of credential data during storage and retrieval

### 🔐 Security
- Passwords are stored in **hashed format**
- Copy-to-clipboard functionality retrieves the correct password when required
- Edit and delete actions protected through controlled UI flows

### 🗄️ Data Management
- Supports **CRUD operations** for credentials:
  - Create new credentials
  - Read saved entries
  - Update existing records
  - Delete entries when no longer needed

### 🔄 Storage Versions
- Two implementations supported:
  - **LocalStorage-based version** for client-side persistence
  - **MongoDB-backed version** for database-driven storage

---

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS 
- **Database:** MongoDB  
- **Tools:** MongoDB Compass  
- **APIs:** REST-style APIs

---

## 📌 Purpose
This project was developed to gain hands-on experience in frontend development, secure data handling, database-backed applications, and API-driven workflows.

