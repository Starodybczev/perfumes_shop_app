<div align="center">
  <h1>💄 Perfumes App — Frontend</h1>
  <p><strong>React + Redux Toolkit + SCSS</strong></p>
  <img src="../assets/HomePage.png" alt="Perfumes App Frontend Banner" width="100%" />

  <p>
    <img src="https://img.shields.io/badge/React-18.2.0-61DAFB?style=flat&logo=react" />
    <img src="https://img.shields.io/badge/Redux%20Toolkit-1.9.5-764ABC?style=flat&logo=redux" />
    <img src="https://img.shields.io/badge/SCSS-modular-CC6699?style=flat&logo=sass" />
  </p>
</div>

---

## 🧠 Overview

The **frontend** of *Perfumes App* is a modern **React** application providing a dark-themed, elegant interface for browsing and purchasing perfumes.  
It uses **Redux Toolkit** for state management and **SCSS** for modular styling.

---

## 🚀 Features

- 🛍️ Product catalog with images & prices  
- 🔍 Filter and search functionality  
- 🛒 Shopping cart (Add / Remove)  
- 💅 Dark & gold color palette  
- 📱 Fully responsive UI  
- ⚡ Smooth API integration via Axios  

---

## 🧩 Tech Stack

- **React 18**
- **Redux Toolkit**
- **React Router DOM**
- **SCSS (modular structure)**
- **Axios** for API calls

---

## 📂 Folder Structure

```bash
frontend/
│
├── public/
│   ├── fonts/
│   └── index.html
│
└── src/
    ├── App/
    ├── components/
    │   ├── Header/
    │   └── Footer/
    ├── const/
    ├── images/
    ├── Pages/
    │   ├── Home/
    │   ├── Shop/
    │   ├── AboutUs/
    │   └── BinPage/
    ├── styles/
    │   ├── styleComponents/
    │   │   ├── _Home.scss
    │   │   ├── _Shop.scss
    │   │   ├── _Header.scss
    │   │   ├── _Footer.scss
    │   │   ├── _AboutUs.scss
    │   │   ├── _mixins.scss
    │   │   └── _variables.scss
    │   └── main.scss
    ├── toolkit/
    │   ├── Slices/
    │   │   ├── addSliceBinProduct.js
    │   │   └── dataSliceProducts.js
    │   ├── store.js
    │   └── index.js
    ├── App.jsx
    └── index.js                  # React entry point
```
---
## 🧰 Installation & Run
```bash
cd frontend
npm install
npm start
```
---
##🧑‍💻 Developer

Frontend by Viktor Starodubcev
<br/>
Focused on clean UI, reusable components, and efficient state management.
