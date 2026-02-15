# 📝 NotesX – Full Stack MERN Notes Application

NotesX is a production-ready full-stack MERN application that allows users to create, view, and delete notes with secure backend APIs and rate limiting.

Live Demo: https://notesx-r6as.onrender.com

---

## 🚀 Tech Stack

### Frontend
- React.js
- Axios
- React Hooks (useState, useEffect)
- React Hot Toast

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- Upstash Redis (Rate Limiting)
- Dotenv

### Deployment
- Render (Backend Hosting)
- MongoDB Atlas (Cloud Database)
- Upstash Redis (Serverless Redis)

---

## 🔥 Features

- Create, delete and fetch notes
- RESTful API architecture
- MongoDB Atlas cloud integration
- Rate limiting using Upstash Redis
- Production deployment on Render
- Environment variable configuration
- Error handling and clean architecture

---

## 📂 Project Structure

```
NotesX/
│
├── frontend/
│ ├── components/
│ ├── pages/
│ ├── lib/
│ └── App.jsx
│
├── backend/
│ ├── src/
│ │ ├── models/
│ │ ├── routes/
│ │ ├── middleware/
│ │ └── server.js
│ └── package.json
│
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the backend folder:
MONGO_URI=your_mongodb_connection_string
UPSTASH_REDIS_REST_URL=your_upstash_url
UPSTASH_REDIS_REST_TOKEN=your_upstash_token
PORT=5001


For production (Render), configure these in the Environment section.

---

## 🛠 Installation (Local Setup)

### 1️⃣ Clone the repository
git clone https://github.com/saikartik2625/NotesX.git
cd NotesX



### 2️⃣ Install backend dependencies
cd backend
npm install
npm run dev


### 3️⃣ Install frontend dependencies
cd frontend
npm install
npm run dev


---

## 📡 API Endpoints

| Method | Endpoint        | Description        |
|--------|-----------------|-------------------|
| GET    | /api/notes      | Fetch all notes   |
| POST   | /api/notes      | Create a note     |
| DELETE | /api/notes/:id  | Delete a note     |

---

## 🧠 Architecture

React Frontend  
⬇  
Express Backend (Render)  
⬇  
MongoDB Atlas (Cloud Database)  
⬇  
Upstash Redis (Rate Limiting)

---

## 🏆 Learning Highlights

- Implemented production-grade MERN architecture
- Integrated cloud database and serverless Redis
- Handled deployment environment variables
- Implemented middleware-based rate limiting
- Debugged DNS and environment configuration issues

---

## 👨‍💻 Author

Kartik  
Full Stack Developer | MERN Stack Enthusiast

---

## 📜 License

This project is open-source and free to use.
