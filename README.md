# 📝 React Todo App (Context API)

A simple and elegant **Todo Application** built using **React**, **Context API**, and **LocalStorage**.  
This app allows users to add, edit, delete, and mark todos as completed, with data persistence across page reloads.

---

## 🚀 Features

- ➕ Add new todos
- ✏️ Edit existing todos
- ❌ Delete todos
- ✅ Mark todos as completed
- 💾 Persistent storage using **LocalStorage**
- 🌐 Global state management using **Context API**
- 🎨 Styled using **Tailwind CSS**

---

## 🛠️ Tech Stack

- **React**
- **Context API**
- **Tailwind CSS**
- **LocalStorage**

---

📂 Project Structure

TodoContext/
│
├── src/
│   │
│   ├── assets/
│   │   └── react.svg
│   │
│   ├── components/
│   │   ├── TodoForm.jsx
│   │   ├── TodoItem.jsx
│   │   └── index.js
│   │
│   ├── contexts/
│   │   ├── TodoContext.js
│   │   └── index.js
│   │
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
│   └── index.js
│
├── .gitignore
├── README.md
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
└── vite.config.js

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/todo-context-app.git
2. Navigate to project directory

     -- cd todo-context-app
3.  Install dependencies

   -- npm install
4.  Start the development server

   --  npm run dev

🧠 How It Works
🔹 Context API

* TodoContext provides global access to:

  -- todos list

  -- addTodo

  -- updateTodo

  -- deleteTodo

  --  toggleComplete

🔹 LocalStorage

*  Todos are automatically saved to localStorage

   --- Data persists even after browser refresh

📌 Future Improvements

  🔍 Search todos

   📅 Due dates

   🌙 Dark/Light mode

  📱 Mobile responsiveness

  🙋‍♂️ Author

  Bhupendra Singh
  Made with ❤️ using React

  ⭐ If you like this project, don’t forget to star the repository!
