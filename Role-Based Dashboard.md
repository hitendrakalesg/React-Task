# React Developer Intern Technical Assignment

# Role-Based Dashboard

---

## 📖 Overview

The objective of this assignment is to build a responsive **Role-Based Dashboard** using **React**.

The application should simulate a simple authentication system with different dashboards for different user roles. Users should only be able to access pages that belong to their assigned role.

---

## ⏱ Time Limit

**60 Minutes**

---

## 🛠 Technology Stack

Use the following technologies:

- React.js
- React Router
- JavaScript (ES6+)
- HTML5
- CSS3 / Tailwind CSS / Bootstrap / Material UI (Any one)
- Context API or any state management approach of your choice

---

# Functional Requirements

## 1. Login Page

Create a login page.

Use the following dummy credentials:

### Admin

```
Email: admin@test.com
Password: admin123
Role: ADMIN
```

---

### Manager

```
Email: manager@test.com
Password: manager123
Role: MANAGER
```

---

### Employee

```
Email: employee@test.com
Password: employee123
Role: EMPLOYEE
```

---

After successful login:

- Store the logged-in user information.
- Redirect the user to the appropriate dashboard based on their role.

---

# 2. Admin Dashboard

The Admin should have access to:

- Dashboard
- Employee Management
- Department Management
- Reports
- Profile
- Logout

### Dashboard Cards

Display summary cards such as:

- Total Employees
- Total Departments
- Total Managers
- Active Employees

---

# 3. Manager Dashboard

The Manager should have access to:

- Dashboard
- Team Members
- Assigned Tasks
- Profile
- Logout

### Dashboard Cards

Display summary cards such as:

- Team Members
- Pending Tasks
- Completed Tasks

---

# 4. Employee Dashboard

The Employee should have access to:

- Dashboard
- My Profile
- My Tasks
- Logout

### Dashboard Cards

Display:

- Assigned Tasks
- Completed Tasks
- Pending Tasks

---

# 5. Navigation

Implement navigation using **React Router**.

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
/manager/dashboard
```

```
/employee/dashboard
```

```
/profile
```

---

# 6. Protected Routes

Only authenticated users should be able to access dashboard pages.

Users should not be able to access dashboards that belong to another role.

Examples:

- Employee should not access Admin Dashboard.
- Manager should not access Employee Dashboard.
- Admin should not access Manager Dashboard unless permitted by your implementation.

Unauthorized access should redirect the user to an appropriate page.

---

# 7. Profile Page

Create a profile page displaying:

- Name
- Email
- Role

---

# 8. Logout

Provide a logout option.

After logout:

- Clear the stored login information.
- Redirect the user to the Login page.

---

# UI Requirements

The application should have:

- Responsive Layout
- Sidebar Navigation
- Top Navigation Bar
- Dashboard Cards
- User Profile Card
- Modern and Clean User Interface

---

# Suggested Folder Structure

```
src/
│── components/
│── pages/
│── layouts/
│── routes/
│── services/
│── context/
│── assets/
│── App.jsx
│── main.jsx
```

---

# Sample User Data

You may use the following dummy data:

```json
[
  {
    "id": 1,
    "name": "Admin User",
    "email": "admin@test.com",
    "password": "admin123",
    "role": "ADMIN"
  },
  {
    "id": 2,
    "name": "Manager User",
    "email": "manager@test.com",
    "password": "manager123",
    "role": "MANAGER"
  },
  {
    "id": 3,
    "name": "Employee User",
    "email": "employee@test.com",
    "password": "employee123",
    "role": "EMPLOYEE"
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

During the follow-up discussion, you may be asked to explain your implementation, routing, state management, authentication flow, and design decisions.

---

# Important Notes

- Build a clean and responsive user interface.
- Organize the project with a proper folder structure.
- Use reusable React components wherever appropriate.
- Use React Router for navigation.
- Keep the code clean and readable.
- Ensure the application runs successfully.
- You may use any UI library or CSS framework of your choice.
- No backend is required. Authentication can be implemented using the provided dummy user data.

---

# Good Luck!

We are evaluating your ability to build a modern React application with routing, role-based navigation, protected routes, state management, reusable components, and clean, maintainable code.
