📘 React Todo App — Daily Learning Project

A simple and clean Todo App built as part of my daily React learning journey.
This project helped me understand core React concepts such as state, props, context API, conditional rendering, and list rendering.

🚀 Features

➕ Add new todos

✏️ Edit todos

✔️ Mark as completed / uncompleted

❌ Delete todos

💾 Autosave to LocalStorage (persists even after refreshing)

🧠 Global state using Context API

🎨 Styled with Tailwind CSS

🛠️ Tech Stack

React

Context API

JavaScript (ES6)

Tailwind CSS

LocalStorage

📂 Folder Structure
src/
 ├─ components/
 │   ├─ TodoForm.jsx
 │   └─ TodoItem.jsx
 ├─ context/
 │   └─ TodoContext.js
 ├─ App.jsx
 ├─ index.jsx
 └─ App.css

🧩 How It Works

TodoContext manages global todo state

TodoForm handles adding new todos

TodoItem handles edit, delete, and toggle

App.jsx stores todos & syncs with LocalStorage

📦 Installation
npm install
npm run dev


Then open your browser at:

http://localhost:5173

🎯 Purpose of This Project

This project helped me practice:

React hooks (useState, useEffect)

Context API for global state

Controlled components

Component composition

Updating and filtering arrays in React