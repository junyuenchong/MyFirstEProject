# MyFirstEProject
My First React Native Project
# 🛒 E-Commerce Mobile App & Admin Panel

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/eshop-app)
![License](https://img.shields.io/github/license/yourusername/eshop-app)
![Issues](https://img.shields.io/github/issues/yourusername/eshop-app)

#Project Overview

This project is a full-stack e-commerce solution consisting of:

User App: Built with React Native using Expo, featuring Redux for cart state management.

Admin Panel: Developed with React Native for managing products and orders.

Backend: Node.js server handling API requests, payment processing, and order management.

Database: MongoDB for storing users, products, orders, and related data.

Payment Integration: Secure PayPal payment gateway to handle checkout and transactions.

---

## 📲 User Mobile App

### Features

- 🛍️ Browse products with categories
- 📦 Add to cart / edit quantity&remove from cart
- 🔒 Login / Register with JWT auth
- 💳 PayPal payment gateway integration
- 📄 Order history & tracking
- 📞 Phone Verification (Twilio)
- 📧 Email Verification (Nodemailer)

### Screenshots
#### 🔐 User
#### Admin Login 
![image](https://github.com/user-attachments/assets/2af495ec-3fd9-4d6e-851f-fc2529b6ff02)

#### 📝 User Register
![image](https://github.com/user-attachments/assets/689a3a78-044b-46d1-8f20-d40b5b039968)

#### 👤 User Edit Profile
![image](https://github.com/user-attachments/assets/32219915-cddd-49e7-81f6-fd66a3e57891)

#### 🏠 User Address management (CRUD)
![image](https://github.com/user-attachments/assets/1eda618a-03f9-4ae1-99f4-8c4e7d47b922)

#### 🔁 Forgot Password
![image](https://github.com/user-attachments/assets/12287936-d508-48cc-a867-2c734420f97b)

#### 🏠 Home
![image](https://github.com/user-attachments/assets/4cc87701-fedb-4faa-b18d-1a4bbbda410d)

#### 🧺 Cart
![image](https://github.com/user-attachments/assets/e6d9cd46-498d-46f0-bffe-398defff12da)

#### 💳 PayPal Payment 
![image](https://github.com/user-attachments/assets/864e86f6-7bdc-41b4-a518-74b9a7ec69f1)

#### 📝 Order History
![image](https://github.com/user-attachments/assets/8a3fe872-0dac-46bb-9e1f-97fbfd4d551e)

---

## 🧑‍💼 Admin Panel
### Features

- 📦 Product management and Category management (CRUD)
- 🔐 Admin authentication
- 🛍️ Browse products with categories
### Screenshots

#### 📊 Dashboard
![image](https://github.com/user-attachments/assets/2605a212-bd7b-4aac-910b-8349d7d4a2a9)

#### 📦 Product 
![image](https://github.com/user-attachments/assets/f4c16eef-b309-4998-a7c5-1b7dbddfbfe0)


---

## 💳 Payment Gateway

Integrated with **PayPal REST API** for secure checkout.

- Supports sandbox and live modes
- Payment handled via WebView (React Native)
- Backend order verification on success

![image](https://github.com/user-attachments/assets/72957bd8-e36a-4d84-9825-2229ceed35d1)


---

## 🧰 Tech Stack

| Layer      | Tech                              |
|------------|-----------------------------------|
| Frontend   | React Native, React, Redux        |
| Backend    | Node.js, Express.js               |
| Database   | MongoDB (Mongoose)                |
| Auth       | JWT (JSON Web Tokens)             |
| Payment    | PayPal Gateway                    |
          

---

## 🚀 Installation

### Clone the repos:

```bash
# Install Dependencies
npm install
# Run the RESTful API
cd api
npm run
# Run the Mobile App: MyFirstEProject
npx expo run:android

