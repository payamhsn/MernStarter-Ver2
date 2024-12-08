# MernStarter Ver2 App

======================

A comprehensive authentication app with state management built with React, Node.js, and MongoDB.

## Features

---

- User registration with email verification
- Login and logout functionality
- Protected routes for authenticated users
- Dashboard page for authenticated users

## Technologies Used

---

- Frontend:
  - React with React Router for client-side routing
  - Vite as the development server and build tool
  - Tailwind CSS for styling
  - Framer Motion for animations
- Backend:
  - Node.js with Express.js as the web framework
  - MongoDB as the database
  - Mongoose for MongoDB ORM
  - JSON Web Tokens (JWT) for authentication
  - Bcrypt for password hashing

### Setup .env file

```bash
MONGO_URI=your_mongo_uri
PORT=5000
JWT_SECRET=your_secret_key
NODE_ENV=development

CLIENT_URL= http://localhost:5173
```

### Run this app locally

```shell
npm run build
```

### Start the app

```shell
npm run start
```
