# React Developer Intern Technical Assignment

# Task Management Dashboard

---

## 📖 Overview

The objective of this assignment is to build a responsive **Task Management Dashboard** using **React**.

The application should allow users to manage tasks through a modern and user-friendly interface. Users should be able to create, update, delete, search, and filter tasks.

---

## ⏱ Time Limit

**90 Minutes**

---

## 🛠 Technology Stack

Use the following technologies:

- React.js
- React Router
- JavaScript (ES6+)
- HTML5
- CSS3 / Tailwind CSS / Bootstrap / Material UI (Any one)
- Axios or Fetch API

---

# Functional Requirements

## 1. Dashboard

Create a dashboard displaying task statistics.

Display summary cards such as:

- Total Tasks
- Pending Tasks
- In Progress Tasks
- Completed Tasks

Display a section showing **Recent Tasks**.

---

## 2. Task Management

Create a page to display all tasks.

Each task should contain the following information:

| Field |
|--------|
| Title |
| Description |
| Priority |
| Status |
| Due Date |

The page should provide the following actions:

- Add Task
- Edit Task
- Delete Task

---

## 3. Search Tasks

Provide a search feature to search tasks by:

- Title
- Description

---

## 4. Filter Tasks

Allow filtering tasks by:

### Status

```
All
Pending
In Progress
Completed
```

### Priority

```
All
High
Medium
Low
```

---

## 5. Task Details

Create a page to display complete information about a selected task.

Display:

- Title
- Description
- Priority
- Status
- Due Date
- Created Date

---

## 6. Update Task Status

Allow users to update the status of a task.

Example:

```
Pending
↓

In Progress
↓

Completed
```

---

## 7. Pages

The application should contain the following pages:

- Dashboard
- Task List
- Task Details
- Not Found (404)

---

# Navigation

Use React Router for navigation.

Suggested routes:

```
/
```

```
/dashboard
```

```
/tasks
```

```
/tasks/:id
```

---

# UI Requirements

The application should include:

- Responsive Layout
- Sidebar Navigation
- Top Navigation Bar
- Dashboard Cards
- Task Table or Card View
- Search Bar
- Filter Dropdowns
- Modal or Form for Add/Edit Operations
- Modern and Clean User Interface

---

# Sample Task Data

You may use mock data or fetch data from any free public API.

Example:

```json
[
  {
    "id": 1,
    "title": "Design Login Page",
    "description": "Create a responsive login page for the application.",
    "priority": "High",
    "status": "Pending",
    "dueDate": "2026-08-15"
  },
  {
    "id": 2,
    "title": "Implement Dashboard",
    "description": "Develop the dashboard with summary cards.",
    "priority": "Medium",
    "status": "In Progress",
    "dueDate": "2026-08-18"
  }
]
```

---

# Submission Instructions

Upload your project to a **GitHub repository**.

The repository should contain:

- Complete source code
- README.md
- package.json

---

# Bonus

You are free to implement any additional features that improve the application.

---

# AI Usage

You are allowed to use AI tools such as:

- ChatGPT
- Claude
- GitHub Copilot
- Gemini
- Official Documentation

During the follow-up discussion, you may be asked to explain your implementation, component structure, routing, state management, and design decisions.

---

# Important Notes

- Build a clean and responsive user interface.
- Organize the project with a proper folder structure.
- Use reusable React components wherever appropriate.
- Use React Router for navigation.
- Keep the code clean and readable.
- Ensure the application runs successfully.
- You may use any UI library or CSS framework of your choice.
- You may use mock data or any free public API.

---

# Good Luck!

We are evaluating your ability to build a modern React application with reusable components, routing, state management, responsive design, and clean, maintainable code.
