To-Do List Web App

A simple and responsive To-Do List Web Application built using HTML, CSS, and JavaScript.
This project allows users to manage daily tasks efficiently with features like adding, completing, deleting, and storing tasks using localStorage.

---

📌 Project Objective

The objective of this project is to build a task management application where users can:

Add new tasks
Mark tasks as completed
Delete tasks
Store tasks permanently using localStorage

The application is fully responsive and works smoothly on desktop and mobile devices.

🚀 Features
✅ Add Tasks

Users can add new tasks using the input field and the Add Task button.

✅ Mark Tasks as Completed

Clicking on a task marks it as completed with:

Strikethrough text
Gray color effect

Clicking again removes the completed status.

✅ Delete Tasks

Each task includes a delete button to remove the task instantly.

✅ localStorage Support

Tasks are saved in the browser using localStorage, so they remain available even after refreshing or reopening the browser.

✅ Responsive Design

The layout automatically adjusts for:

Desktop screens
Tablets
Mobile devices

---

🛠️ Technologies Used
HTML5
CSS3
JavaScript (ES6)
localStorage API

---

📂 Project Structure
todo-list-app/
│
├── index.html
├── README.md

---

⚙️ Methodology

1. Structure Creation (HTML)

HTML was used to create:

Input field
Add Task button
Task list container

Main sections:

Header
Task Input Area
Task List 2. Styling (CSS)

CSS was used for:

Clean layout
Proper spacing
Responsive design
Button styling
Completed task effects

Media queries were added for mobile responsiveness.

3. Functionality (JavaScript)
   Add Task
   Reads input value
   Creates a task object
   Pushes task into array
   Saves task to localStorage
   Mark as Completed
   Toggles completed state
   Adds/removes CSS class
   Delete Task
   Removes selected task from array
   Save to localStorage

Tasks are stored using:

localStorage.setItem("tasks", JSON.stringify(tasks));
Load Tasks

Tasks are retrieved when the page loads using:

JSON.parse(localStorage.getItem("tasks"))

---

💻 How to Run the Project
Download or clone the repository
git clone <repository-link>
Open the project folder
Run the index.html file in any browser

---

📱 Responsive Design

The application is responsive for:

Mobile phones
Tablets
Laptops
Desktop screens

---

📸 Output

The application provides:

Task creation
Task completion tracking
Task deletion
Persistent storage after refresh

---

👨‍💻 Author

Developed by Yogesh Kolte
