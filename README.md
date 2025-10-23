# 📝 Manage Your Todos – React + LocalStorage

A responsive and minimal **Todo List App** built with **React.js** and **Vite**, featuring local data persistence via **LocalStorage**. Users can add, edit, delete, and mark tasks as complete — all stored locally without backend dependencies.

---

## 🧩 Features

- ✍️ Add new todos with a clean input form
- 📝 Edit tasks inline (disabled for completed tasks)
- ✅ Toggle completion status with visual feedback
- ❌ Delete tasks instantly
- 💾 Persistent storage using browser's LocalStorage
- 🎨 Dynamic styling for completed vs pending tasks
- ⚡ Built with Vite for fast development and optimized builds

---

## 🛠️ Tech Stack

| Technology     | Purpose                          |
|----------------|----------------------------------|
| React.js       | UI and component logic           |
| Vite           | Fast bundling and dev server     |
| CSS / Tailwind | Styling and layout               |
| LocalStorage   | Persistent client-side storage   |
| Context API    | Global state management          |

---

## 📁 Project Structure

```
src/
├── Components/
│   ├── ToDoForm.jsx       # Input form for new todos
│   └── ToDoItem.jsx       # Individual todo item with edit/delete
├── context/
│   └── ToDoContext.jsx    # Context provider and hooks
├── App.jsx                # Main app logic and layout
├── App.css                # Custom styles
├── assets/                # Logos and static assets
└── main.jsx               # Entry point
```

---

## Installation

```
git clone https://github.com/your-username/react-todo-local.git
cd react-todo-local
npm run dev
```

---

## 🧠 How It Works
- **State Management:** Todos are managed via *useState* and shared using *Context API*.
- **Persistence:** On every update, todos are synced to *localStorage*. On load, they’re retrieved via *useEffect*.
- **Unique IDs:** Each todo is assigned a *timestamp-based id* using Date.now().

---

## 📸 UI Highlights
<img width="1517" height="810" alt="image" src="https://github.com/user-attachments/assets/c6786a0c-a014-4e8f-b481-1e22335ecb5b" />


