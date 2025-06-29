# SkillSync Frontend

🚀 **SkillSync** is a responsive, modern web application that allows users to upload their resume and paste a job description to receive a skill match analysis. This is the **frontend** of the application, built with **React**, **Vite**, and **Tailwind CSS**.

## 🌐 Live Demo

[🔗 Visit the Live Website](https://your-vercel-link.vercel.app)  
> _Replace the link above with your actual deployed URL_

---

## 📁 Project Structure
frontend/
├── public/ # Static files (e.g., images, favicon)
├── src/
│ ├── components/ # Reusable components (Navbar, Forms, Inputs, etc.)
│ ├── context/ # Auth context and global state
│ ├── pages/ # Page-level components (Home, Login, Analyze, etc.)
│ ├── App.jsx # Main app layout
│ ├── main.jsx # Entry point for React
│ └── index.css # Tailwind + custom styles
├── .gitignore
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
└── vite.config.js

---

## ⚙️ Technologies Used

- ⚛️ React (with Hooks and Router)
- ⚡ Vite (fast bundler)
- 🎨 Tailwind CSS (utility-first styling)
- 🔐 JWT & Auth Context (for protected routes)
- 📦 Axios (API handling)
- 🌗 Dark mode toggle

---

## 📦 Setup Instructions

### ✅ Local Development

```bash
cd frontend
npm install
npm run dev
