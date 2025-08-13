# 🗂 Simple Kanban Board

A simple and interactive *Kanban Board* built using *HTML, CSS, and JavaScript, implementing the **HTML Drag and Drop API*.  
This project allows users to drag and drop tasks between columns like *To Do, **In Progress, and **Done*.

---

## 🚀 Features
- *Three columns*: To Do, In Progress, Done
- *Drag and Drop functionality* using the native HTML Drag and Drop API
- *Responsive design* for better usability
- Lightweight — no external libraries

---

## 🛠 Technologies Used
- *HTML5* – Structure and Drag/Drop API attributes
- *CSS3* – Styling and layout
- *JavaScript (Vanilla)* – DOM manipulation and drag/drop logic

---

## 📂 Project Structure

📦 Simple-Kanban-Board ├── index.html       # Main HTML file ├── style.css        # Styling └── script.js        # Drag and Drop functionality

---

## 📌 How It Works
1. *Drag an item* from one column.
2. *Drop it* into another column.
3. The HTML Drag and Drop API handles:
   - dragstart → Store dragged item data
   - dragover → Allow drop by preventing default behavior
   - drop → Append item to the target column

---

## 💡 Learning Outcomes
- Understanding the *HTML Drag and Drop API*
- Handling *JavaScript Events*
- Creating a simple *task management UI*
- Practicing *CSS flexbox/grid* layouts

---

## 🔮 Future Improvements
- Save tasks in *localStorage* so they persist after refresh
- Add a *task creation form*
- Add *delete/edit task* options
- Add animations for smoother drag/drop

