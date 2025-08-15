# 🛠️ Post Manager App Backend (Node.js + Express + MongoDB)

Backend API for the Post Manager App — a MERN stack CRUD application that allows users to create, read, update, and delete blog posts. This backend handles data storage, validation, and API endpoints, and integrates with MongoDB using Mongoose.

---

## 🚀 Features
- Create, read, update, and delete blog posts
- Optional query parameters for pagination (`limit` and `start`)
- Fetch single post by ID
- Error handling with consistent response structure
- Modular controller and route structure
- MongoDB integration with Mongoose

---

## 🛠 Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Tools:** Nodemon, dotenv, Postman for API testing

---

## 📂 Folder Structure
backend/
│
├── src/
│ ├── controller/ # Controllers for business logic
│ │ ├── postcontroller.js
│ │ ├── productcontroller.js
│ │ └── usercontroller.js
│ │
│ ├── models/ # Mongoose schemas
│ │ ├── post.js
│ │ ├── product.js
│ │ └── user.js
│ │
│ ├── routes/ # API route definitions
│ │ ├── postroutes.js
│ │ ├── productroutes.js
│ │ └── userroutes.js
│ │
│ ├── utils/ # Utility functions
│ │ ├── response.js
│ │ ├── sendEmail.js
│ │ └── sendGrid.js
│ │
│ ├── middleware/ # Middleware (auth, validations)
│ ├── templates/ # Email templates
│ ├── app.js # Express app configuration
│ ├── nodelec.js # Entry point (server startup)
│ └── .env # Environment variables
│
├── package.json # Dependencies
├── package-lock.json
└── README.md
