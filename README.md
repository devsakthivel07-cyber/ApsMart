APS MART – ONLINE GROCERY STORE

Project Documentation

1. Introduction

APS Mart is a web-based online grocery and stationery shopping application developed as a college academic project.
The system allows users to browse products, add them to cart, place orders, and make secure online payments.
An admin panel is provided to manage users, products, and orders efficiently.

This project demonstrates full-stack web development, including frontend UI/UX, backend logic, database management, and payment gateway integration.

2. Objectives of the Project

To build a real-world e-commerce application

To provide users with an easy and fast shopping experience

To implement secure online payment using Razorpay

To allow admin to manage products, users, and orders

To reduce manual order handling and improve efficiency

3. System Overview
3.1 User Module

User registration and login

Browse products by category

Add products to cart

Increase/decrease quantity

Checkout and online payment

View order history and profile details

3.2 Admin Module

Admin login

View total users, orders, revenue

Add / update / delete products

View all orders

Update order status (Pending, Delivered, etc.)

4. Technologies Used
Frontend

HTML5

Tailwind CSS

JavaScript (Fetch API, DOM manipulation)

Backend

PHP (Core PHP with PDO)

REST-style AJAX endpoints

Database

MySQL (phpMyAdmin)

Payment Gateway

Razorpay (Test Mode)

Server

Apache (XAMPP / Hosting server)

5. Database Design
Tables Used
5.1 users

id

name

email

phone

password

created_at

5.2 products

id

name

category

price

quantity

description

image

5.3 cart

id

user_id

product_id

quantity

5.4 orders

id

user_id

total

payment_method

status

payment_id

customer_name

customer_phone

address

created_at

5.5 addresses

id

user_id

address

city

pincode

6. Functional Modules Explanation
6.1 Product Management

Products are stored in the database

Displayed dynamically on the website

Filtered by category (Fruits, Snacks, etc.)

Admin can add/update/delete products

6.2 Cart System

Each user has an individual cart

Same product increases quantity instead of duplicating

Cart total updates dynamically

6.3 Checkout & Payment

Address verification before payment

Razorpay order creation

Secure payment processing

Payment success updates order status

6.4 Order Management

Orders stored after payment

Users can view past orders in profile

Admin can update order status

7. Security Features

Session-based authentication

Protected routes (login required)

SQL Injection prevention using PDO prepared statements

Payment handled securely by Razorpay

8. User Interface (UI/UX)

Fully responsive design (Mobile + Desktop)

Clean and modern UI using Tailwind CSS

Easy navigation with navbar and categories

Clear order and payment flow

9. Advantages of the System

Easy to use

Time saving

Secure payment

Real-time order tracking

Scalable for future features

10. Limitations

Uses Razorpay test mode (not live)

No OTP verification

No product reviews

Single address per user (can be expanded)

11. Future Enhancements

Live payment gateway

Multiple delivery addresses

Product reviews and ratings

Delivery tracking

Admin analytics charts

Email / SMS notifications

12. Conclusion

APS Mart is a complete end-to-end e-commerce web application developed using PHP and MySQL.
The project successfully demonstrates practical implementation of frontend design, backend logic, database integration, and online payment processing.

This project enhanced our understanding of full-stack development and real-world application design.

13. References

PHP Documentation – https://www.php.net

Razorpay API Docs – https://razorpay.com/docs

Tailwind CSS – https://tailwindcss.com

MySQL Documentation – https://dev.mysql.com
