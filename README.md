# ✅ Task Manager — IndexedDB

A fully client-side Task Manager built with pure HTML, CSS, and JavaScript — no frameworks, no backend, no dependencies. Tasks are stored in the browser using **IndexedDB**, so your data survives page refreshes.

---

## ✨ Features

- 💾 **Persistent Storage** — Uses IndexedDB to keep tasks after refresh
- ➕ **Add / Delete / Toggle** — Full CRUD operations
- 🔍 **Live Search** — Filter tasks by title or description instantly
- 🗂️ **Status Filters** — View All, Pending, or Done tasks
- ⚡ **Optimistic UI** — Instant updates with automatic revert if DB fails
- 🌱 **Seed Demo Tasks** — One click to populate sample data
- ⌨️ **Keyboard Shortcut** — `Ctrl + Enter` to add a task quickly
- 🟡🟢 **Color-coded Cards** — Pending = Yellow, Done = Green
- 📢 **Toast Notifications** — Non-intrusive success/error feedback
- 📱 **Responsive** — Works on mobile and desktop

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Adnan-Ghiyath/Certificate-generator.git
   ```
2. Open `Task_Manager.html` directly in your browser — no server needed
3. Add tasks using the form on the left
4. Mark tasks as Done ✅ or delete them 🗑️
5. Use filters and search to find tasks quickly

---

## 🗄️ How Data is Stored

This app uses the browser's built-in **IndexedDB** — a structured local database:

| Property | Value |
|----------|-------|
| Database Name | `TaskDB` |
| Version | `1` |
| Store Name | `tasks` |
| Key | `id` (auto-increment) |
| Indexes | `status`, `createdAt` |

Data is stored **only on your device** — nothing is sent to any server.

---

## 📁 Project Structure

```
Task_Manager.html    # Everything in one file (HTML + CSS + JS)
```

---

## 🛠️ Built With

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

- Pure Vanilla JavaScript
- IndexedDB (browser-native database)
- Zero dependencies — no npm, no frameworks

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + Enter` | Add task quickly |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Made with ❤️ by [Adnan-Ghiyath](https://github.com/Adnan-Ghiyath)
