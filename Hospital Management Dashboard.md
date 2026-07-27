# React Developer Intern Technical Assignment

# Hospital Management Dashboard

---

## 📖 Overview

The objective of this assignment is to build a responsive **Hospital Management Dashboard** using **React**.

The application should provide a dashboard to manage doctors, patients, and appointments through an intuitive and modern user interface.

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

Create a dashboard that displays the following summary cards:

- Total Doctors
- Total Patients
- Today's Appointments
- Available Doctors

Display a section showing **Recent Appointments**.

---

## 2. Doctor Management

Create a page to display all doctors.

Each doctor should contain the following information:

| Field |
|--------|
| Name |
| Specialization |
| Experience |
| Contact Number |

The page should provide the following actions:

- Add Doctor
- Edit Doctor
- Delete Doctor

---

## 3. Patient Management

Create a page to display all patients.

Each patient should contain:

| Field |
|--------|
| Name |
| Age |
| Gender |
| Contact Number |

The page should provide the following actions:

- Add Patient
- Edit Patient
- Delete Patient

---

## 4. Appointment Management

Create a page to display all appointments.

Each appointment should contain:

| Field |
|--------|
| Patient Name |
| Doctor Name |
| Appointment Date |
| Appointment Time |
| Status |

The page should provide the following actions:

- Book Appointment
- Update Appointment
- Cancel Appointment

---

## 5. Search

Provide search functionality for:

### Doctors

- Name
- Specialization

### Patients

- Name

### Appointments

- Patient Name
- Doctor Name

---

## 6. Filter

Provide filtering options for:

### Doctors

- Specialization

### Patients

- Gender

### Appointments

- Status
- Date

---

## 7. Doctor Details

Create a page to display complete information about a selected doctor.

Display:

- Name
- Specialization
- Experience
- Contact Number
- Available Schedule

---

## 8. Patient Details

Create a page to display complete information about a selected patient.

Display:

- Name
- Age
- Gender
- Contact Number
- Appointment History

---

# Pages

The application should contain the following pages:

- Login (UI only)
- Dashboard
- Doctors
- Doctor Details
- Patients
- Patient Details
- Appointments
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
/dashboard
```

```
/doctors
```

```
/doctors/:id
```

```
/patients
```

```
/patients/:id
```

```
/appointments
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
- Filter Options
- Modal or Form for Add/Edit Operations
- Modern and Clean User Interface

---

# Sample Data

You may use mock data or fetch data from any free public API.

### Doctor

```json
{
  "id": 1,
  "name": "Dr. John Smith",
  "specialization": "Cardiology",
  "experience": 10,
  "contactNumber": "9876543210"
}
```

### Patient

```json
{
  "id": 1,
  "name": "Alice Johnson",
  "age": 30,
  "gender": "Female",
  "contactNumber": "9876543211"
}
```

### Appointment

```json
{
  "id": 1,
  "patientName": "Alice Johnson",
  "doctorName": "Dr. John Smith",
  "appointmentDate": "2026-08-15",
  "appointmentTime": "10:30 AM",
  "status": "Confirmed"
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

During the follow-up discussion, you may be asked to explain your implementation, routing, component structure, state management, and design decisions.

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
