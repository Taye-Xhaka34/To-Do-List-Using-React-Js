# To Do List App

A beautiful, responsive React To-Do List application.  
Easily add, delete, and reorder your daily tasks!
---
## 📁 Folder Structure
```
To Do List App/
├── my-to-do-list/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── ToDoList.jsx
│   │   ├── index.css
│   │   ├── main.jsx
│   ├── package.json
│   ├── ...other config files
```
---
## 🚀 Getting Started
### 1. **Install Node.js**
Download and install [Node.js](https://nodejs.org/) if you haven't already.
### 2. **Install Dependencies**
Open your terminal in the `my-to-do-list` folder and run:
```
npm install
```
### 3. **Run the App**
Start the development server:
```
npm run dev
```
Theapp will open in your browser (usually at `http://localhost:5173` or similar).
---
## 📝 Features

- **Add Tasks:** Type a task and click "Add".
- **Delete Tasks:** Remove tasks with the "Delete" button.
- **Reorder Tasks:** Move tasks up or down.
- **Responsive Design:** Works great on mobile and desktop.
- **Modern UI:** Beautiful gradients, smooth hover effects, and card layout.

---

## 📄 File Overview

- **App.jsx**  
  Main React component, renders the ToDoList.

- **ToDoList.jsx**  
  Contains all logic for managing tasks (add, delete, move).

- **index.css**  
  Styles for the app, including responsiveness and modern look.

- **main.jsx**  
  Entry point, renders the app to the DOM.

---

## 🛠️ Customization

- Change initial tasks in `ToDoList.jsx` (`useState` array).
- Edit styles in `index.css` for your own theme.

---

## 💡 Tips

- Use the app on any device—it's fully responsive!
- You can extend functionality (edit tasks, persist to localStorage, etc.).
