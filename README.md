# Craftique - eCommerce Website Database Project

This repository contains the MySQL database design and implementation for an eCommerce website. The project is part of a DBMS lab assignment, built using **MySQL** and managed via **XAMPP phpMyAdmin**.

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
- Example columns: `user_id`, `name`, `email`, `password`, `role`.

### 2. `products`
- Maintains details of the products available for purchase.
- Example columns: `product_id`, `name`, `description`, `price`, `category_id`, `stock`.

### 3. `categories`
- Categorizes products for better navigation.
- Example columns: `category_id`, `category_name`.

### 4. `orders`
- Tracks user orders and their statuses.
- Example columns: `order_id`, `user_id`, `order_date`, `status`, `total_amount`.

### 5. `order_items`
- Stores details of products included in each order.
- Example columns: `order_item_id`, `order_id`, `product_id`, `quantity`, `price`.

### 6. `payments`
- Records payment details for orders.
- Example columns: `payment_id`, `order_id`, `payment_date`, `payment_method`, `amount`.

---

## Setup Instructions

Follow these steps to set up the database on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   cd ecommerce-database
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

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

---

## Contact

For questions or support, please reach out:

- **Author**: sakibsidha
- **Email**: [sakib22205101951@diu.edu.bd]
- **University**: Daffodil International University

---

Thank you for exploring this project!

