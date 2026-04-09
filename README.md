# 🔐 SecureVault – Full Stack File Sharing Application

## 📌 Project Overview

SecureVault is a **full-stack web application** that enables **secure file sharing between users (sender & receiver)**. The system ensures that only registered users can upload, send, and access files through authentication.

---

## 🚀 Key Features

### 👤 User Authentication

* Users must **register** before accessing the system
* Secure **login system** for both sender and receiver
* Session-based access control

---

### 📤 File Upload (Sender)

* Sender can **upload files securely**
* Files are stored and linked to a specific receiver
* Easy-to-use upload interface

---

### 🔗 File Sharing

* Sender selects or specifies the **receiver**
* Files are shared directly to the receiver’s account
* Controlled and secure file transfer

---

### 📥 File Access (Receiver)

* Receiver logs in to their account
* Can **view shared files in their folder/dashboard**
* Access only the files shared with them

---

### 🔒 Security Features

* Authentication required for all actions
* Restricted access (no unauthorized viewing)
* User-specific file visibility

---

### 🌐 Full Stack Architecture

* Separate **frontend and backend**
* Real-time interaction between UI and server
* Scalable and modular design

---

## 🛠️ Tech Stack

### 🔹 Frontend

* HTML / CSS / JavaScript
* (React / Vite if used)

### 🔹 Backend

* Node.js
* Express.js

### 🔹 Tools

* npm (Node Package Manager)
* VS Code

---

## 📂 Project Structure

```
SecureVault/
│
├── backend/        # Backend server (API handling)
├── frontend/       # Frontend application (UI)
└── README.md
```

---

## ⚙️ Installation & Setup

### ✅ Step 1: Clone the Repository

```
git clone https://github.com/your-username/SecureVault.git
cd SecureVault
```

---

## ▶️ Run the Project

### 🔹 Start Backend Server

Open **Terminal 1**:

```
cd backend
npm install
npm run dev
```

---

### 🔹 Start Frontend Server

Open **Terminal 2**:

```
cd frontend
npm install
npm run dev
```

---

## 🌐 Application Access

* Automatically opens in browser
  OR

```
http://localhost:3000
```

---

## 🔁 Workflow of the Application

1. **User Registration**

   * Both sender and receiver create accounts

2. **Login**

   * Users log in using credentials

3. **File Upload (Sender)**

   * Sender uploads file
   * Selects receiver

4. **File Sharing**

   * File is securely linked to receiver

5. **File Access (Receiver)**

   * Receiver logs in
   * Views/downloads files from their folder

---

## ⚠️ Important Notes

* Run both backend & frontend simultaneously
* Backend must start before frontend
* Do not close terminals while running

---

## 🚀 Future Enhancements

* End-to-end encryption
* File expiry feature
* Email notifications
* Drag & drop upload UI

---

## 👩‍💻 Author

**T. Sujitha Mary**
Department of Artificial Intelligence and Data Science
St. Joseph College of Engineering

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
