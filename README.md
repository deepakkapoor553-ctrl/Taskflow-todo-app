# 📋 TaskFlow – Modern To-Do App

A beautiful, feature-rich task manager with glass-morphism UI, priorities, deadlines, reminders, time tracking, and dark/light themes — all in a single HTML file.

![Screenshot](screenshot.png)

## ✨ Features

- ✅ **Add / Edit / Delete** tasks easily
- 🎯 **Priority Levels** – High, Medium, Low
- ⏰ **Deadlines & Reminders** – Get notifications before tasks are due
- ⏱️ **Built-in Time Tracker** – Track time spent on each task (start/stop)
- 🔍 **Search & Filter** – All / Active / Completed / Schedule view
- 📊 **Progress Bar** – Visual completion percentage
- 🌙 **Dark / Light Theme** – Toggle with one click
- 💾 **Auto-save** – All data stored in your browser (localStorage)
- 🔔 **Browser Notifications** – Reminders work even when tab is in background
- 📱 **Fully Responsive** – Works on mobile, tablet, desktop

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| CSS3 | Glass-morphism UI + Dark/Light themes |
| Vanilla JS | Logic, timer, filters, CRUD |
| localStorage | Data persistence (no server needed) |
| Font Awesome | Icons |
| Google Fonts (Inter) | Modern typography |

## 🚀 How to Run

1. Download or clone this repository
2. Open `index.html` in your browser
3. Start managing your tasks!

No build tools, no npm install, no server required.

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Enter` | Add task (from title field) |
| `Esc` | Close modal / confirm dialog |

## 📦 Data Storage

All tasks and settings are saved in `localStorage` under these keys:
- `taskflow_v2_tasks` – All your tasks
- `taskflow_v2_settings` – Theme and sort preferences
- `taskflow_v2_notified` – Tracking which reminders have fired

## 📁 Project Structure
taskflow-todo-app/
├── index.html (Everything in one file!)
├── README.md (This file)
└── .gitignore (Git ignore rules)


## 🤝 Contributing

Feel free to fork this repository and submit pull requests. Suggestions and improvements are welcome!

## 📄 License

MIT License — Free to use, modify, and distribute.

---

**Made with ❤️ for better productivity.**

*Om Shanti* 🕉️
