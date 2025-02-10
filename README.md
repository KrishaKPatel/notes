# Full Stack Notes App

This is a full-stack Notes App built using the **MERN** stack (**MongoDB, Express.js, React.js, Node.js**). The app includes functionalities like authentication (Login & Sign Up), adding/editing notes, pinning important notes, and searching through the notes.

## 🚀 Features
- User Authentication (JWT-based Login & Sign Up)
- CRUD operations for Notes (Add, Edit, Delete, Search)
- Pin Notes to prioritize important ones
- Responsive UI built with **React.js & Tailwind CSS**
- Backend with **Node.js, Express.js, and MongoDB Atlas**
- Secure API endpoints with JWT Authentication

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS, React Router
- **Backend:** Node.js, Express.js, MongoDB (Atlas)
- **Authentication:** JWT (JSON Web Token)
- **State Management:** React Context API
- **API Client:** Axios

## 📂 Project Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/KrishaKPatel/notes.git
cd notes
```

### 2️⃣ Install dependencies
#### Frontend:
```bash
cd frontend
npm install
```
#### Backend:
```bash
cd backend
npm install
```

### 3️⃣ Start the development server
#### Backend:
```bash
cd backend
npm start
```
localhost:8000

#### Frontend:
```bash
cd frontend
npm run dev
```
localhost:5173

add /login

## 🎯 API Endpoints
| Method | Endpoint          | Description            |
|--------|------------------|------------------------|
| POST   | /api/auth/signup | Register a new user   |
| POST   | /api/auth/login  | Login user            |
| GET    | /api/notes       | Get all notes         |
| POST   | /api/notes       | Create a new note     |
| PUT    | /api/notes/:id   | Update a note         |
| DELETE | /api/notes/:id   | Delete a note         |

