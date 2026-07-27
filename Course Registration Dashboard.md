# React Developer Intern Technical Assignment

# Course Registration Dashboard

---

## 📖 Overview

The objective of this assignment is to build a responsive **Course Registration Dashboard** using **React**.

The application should allow users to manage students, courses, and course enrollments through a clean and modern user interface.

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
- Axios or Fetch API

---

# Functional Requirements

## 1. Dashboard

Create a dashboard displaying the following summary cards:

- Total Students
- Total Courses
- Total Enrollments
- Active Courses

Display a section showing **Recent Enrollments**.

---

## 2. Student Management

Create a page to display all students.

Each student should contain the following information:

| Field |
|--------|
| Name |
| Email |
| Department |
| Year |

The page should provide the following actions:

- Add Student
- Edit Student
- Delete Student

---

## 3. Course Management

Create a page to display all courses.

Each course should contain:

| Field |
|--------|
| Course Name |
| Course Code |
| Instructor |
| Credits |

The page should provide the following actions:

- Add Course
- Edit Course
- Delete Course

---

## 4. Course Enrollment

Create a page to manage course enrollments.

Each enrollment should contain:

| Field |
|--------|
| Student Name |
| Course Name |
| Enrollment Date |

The page should provide the following actions:

- Enroll Student
- Remove Enrollment

---

## 5. Search

Provide search functionality for:

### Students

- Name
- Email

### Courses

- Course Name
- Course Code

---

## 6. Filter

Provide filtering options for:

### Students

- Department

### Courses

- Instructor

---

## 7. Student Details

Create a page displaying complete information about a selected student.

Display:

- Name
- Email
- Department
- Year
- Enrolled Courses

---

## 8. Course Details

Create a page displaying complete information about a selected course.

Display:

- Course Name
- Course Code
- Instructor
- Credits
- Enrolled Students

---

# Pages

The application should contain the following pages:

- Login (UI only)
- Dashboard
- Students
- Student Details
- Courses
- Course Details
- Enrollments
- Not Found (404)

---

# Navigation

Use **React Router** for navigation.

Suggested routes:

```
/
```

```
/login
```

```
/dashboard
```

```
/students
```

```
/students/:id
```

```
/courses
```

```
/courses/:id
```

```
/enrollments
```

---

# UI Requirements

The application should include:

- Responsive Layout
- Sidebar Navigation
- Top Navigation Bar
- Dashboard Summary Cards
- Data Tables
- Search Bar
- Filter Dropdowns
- Modal or Form for Add/Edit Operations
- Modern and Clean User Interface

---

# Sample Data

You may use mock data or fetch data from any free public API.

### Student

```json
{
  "id": 1,
  "name": "John Doe",
  "email": "john@example.com",
  "department": "Computer Science",
  "year": "Third Year"
}
```

### Course

```json
{
  "id": 101,
  "courseName": "Data Structures",
  "courseCode": "CS301",
  "instructor": "Dr. Smith",
  "credits": 4
}
```

### Enrollment

```json
{
  "id": 1,
  "studentName": "John Doe",
  "courseName": "Data Structures",
  "enrollmentDate": "2026-08-15"
}
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
