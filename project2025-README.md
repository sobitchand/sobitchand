# 🌐 Project 2025 — Dynamic Web Application

<p align="left">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

---

## What is this?

Project 2025 is a full-stack dynamic web application built from scratch as part of my engineering coursework at Pokhara University. It provides a complete user lifecycle — registration, login, and a personal dashboard — alongside an admin panel for managing orders and users. The goal was to understand how real-world web systems are structured and secured end to end.

---

## ✨ Features

- **User Authentication** — Secure register and login system with session management
- **Admin Dashboard** — Centralized control panel for managing users and system data
- **Order Management** — Create, view, and track orders through a dedicated interface
- **Role-based Access** — Separate views and permissions for admin vs regular users
- **Clean UI** — Minimal, functional frontend built with pure HTML and CSS

---

## 🚀 How to Run It

### Prerequisites
- PHP 7.4 or higher
- MySQL / MariaDB
- A local server (XAMPP, WAMP, or Laragon recommended)

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/sobitchand/project2025.git
cd project2025

# 2. Move the project into your server's web root
#    For XAMPP: C:/xampp/htdocs/project2025
#    For WAMP:  C:/wamp64/www/project2025

# 3. Import the database
#    Open phpMyAdmin → Create a new database → Import the .sql file (if provided)

# 4. Configure database connection
#    Edit the DB config file (config.php or db.php) with your credentials:
#    DB_HOST = localhost
#    DB_USER = root
#    DB_PASS = your_password
#    DB_NAME = project2025

# 5. Start your local server and visit:
http://localhost/project2025/index.php
```

### Default Admin Access
```
URL:      http://localhost/project2025/admin.php
Username: admin
Password: admin123   ← change this immediately
```

---

## 📸 Screenshots / Demo

> Screenshots coming soon.

| Page | Preview |
|------|---------|
| Landing Page | `index.html` |
| Login | `login.php` |
| Dashboard | `dashboard.php` |
| Admin Panel | `admin.php` |
| Orders | `orders.php` |

---

## 🧠 What I Learned

- **Server-side scripting** — How PHP processes form data, manages sessions, and talks to a database without exposing logic to the client
- **Authentication fundamentals** — The difference between a login form and a secure login system (hashing, session tokens, redirect guards)
- **SQL & database design** — Writing raw queries, structuring relational tables, and avoiding basic injection vulnerabilities
- **Project structure** — How to separate concerns across files (auth, routing, views) even in a simple PHP app

---

## 📁 Project Structure

```
project2025/
├── index.html        # Landing page
├── index.php         # App entry point
├── login.php         # Login form + auth logic
├── register.php      # User registration
├── dashboard.php     # User dashboard
├── admin.php         # Admin control panel
├── order.php         # Single order view
└── orders.php        # Orders list
```

---

## 👤 Author

**Purushottam Chand Bohora**
BE Information Technology — Pokhara University
GitHub: [@sobitchand](https://github.com/sobitchand)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
