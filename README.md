# ExpenseTracker-Api

This is an Express.js API for managing expenses. It allows you to perform CRUD (Create, Read, Update, Delete) operations on expenses stored in a MongoDB database.

---

## Features & Paths
1. **Add a new expense** - `POST /api/expenses`
2. **Fetch all expenses** - `GET /api/expenses`
3. **Update an existing expense by ID** - `PUT /api/expenses/:id`
4. **Delete an expense by ID** - `DELETE /api/expenses/:id`

---

## Endpoints

### 1. **POST /api/expenses**
- Adds a new expense to the database. Requires `date`, `value`, and `label` fields in the request body.

### 2. **GET /api/expenses**
- Retrieves all expenses, sorted by creation date in descending order.

### 3. **PUT /api/expenses/:id**
- Updates an existing expense by its unique ID. 

### 4. **DELETE /api/expenses/:id**
- Deletes an expense by its unique ID.

---
