
A backend project built by following the **Chai aur Code Backend Series** and completing the remaining implementation as a hands-on learning project.

This project is a **YouTube-style backend** built with **Node.js, Express.js, MongoDB, and Mongoose**, covering authentication, user management, media handling, and backend architecture fundamentals.
---

- [Model link](https://app.eraser.io/workspace/YtPqZ1VogxGy1jzIDkzj?origin=share)

## About the Project

This repository is inspired by the backend series by **Hitesh Choudhary**.  
The project was designed as a practical backend learning exercise where the core structure and guidance were provided, while learners were encouraged to complete the remaining parts on their own.

I used this project to understand how a real backend is structured and how different backend components work together in a complete application.

---

## Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB**
- **Mongoose**
- **JWT Authentication**
- **bcrypt**
- **Multer**
- **Cloudinary**
- **Cookie Parser**
- **CORS**
- **dotenv**

---

## Features

This backend project is built around a **video hosting / content platform** and includes functionality such as:

- User registration and login
- JWT-based authentication
- Access token and refresh token flow
- Password hashing using bcrypt
- User profile management
- Video upload handling
- Cloudinary integration for media storage
- Protected routes with middleware
- MongoDB schema design with Mongoose
- Cookie handling and authentication flow
- Scalable backend folder structure

---

## Project Structure

```bash
src/
│── controllers/      # Route logic / controller functions
│── db/               # Database connection setup
│── middlewares/      # Auth, upload, error handling middleware
│── models/           # Mongoose models/schemas
│── routes/           # API route definitions
│── utils/            # Utility functions/helpers
│── app.js            # Express app configuration
│── index.js          # Entry point