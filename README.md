# 📝 Taskie - Student Task Management System

**Taskie** is a modern, clean, and intuitive task management web application designed specifically for university students. It helps users organize assignments and track project progress.

---

## ✨ Features

-   **Interactive Dashboard:** Visualize your productivity with a dynamic doughnut chart showing Upcoming, In Progress, and Completed tasks.
-   **Task Management:** Add, delete, and mark tasks as complete. Data is saved locally so your progress isn't lost when you refresh.
-   **Project Overview:** Categorize your tasks into academic projects (like IMS566 or IMS560) with visual progress bars.
-   **Responsive Design:** Fully accessible on both Desktop and Mobile devices.

---

## 🔐 Access & Security
To access the dashboard, users must first log in. 
- **New Users:** You must click on "Create Account" to register your credentials.
- **Data Privacy:** Taskie uses `localStorage`, meaning your account and task data are stored safely on your own computer and are not sent to any external servers.

---

## 🛠️ Tech Stack

-   **Frontend:** HTML5, CSS3 (Custom Gradients & Glassmorphism)
-   **Framework:** Bootstrap 5 (Responsive Layouts)
-   **Icons:** FontAwesome 6
-   **Fonts:** Plus Jakarta Sans
-   **Charts:** Chart.js
-   **Storage:** Browser LocalStorage API (No database required for local use)

---

## 📂 Project Structure

```text
/Taskie
│
├── dashboard.html   # Main overview with task statistics (Chart.js)
├── tasks.html       # Management page to add/edit/delete tasks
├── projects.html    # Categorized project progress tracking
├── register.html    # Register page for new user
└── index.html       # (Optional) Login or Landing page
