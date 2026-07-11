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
- Controlled credential management through structured CRUD workflows
- Copy-to-clipboard functionality for quick access
- Password visibility toggle for secure viewing
- Secure handling of credential data through REST APIs
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

- **Frontend:** React (v19), Vite, Tailwind CSS (v4), React-Toastify, UUID, Lordicon
- **Backend:** Node.js, Express (v5.x), Body-Parser, Cors, Dotenv
- **Database:** MongoDB (Connected via official `mongodb` driver)
- **Tools:** MongoDB Compass

---

## 📁 Project Structure

```text
PassVault/
├── Backend/                # Express backend server
│   ├── .env                # Backend environment variables
│   ├── package.json        # Backend dependencies (express, mongodb, etc.)
│   └── server.js           # Server logic and API endpoints
├── public/                 # Static assets for the frontend
├── src/                    # Frontend React code
│   ├── assets/             # Images and design assets
│   ├── components/         # React components
│   │   ├── Footer.jsx      # Footer component
│   │   ├── Manager.jsx     # Main Credential Manager component
│   │   └── Navbar.jsx      # Navigation bar component
│   ├── App.css             # Component-level styles
│   ├── App.jsx             # Shell React component
│   ├── index.css           # Global CSS and Tailwind directives
│   └── main.jsx            # Entry point for React
├── package.json            # Frontend dependencies and scripts
├── tailwind.config.js      # Tailwind configurations
├── vite.config.js          # Vite configurations
└── README.md               # Project documentation
```

---

## 🚀 Getting Started

Follow these steps to set up and run the application locally.

### Prerequisites

Ensure you have the following installed on your local machine:
- [Node.js](https://nodejs.org/) (v16+ recommended)
- [MongoDB Community Server](https://www.mongodb.com/try/download/community) (running locally on port `27017`)
- [MongoDB Compass](https://www.mongodb.com/products/compass) (optional, for viewing database collections)

### Installation & Run

#### 1. Backend Server Setup
1. Navigate to the `Backend` directory:
   ```bash
   cd Backend
   ```
2. Install the backend dependencies:
   ```bash
   npm install
   ```
3. Start the Express server:
   ```bash
   node server.js
   ```
   The backend will run on [http://localhost:3000](http://localhost:3000).

#### 2. Frontend Setup
1. Open a new terminal in the project root directory.
2. Install the frontend dependencies:
   ```bash
   npm install
   ```
3. Start the Vite development server:
   ```bash
   npm run dev
   ```
   Open your browser and navigate to the address shown (usually [http://localhost:5173](http://localhost:5173)).

---

## 📌 Purpose
This project was developed to gain hands-on experience in frontend development, secure data handling, database-backed applications, and API-driven workflows.

