# 🏦 Simple Banking Application

## 📌 Objective

This project is a **simple banking web application** built using Flask and SQLite. It allows users to:
- Create a bank account
- Check account balance
- Deposit and withdraw funds
- View bank statement (feature placeholder)

The goal is to demonstrate a minimal full-stack application for learning or prototyping.

---

## 🧰 Tech Stacks

- **Backend:** Python with Flask (lightweight WSGI web framework)
- **Frontend:** HTML (with embedded Flask template rendering)
- **Database:** SQLite (serverless and easy to use for small-scale apps)
- **Containerization:** Docker (via included `Dockerfile`)
- **Other Tools:** Jinja2 for templating, HTTP methods for routing

---

## 🪜 Steps Included

### 1. **Database Initialization**
- Automatically creates a SQLite database (`bank.db`) with an `accounts` table.

### 2. **Account Creation**
- Input name and initial balance through a form.
- Data is saved to the database.

### 3. **Balance Check**
- Submit account ID to retrieve and display the current balance.

### 4. **Deposit**
- Input account ID and deposit amount to add funds.

### 5. **Withdraw**
- Withdraw amount after checking if sufficient balance is available.

### 6. **Statement**
- Placeholder for future enhancement to show transaction history.

### 7. **Run the App**
- The app runs on `http://0.0.0.0:5005`.

---

## 💡 Key Insights

- Demonstrates **CRUD operations** using Python and SQLite.
- Shows how to **integrate HTML with Flask** using `render_template_string`.
- UI includes a simple **navigation menu** for user flow.
- **Error handling** implemented for balance check and withdrawal.
- Ready for **containerized deployment** with Docker.

---




