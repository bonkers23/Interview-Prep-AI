# 🚀 Interview Prep AI

An **AI-powered interview preparation platform** built on the **MERN stack**. It helps users practice role-specific technical interview questions with **AI-generated Q&A** and **concept explanations** powered by **Google Gemini API**.

---

## ✨ Features

- 🔐 **Authentication** – Secure login/signup with JWT & bcrypt password hashing
- 👤 **User Profiles** – Profile photo upload with Multer
- 📚 **Interview Sessions** – Create sessions with AI-generated Q&A based on role, experience, and topics
- 📌 **Question Management** – Pin/unpin questions, add personal notes
- 🤖 **AI Explanations** – Get detailed AI-powered concept explanations for any question
- 📱 **Responsive UI** – Built with React + TailwindCSS
- ⚡ **Clean Architecture** – Modular backend with MVC pattern & scalable frontend structure

---

## 🛠️ Tech Stack

**Frontend:** React, Vite, Context API, TailwindCSS, Axios, Framer Motion

**Backend:** Node.js, Express.js, MongoDB (Mongoose), JWT, Bcrypt, Multer, CORS

**AI Integration:** Google Gemini API (@google/genai)

---

## 📂 Project Structure

### Backend

- `config/` → MongoDB connection
- `models/` → User, Session, Question schemas
- `controllers/` → Business logic (Auth, AI, Session, Question)
- `routes/` → API endpoints
- `middlewares/` → JWT auth, file uploads
- `utils/` → AI prompt templates
- `server.js` → Entry point

### Frontend

- `components/` → Reusable UI (Cards, Inputs, Layouts, Modals, Loaders)
- `pages/` → Landing, Auth, Dashboard, InterviewPrep
- `context/` → Global auth state with Context API
- `utils/` → API paths, Axios instance, helpers
- `App.jsx` → Routes
- `index.css` → Tailwind + custom styles

---

## ⚙️ Installation

### 1️⃣ Clone the repo

```bash
git clone https://github.com/your-username/interview-prep-ai.git
cd interview-prep-ai

```

### 2️⃣ Setup Backend

```bash
cd backend
npm install

```

Create a `.env` file:

```
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_gemini_api_key
PORT=8000

```

Run server:

```bash
npm run dev

```

### 3️⃣ Setup Frontend

```bash
cd frontend
npm install
npm run dev

```

---

## 🚀 Usage

1. Register/Login as a user
2. Create a new interview session by entering role, experience, and topics
3. Get AI-generated Q&A, pin questions, add notes
4. Use “Learn More” to get AI-powered concept explanations
5. Manage all sessions from your dashboard

---

## 📸 Screenshots

(Add few screenshots here: Landing page, Dashboard, InterviewPrep page)

---

## 📈 Future Enhancements

- Cloud storage for images (S3/Cloudinary)
- Role-based authorization
- Progress analytics dashboard
- Email verification & forgot password

---

## 👨‍💻 Author

**Shariq Hashmi**

- GitHub: https://github.com/bonkers23
- LinkedIn: https://www.linkedin.com/in/shariq-hashmi-6793a5250/