# React Developer Intern Technical Assignment

# Employee Management Dashboard

---

## 📖 Overview

The objective of this assignment is to build a responsive **Employee Management Dashboard** using **React**.

The application should allow users to manage employees through a clean and user-friendly interface.

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

## 1. Login Page

Create a login page.

Use the following dummy credentials:

### Admin

```
Email: admin@test.com
Password: admin123
```

---

### Employee

```
Email: employee@test.com
Password: employee123
```

After successful login:

- Admin should be redirected to the Admin Dashboard.
- Employee should be redirected to the Employee Dashboard.

---

## 2. Dashboard

Create separate dashboards for:

- Admin
- Employee

### Admin Dashboard

Display summary cards such as:

- Total Employees
- Active Employees
- Departments

---

### Employee Dashboard

Display:

- Welcome message
- Employee profile information

---

## 3. Employee Management

Create a page to display all employees.

Each employee should contain:

| Field |
|--------|
| Name |
| Email |
| Department |
| Designation |

The page should provide the following actions:

- Add Employee
- Edit Employee
- Delete Employee

---

## 4. Search Employees

Provide a search feature to search employees by:

- Name
- Email

---

## 5. Filter Employees

Allow filtering employees by department.

Example:

```
All
Development
HR
Sales
Marketing
```

---

## 6. Employee Details

Create a page to display complete information of a selected employee.

---

## 7. Logout

Provide a logout option.

After logout:

- User should be redirected to the Login page.

---

# Pages

The application should contain the following pages:

- Login
- Admin Dashboard
- Employee Dashboard
- Employee List
- Employee Details
- Not Found (404)

---

# Navigation

Use React Router for navigation.

Suggested routes:

```
/
```

```
/login
```

```
/admin/dashboard
```

```
/employee/dashboard
```

```
/employees
```

```
/employees/:id
```

---

# UI Requirements

The application should have:

- Responsive Layout
- Sidebar Navigation
- Top Navigation Bar
- Dashboard Cards
- Employee Table
- Modern and Clean User Interface

---

# Sample Employee Data

You may use mock data or fetch data from a public API.

Example:

```json
[
  {
    "id": 1,
    "name": "John Doe",
    "email": "john@example.com",
    "department": "Development",
    "designation": "Software Engineer"
  },
  {
    "id": 2,
    "name": "Jane Smith",
    "email": "jane@example.com",
    "department": "HR",
    "designation": "HR Executive"
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

During the follow-up discussion, you may be asked to explain your implementation, folder structure, routing, and design decisions.

---

# Important Notes

- Build a clean and responsive user interface.
- Organize the project with a proper folder structure.
- Use reusable React components wherever appropriate.
- Keep the code clean and readable.
- Ensure the application runs successfully.
- You may use any UI library or CSS framework of your choice.

---

# Good Luck!

We are evaluating your ability to build a modern React application with clean UI, reusable components, routing, state management, and maintainable code.
