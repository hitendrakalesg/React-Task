# React Developer Intern Technical Assignment

# Product Inventory Dashboard

---

## 📖 Overview

The objective of this assignment is to build a responsive **Product Inventory Dashboard** using **React**.

The application should allow users to manage products through a clean and user-friendly interface.

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

Create a dashboard displaying inventory statistics.

Display summary cards such as:

- Total Products
- Total Categories
- Low Stock Products
- Out of Stock Products

---

## 2. Product Management

Create a page to display all products.

Each product should contain the following information:

| Field |
|--------|
| Product Name |
| Category |
| Price |
| Stock Quantity |
| Status (In Stock / Low Stock / Out of Stock) |

The page should provide the following actions:

- Add Product
- Edit Product
- Delete Product

---

## 3. Search Products

Provide a search feature to search products by:

- Product Name
- Category

---

## 4. Filter Products

Allow filtering products by category.

Example:

```
All
Electronics
Clothing
Books
Furniture
Groceries
```

---

## 5. Product Details

Create a page to display complete information about a selected product.

The page should display:

- Product Name
- Category
- Description
- Price
- Available Quantity
- Product Image

---

## 6. Low Stock Products

Create a section to display products with low stock.

Example:

```
Stock Quantity < 10
```

---

## 7. Navigation

The application should include the following pages:

- Dashboard
- Products
- Product Details
- Not Found (404)

---

# Routing

Use React Router for navigation.

Suggested routes:

```
/
```

```
/dashboard
```

```
/products
```

```
/products/:id
```

---

# UI Requirements

The application should have:

- Responsive Layout
- Sidebar Navigation
- Top Navigation Bar
- Dashboard Cards
- Product Table or Grid
- Search Bar
- Filter Dropdown
- Modern and Clean User Interface

---

# Sample Product Data

You may use mock data or fetch data from a public API.

Example:

```json
[
  {
    "id": 1,
    "name": "Laptop",
    "category": "Electronics",
    "price": 75000,
    "stock": 12,
    "description": "15.6-inch Full HD Laptop",
    "image": "https://example.com/laptop.jpg"
  },
  {
    "id": 2,
    "name": "Office Chair",
    "category": "Furniture",
    "price": 8500,
    "stock": 5,
    "description": "Ergonomic office chair",
    "image": "https://example.com/chair.jpg"
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
- Keep the code clean and readable.
- Ensure the application runs successfully.
- You may use any UI library or CSS framework of your choice.
- You may use mock data or any free public API.

---

# Good Luck!

We are evaluating your ability to build a modern React application with reusable components, routing, state management, responsive UI, and clean, maintainable code.
