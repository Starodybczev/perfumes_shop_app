
---

## ⚙️ `server/README.md`

<div align="center">
  <h1>⚙️ Perfumes App — Server</h1>
  <p><strong>Node.js + Express + SQL</strong></p>
  <p>
    <img src="https://img.shields.io/badge/Node.js-Express-68A063?style=flat&logo=node.js" />
    <img src="https://img.shields.io/badge/MySQL-database-00758F?style=flat&logo=mysql" />
    <img src="https://img.shields.io/badge/API-RESTful-orange?style=flat" />
  </p>
</div>

---

## 🧠 Overview

This is the **backend** of the *Perfumes App*, built with **Node.js + Express**.  
It serves as the API layer for fetching perfume data from the **SQL database** and sending it to the React frontend.

---

## 🧩 Features

- ⚡ REST API for perfume products  
- 💾 SQL database connection  
- 🌐 CORS enabled for frontend  
- 🧱 Environment variables via `.env`  
- 🧠 Minimal, structured codebase  

---

## 🧰 Tech Stack

- **Node.js**
- **Express**
- **MySQL / SQLite**
- **dotenv**
- **cors**

---

## 📂 Folder Structure

```bash
server/
│
├── db/
│   └── perfumes.sql          # Database schema
├── server.js                 # Express entry file
├── package.json
└── .env.example              # Example environment file
```
## ▶️ Run Server
```bash
cd server
npm install
node server.js
```
