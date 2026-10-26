# NovaCart — Responsive E-Commerce Website

A responsive PHP + MySQL e-commerce demo built with HTML, CSS and vanilla JavaScript.

## Features
- Responsive home and product listing pages
- Product search by name, category or description
- Session-based shopping cart (add, update quantity, remove)
- Registration and login using PHP password hashing and prepared statements
- Demo checkout form (does not process payments or store orders)
- MySQL product and user tables
- Mobile navigation

## Requirements
- WAMP/XAMPP with PHP 7.4+ and MySQL/MariaDB
- PDO MySQL extension enabled
- Browser

## Run locally (WAMP)
1. Extract `ecommerce-website` into `C:\wamp64\www\`.
2. Start WAMP and ensure its icon is green.
3. Open phpMyAdmin, select the **Import** tab, and import `database/ecommerce.sql`.
4. Open `config/database.php` and set your MySQL username/password.
5. Visit `http://localhost/ecommerce-website/`.

## Database
The SQL file creates `ecommerce_db`, `products`, and `users`, then inserts sample products.

## Before submitting
- Replace or improve sample product data and images if desired.
- Test registration, login, product search and cart.
- Push all project files to a GitHub repository.
- Submit the repository URL to your task portal.

## Important limitations
This is a learning/demo project. Checkout does not charge money, create a persistent order, or arrange delivery. For a production store, add CSRF protection, order persistence, payment provider integration, inventory validation, HTTPS, rate limiting and security review. Never commit real credentials to GitHub.


Enhanced add-ons: `track_order.php` and `reviews.php` pages. Import the updated `database/ecommerce.sql` to create order/review tables. Tracking is simulated and requires courier API integration for real live tracking.
