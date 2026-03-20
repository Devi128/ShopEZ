# Technical Architecture - SHOPEZ E-commerce Application

## Overview
The SHOPEZ application follows the MERN stack architecture, consisting of Frontend, Backend, and Database layers.

---

## Frontend (Client Side)
The frontend is developed using React.js and is responsible for user interaction and UI rendering.

### Components:
- User Authentication (Login/Register)
- Product Listing
- Cart Management
- Order Placement
- User Profile
- Admin Dashboard

### Technologies:
- React.js
- Axios
- Tailwind CSS

---

## Backend (Server Side)
The backend is built using Node.js and Express.js. It handles business logic and API requests.

### API Endpoints:
- /api/users
- /api/products
- /api/orders
- /api/cart

### Features:
- JWT Authentication
- Admin Authorization
- RESTful APIs

---

## Database
MongoDB is used as the database to store application data.

### Collections:
- Users
- Products
- Orders
- Cart

---

## Architecture Flow
The frontend communicates with the backend via API calls. The backend processes the request and interacts with the MongoDB database to fetch or store data.

Frontend → Backend → Database