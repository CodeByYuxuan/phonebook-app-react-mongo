# 📞 Phonebook App (React + Node.js + MongoDB)

A full-stack contact management application built with **React** for the frontend, **Node.js/Express** for the backend, and **MongoDB Atlas** for persistent storage.

This project is part of the [Full Stack Open](https://fullstackopen.com/en/part3) course and focuses on mastering CRUD operations, backend deployment, environment configuration, and RESTful API development.

---

## 🚀 Features

- Add, update, delete, and list contacts
- Client-side input validation
- Backend data validation with Mongoose
- Real-time notifications on operations
- Responsive UI with React
- MongoDB Atlas for cloud-based data persistence
- RESTful API with Express.js

---

## 🗂 Project Structure

```
Phonebook/
├── backend/           # Node.js + Express backend
│   ├── index.js
│   ├── models/
│   └── controllers/
├── frontend/          # React + Vite frontend
│   ├── src/
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── services/
│   ├── public/
│   ├── index.html
│   └── package.json
```

---

## ⚙️ Getting Started

### 🧩 Prerequisites

- Node.js >= 14
- npm or yarn
- MongoDB Atlas account

---

### 📦 Installation

#### Backend

```bash
cd backend
npm install
```

Set up a `.env` file in `/backend`:

```env
MONGODB_URI=mongodb+srv://<username>:<password>@<cluster-url>/<dbname>?retryWrites=true&w=majority
PORT=3001
```

Start the backend:

```bash
npm start
```

---

#### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🔌 API Endpoints (Backend)

| Method | Endpoint           | Description       |
| ------ | ------------------ | ----------------- |
| GET    | `/api/persons`     | Get all contacts  |
| POST   | `/api/persons`     | Add a new contact |
| PUT    | `/api/persons/:id` | Update a contact  |
| DELETE | `/api/persons/:id` | Delete a contact  |

---

## 🌐 Deployment

You can deploy the backend to [Render](https://render.com/) or [Railway](https://railway.app/), and the frontend to [Netlify](https://netlify.com) or [Vercel](https://vercel.com).

---

## ✅ ESLint Setup

The frontend uses ESLint with:

- `eslint-plugin-react`
- `@eslint/js`
- Vite for fast development

Lint code with:

```bash
npm run lint
```

---

## 📚 Learn More

- [Part 3: Full Stack Open - Node.js and Express](https://fullstackopen.com/en/part3)
- [MongoDB Atlas Setup](https://www.mongodb.com/cloud/atlas)
- [Deploying the backend](https://fullstackopen.com/en/part3/deploying_app_to_internet)

---

## 🧑‍💻 Author

Yuxuan — developed as part of Full Stack Open coursework.

---

## 📝 License

This project is licensed for educational purposes. Use it to learn, extend, and build upon your own full-stack apps.
