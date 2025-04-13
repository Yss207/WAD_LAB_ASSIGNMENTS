# 🧑‍💼 Employee Management CRUD API

This project is a simple **CRUD (Create, Read, Update, Delete)** API built with **Node.js**, **Express.js**, and **MongoDB**. It manages employee records with fields like `name`, `department`, and `salary`.

This project was created as **Assignment 3(b)** for the Web Application Development subject for TE-IT SPPU Syllabus.

---

## 🚀 Features

- Add a new employee 👨‍💼
- Get all employees or filter by department 🔍
- Update employee details ✏️
- Delete an employee by ID 🗑️
- Delete employees with salary less than a specified amount 💸

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas (via Mongoose ODM)
- **Testing Tool**: Postman (for API requests)

---
## 📡 API Endpoints

| Method | Endpoint                         | Description                                         |
|--------|----------------------------------|-----------------------------------------------------|
| POST   | `/add-employee`                  | Add a new employee                                  |
| GET    | `/employees`                     | Get all employees                                   |
| GET    | `/employees/department/:dept`    | Get employees by department                         |
| PUT    | `/update-employee/:id`           | Update an employee by ID                            |
| DELETE | `/delete-employee/:id`           | Delete an employee by ID                            |
| DELETE | `/delete-on-salary/:amount`      | Delete employees with salary less than a given value|

---
