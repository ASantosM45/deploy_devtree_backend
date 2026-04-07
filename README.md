
# DevTree Backend

Backend for DevTree, a developer social network application.  
This backend provides authentication, user management, and API endpoints consumed by the frontend.

---

## 🌍 Live Demo
Currently, the backend is not deployed. To test locally, follow the installation instructions below.

---

## 🧠 Features

- User registration and login with JWT authentication
- CRUD operations for user profiles
- Secure password storage (bcrypt)
- API endpoints for frontend consumption
- Middleware for route protection

---

## 🛠️ Technologies

- Node.js
- Express
- MongoDB / Mongoose
- JWT for authentication
- dotenv for environment variables

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/ASantosM45/deploy_devtree_backend.git
cd deploy_devtree_backend
````

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file (you can use `.env.example` as a template):

```bash
PORT=3000
DB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

4. Start the development server:

```bash
npm run dev
```

The backend will run on `http://localhost:3000`.

---

## 🔌 API Endpoints

| Method | Endpoint       | Description         |
| ------ | -------------- | ------------------- |
| POST   | /auth/register | Register a new user |
| POST   | /auth/login    | Login and get JWT   |
| GET    | /users         | List all users      |
| GET    | /users/:id     | Get a specific user |
| PUT    | /users/:id     | Update user profile |
| DELETE | /users/:id     | Delete user         |

> ⚠️ Note: For full functionality, connect the backend to a MongoDB database.

---

## 🔧 Environment Variables

Make sure to create a `.env` file with the following variables:

```bash
PORT=
DB_URI=
JWT_SECRET=
```

## 🔗 Frontend

Frontend repository: [DevTree Frontend](https://github.com/ASantosM45/deploy_devtree_frontend)

---




