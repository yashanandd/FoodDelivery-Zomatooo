# Zomatooo 🍔
A modern, full-stack food delivery application built using the MERN stack. Zomatooo provides a seamless end-to-end experience for both customers ordering food and administrators managing the restaurant menu.

## 🚀 Features
- **Interactive Customer Frontend:** A responsive React application where users can browse food categories, manage their carts, and securely checkout.
- **Secure Payments:** Integrated with Stripe for handling real transactions and payment intents safely.
- **Dedicated Admin Dashboard:** A robust control panel for administrators to add, edit, or remove menu items, upload photos, and track incoming user orders.
- **Authentication & Security:** User login and registration powered by JWT (JSON Web Tokens) and Bcrypt for password hashing.
- **Cloud Database:** Hosted on MongoDB Atlas, ensuring flexible and scalable data storage for users, foods, and orders.

## 🛠️ Tech Stack
- **Frontend:** React.js, Vite, React Router, Context API, CSS3
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Atlas), Mongoose
- **Tools/Libraries:** Stripe (Payments), Multer (Image Uploads), JWT, Axios, Nodemon

## ⚙️ How to Run Locally
1. Clone the repository and navigate to the project directory.
2. Run `npm install` inside the `frontend`, `admin`, and `backend` directories.
3. Configure your [.env](cci:7://file:///c:/Users/hiii/Downloads/FoodDelivery-Tomato-main/FoodDelivery-Tomato-main/food-del/backend/.env:0:0-0:0) variables in the backend for MongoDB, Stripe, and JWT.
4. Start the backend: `cd backend && npm run server` (runs on `localhost:4000`)
5. Start the frontend: `cd frontend && npm run dev` (runs on `localhost:5174`)
6. Start the admin panel: `cd admin && npm run dev` (runs on `localhost:5175`)
