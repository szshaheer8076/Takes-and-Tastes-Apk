# Takes and Tastes – Full-Stack Food Delivery App

A complete food delivery application built with **React Native (Expo)**, **Node.js/Express**, and **MongoDB**.  
Browse restaurants, manage carts, place orders, and track your food – all in one production-ready codebase.

---

## 📱 Download APK

You can try the app instantly by installing the APK:

👉 **Download APK:**  
[Takes and Tastes – Android APK](https://drive.google.com/file/d/1C5rNf5YdV0jUfu2PRy08hz6VR-vaahec/view?usp=drivesdk)



---

 ✨ Features

- 🔐 **JWT Authentication**
  - User registration & login  
  - Secure password hashing (bcrypt)
- 🏪 **Restaurant Management**
  - Restaurant listing by category  
  - Search & basic filters
- 🍽️ **Menu & Items**
  - Per-restaurant menus  
  - Item name, price, image support
- 🛒 **Shopping Cart**
  - Add / remove items  
  - Update quantities  
  - Cart total calculation
- 📦 **Order System**
  - Place orders  
  - Order status tracking  
  - Order history
- 👤 **User Profiles**
  - Profile information  
  - Delivery addresses
- 📱 **Mobile UI**
  - React Native + Expo  
  - React Native Paper components  
  - Ready for Android & iOS
- 🛠️ **Admin-Ready Backend**
  - Endpoints for managing restaurants, menu items, and orders  
  - Extendable for an admin dashboard


 🧱 Tech Stack

**Frontend (Mobile App)**  
- React Native (Expo)  
- React Navigation  
- Context API (state management)  
- Axios (API requests)  
- React Native Paper (UI components)

**Backend (API)**  
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- JWT Authentication  
- bcrypt password hashing  
- RESTful API architecture

**Database**  
- MongoDB / MongoDB Atlas  
- Collections:
  - `users`
  - `restaurants`
  - `menuItems`
  - `orders`

---

## 📂 Project Structure

```bash
takes-and-tastes/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── config/
│   ├── .env.example
│   ├── package.json
│   └── README.md
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── screens/
│   │   ├── navigation/
│   │   ├── context/
│   │   └── services/
│   ├── .env.example
│   ├── app.json
│   ├── package.json
│   └── README.md
├── documentation/
│   ├── API_DOCUMENTATION.md
│   ├── DATABASE_SCHEMA.md
│   └── ARCHITECTURE.md
├── screenshots/
│   ├── home.png
│   ├── menu.png
│   ├── cart.png
│   └── order.png
├── README.md
└── LICENSE
