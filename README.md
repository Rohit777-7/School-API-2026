# School-API-2026
# School Management API

## 📌 Overview
This project is a Node.js + Express API with MySQL database to manage school data.  
It allows users to add schools and retrieve a list of schools sorted by proximity.

---

## 🚀 Features
- Add School API
- List Schools API (sorted by distance)
- Input validation
- MySQL database integration

---

## 🛠️ Tech Stack
- Node.js
- Express.js
- MySQL
- Postman (for testing)

---

## 📂 API Endpoints

### ➤ Add School
- Method: POST
- URL: /api/addSchool

Body:
```json
{
  "name": "ABC School",
  "address": "Nagpur",
  "latitude": 21.1458,
  "longitude": 79.0882
}