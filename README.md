# 💰 Expense Tracker REST API

A beginner-friendly Full Stack Expense Tracker application built using **Node.js**, **Express.js**, **SQLite (better-sqlite3)**, and **React + Vite**.

The application allows users to add, view, update, and delete daily expenses. It also provides monthly expense summaries, category-wise spending analysis, pagination, and filtering.

---

# 🚀 Features

## Backend (Express + SQLite)

- REST API using Express.js
- SQLite database using better-sqlite3
- Automatic database and table creation
- CORS enabled
- JSON request parsing
- CRUD operations
- Pagination
- Category filtering
- Monthly expense summary
- Category-wise total calculation
- Error handling

---

## Frontend (React + Vite)

- Add Expense Form
- Category Dropdown
- Date Picker
- Monthly Summary
- Expense List
- Pagination
- Category Filter
- Delete Expense
- Loading Indicators
- Responsive UI
- Beginner Friendly Code

---

# 📂 Project Structure

```
Project Folder
│
├── backend
│   ├── index.js
│   ├── data.db
│   └── package.json
│
├── frontend
│   └── src
│       ├── App.jsx
│       ├── App.css
│       ├── main.jsx
│       └── index.css
│
└── README.md
```

---

# 🛠 Technologies Used

### Backend

- Node.js
- Express.js
- better-sqlite3
- SQLite

### Frontend

- React
- Vite
- CSS

---

# 📦 Database

Database Name

```
data.db
```

Table Name

```
expenses
```

Columns

| Column | Type |
|---------|------|
| id | INTEGER |
| title | TEXT |
| amount | REAL |
| category | TEXT |
| date | TEXT |
| created_at | TEXT |

---

# 🔗 REST API Endpoints

## Add Expense

```
POST /expenses
```

Adds a new expense.

---

## Get Expenses

```
GET /expenses
```

Supports

- Pagination
- Category Filter
- Month Filter

Example

```
GET /expenses?page=1&limit=10
```

---

## Monthly Summary

```
GET /expenses/summary
```

Example

```
GET /expenses/summary?month=2026-07
```

---

## Update Expense

```
PUT /expenses/:id
```

Updates an existing expense.

---

## Delete Expense

```
DELETE /expenses/:id
```

Deletes an expense.

---

# ▶️ Running the Backend

Move to backend folder

```bash
cd backend
```

Start server

```bash
node index.js
```

Server runs at

```
http://localhost:5000
```

---

# ▶️ Running the Frontend

Move to frontend folder

```bash
cd frontend
```

Start Vite

```bash
npm run dev
```

Open browser

```
http://localhost:5173
```

---

# 📷 Application Features

✔ Add Expense

✔ View Expenses

✔ Edit Expense

✔ Delete Expense

✔ Monthly Summary

✔ Category-wise Spending

✔ Pagination

✔ Category Filter

✔ Responsive Design

---

# 🧪 Testing API

The API can be tested using

- Postman
- Thunder Client
- Insomnia

---

# 📖 Learning Outcomes

This project demonstrates:

- Express Routing
- REST API Development
- CRUD Operations
- SQLite Database
- React Hooks
- API Integration
- Pagination
- Filtering
- State Management
- Responsive CSS

---

# 👩‍💻 Author

Developed as a Full Stack CRUD REST API Project using

- Express.js
- SQLite
- React
- Vite

---

# 📄 License

This project is created for educational and learning purposes.
