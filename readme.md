# Book Management System

A web-based **Book Management System** that allows administrators to manage books, view customer orders, and monitor sales through a secure admin panel. This project is **separate and independent** from the LMS project.

---

## Project Overview

The Book Management System provides:

* Centralized **admin dashboard**
* Complete **book management** (add, edit, delete books)
* **Customer order management**
* Simple and secure admin authentication
* Database-driven architecture using MySQL

---

## Tech Stack

* **Backend:** PHP
* **Database:** MySQL
* **Server:** Apache (000webhost compatible)
* **Database Tool:** phpMyAdmin

---

## 🗄️ Database Setup

1. Locate the database file:

   ```text
   /db/Onlinesell.sql
   ```

2. Open **phpMyAdmin**.

3. Create a new database (for example: `onlinesell`).

4. Import the `Onlinesell.sql` file into the created database.

---

## 🔧 Database Configuration

1. Navigate to the file where the **database connection function** is defined.

2. Update the database credentials:

   * Host name
   * Database name
   * Username
   * Password

3. Save the file after making the changes.

---

## Admin Panel Access

* **Admin URL:**

  ```text
  https://bookwallsell.000webhostapp.com/book/admin
  ```

* **Admin Credentials:**

  * **Username:** `admin`
  * **Password:** `12345`

---

## Admin Features

After successful login, the admin can:

* Add, update, and delete books
* Manage book categories
* View customer orders
* Track order details and status
* Manage inventory records

---

## Functional Modules

* **Admin Authentication**
* **Book Management**
* **Order Management**
* **Database Management**

---

## Testing

* Manual testing of admin workflows
* Database validation testing
* Login and authentication testing
* CRUD operation testing for books and orders

---

## Deployment

* Hosted on **000webhost**
* Compatible with shared hosting environments

---

## Future Enhancements

* User-facing book catalog
* Online payment integration
* Order status notifications
* Advanced reporting and analytics

---

## Notes

* This project is **independent** of the LMS system.
* Ensure database credentials are correct before accessing the admin panel.
