# Craftique - eCommerce Website Database Project

This repository contains the MySQL database design and implementation for an eCommerce website. The project is part of a DBMS lab assignment, built using **MySQL** and managed via **XAMPP phpMyAdmin**.

---
This was done as a team effort, here is the team info:

**Team Laughter Crew**
- Ramesha Rawnok Haque (ID: 1665)
- Kh Sadman Sakib (ID: 1951)
- Most. Sumaiya Islam Sithi (ID: 1915)
- Fahmida Akter Juthi (ID: 1926)
- Hafijur Rahman (ID: 1620)

---

The project is submitted to:

**MD Shah Jalal**</br>
Senior Lecturer</br>
Department of CSE, Daffodil International University

---

## Features

- **Comprehensive Database Schema**: Designed to support core eCommerce functionality.
- **User Management**: Handles customer registrations, logins, and profiles.
- **Product Management**: Includes product categories, details, and inventory tracking.
- **Order Processing**: Covers order placement, payment details, and shipping.
- **Admin Functionality**: Tracks sales, manages inventory, and handles user roles.

---

## Database Schema

The database consists of multiple tables to support the functionality of the eCommerce website. Below are the key tables:

### 1. `users`
- Stores user information such as names, emails, passwords (hashed), and roles.

### 2. `products`
- Maintains details of the products available for purchase.

### 3. `categories`
- Categorizes products for better navigation.

### 4. `orders`
- Tracks user orders and their statuses.

### 5. `order_items`
- Stores details of products included in each order.

### 6. `payments`
- Records payment details for orders.

There are total of 17 tables, 20+ procedures, 20+ triggers and 20+ views in the project. The project report demostrate them.

---

## Setup Instructions

Follow these steps to set up the database on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   ```

2. **Start XAMPP**:
   - Launch XAMPP and start the **Apache** and **MySQL** modules.

3. **Import the Database**:
   - Open `phpMyAdmin` in your browser (usually at `http://localhost/phpmyadmin`).
   - Create a new database (e.g., `ems`).
   - Import the `ems.sql` file from this repository.

4. **Verify the Tables**:
   - Ensure all tables are created successfully with the required schema.

---

## Usage

- Use this database as the backend for your eCommerce project.
- Connect your web application (frontend) to the database using a programming language or framework of your choice.
- Test database operations such as user registration, product addition, order placement, and payment processing.

---

## Tools and Technologies

- **MySQL**: Database management system.
- **phpMyAdmin**: Database administration tool.
- **XAMPP**: Local server for running MySQL and Apache.

---

## Contributions

Contributions are welcome! If you'd like to improve the database schema or add features, feel free to fork the repository, make changes, and submit a pull request.

---

## Contact

For questions or support, please reach out:

- **Author**: sakibsidha
- **Email**: sakib22205101951@diu.edu.bd
- **University**: Daffodil International University

---

Thank you for exploring this project!

