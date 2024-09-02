# Pharmageddon Backend

[![PHP](https://img.shields.io/badge/PHP-v8.1-777BB4?logo=php&color=777BB4&labelColor=303030)](https://www.php.net/)
[![Laravel](https://img.shields.io/badge/Laravel-v9.0-FF2D20?logo=laravel&color=FF2D20&labelColor=303030)](https://laravel.com/)
[![MySQL](https://img.shields.io/badge/MySQL-v8.0-4479A1?logo=mysql&color=4479A1&labelColor=303030)](https://www.mysql.com/)
[![Composer](https://img.shields.io/badge/Composer-v2.0-885630?logo=composer&color=885630&labelColor=303030)](https://getcomposer.org/)
[![JWT](https://img.shields.io/badge/JWT-JSON_Web_Tokens-000000?logo=jsonwebtokens&color=000000&labelColor=303030)](https://jwt.io/)
[![Firebase](https://img.shields.io/badge/Firebase-v10.0.0-FFCA28?logo=firebase&color=FFCA28&labelColor=303030)](https://firebase.google.com/)
[![Postman](https://img.shields.io/badge/Postman-API_Testing-FF6C37?logo=postman&color=FF6C37&labelColor=303030)](https://www.postman.com/)
[![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?logo=docker&color=2496ED&labelColor=303030)](https://www.docker.com/)

## 💡 Project Overview

Pharmageddon is a comprehensive solution designed to streamline medication management for pharmacies. It offers both mobile and web applications, enabling users to browse, order, and track medications efficiently. The system includes features like secure authentication, real-time order tracking, detailed medicine information, and multi-language support. Built with Laravel for the backend and MySQL for data management, Pharmageddon ensures robust performance and security. The integration with Firebase allows real-time notifications, enhancing user experience. This project aims to simplify pharmacy operations, improve customer service, and ensure quick access to critical medication information across platforms.

## Table of Contents

-   [✨ Features](#-features)
-   [🛠️ Project Structure & Technologies Used](#️-project-structure--technologies-used)
-   [📱📱 App Preview](#-app-preview)
-   [👥 Team Members](#-team-members)

## ✨ Features

-   **Secure Authentication**: Implements JWT-based authentication to ensure secure user sessions across both mobile and web platforms.
-   **Medication Management**: Provides endpoints for creating, reading, updating, and deleting (CRUD) medication records, including detailed descriptions, manufacturer information, and effect categories.
-   **Order Processing**: Manages order creation, status updates, and real-time tracking, facilitating efficient order handling for pharmacies.
-   **Notification System**: Integrated with Firebase to send real-time push notifications about order status updates and other critical events.
-   **Multi-language Support**: API endpoints are designed to handle multiple languages, enhancing accessibility for users in different regions.
-   **Role-Based Access Control**: Supports different user roles (Admin, Pharmacist, User), each with specific permissions to ensure data security and operational integrity.

## 🛠️ Project Structure & Technologies Used

### Project Structure

The Pharmageddon backend follows a clean, modular architecture that separates concerns into different layers, making the system maintainable and scalable:

-   **Controllers**: Handle incoming requests and return responses. Controllers are responsible for orchestrating the application flow by interacting with services and repositories.
-   **Services**: Contain the business logic of the application, providing an abstraction over data processing and other operations.
-   **Repositories**: Abstract the data layer, interacting with MySQL to perform CRUD operations.
-   **Middleware**: Manages the request pipeline, ensuring secure authentication and authorization.
-   **Models**: Represent the database entities, defining the schema and relationships for Laravel’s Eloquent ORM.

### Technologies Used

-   **Laravel**: A PHP framework that provides an elegant syntax and powerful tools for building scalable web applications. Laravel’s MVC architecture ensures separation of concerns and facilitates the development of both simple and complex features.
-   **MySQL**: A relational database management system used for storing and retrieving data. MySQL is chosen for its robustness, reliability, and compatibility with Laravel’s Eloquent ORM.
-   **JWT Authentication**: JSON Web Tokens (JWT) are used to securely manage user sessions. JWT ensures that each request is authenticated without the need to constantly check session data on the server.
-   **Firebase**: Used for sending real-time notifications. Firebase integration allows for seamless push notifications, improving user engagement and responsiveness.

## 📱 App Preview

<div style="display: flex; flex-wrap: wrap;">

<img src="app-preview/app-preview/phr-web1.png" alt="Login page" width="40%" style="padding-right:15px;padding-bottom:15px;">

<img src="app-preview/app-preview/phr-web5.png" alt="Medicine Browsing" width="40%" style="padding-right:15px;padding-bottom:15px;">

<img src="app-preview/app-preview/phr-web4.png" alt="Manufacturer Browsing" width="40%" style="padding-right:15px;padding-bottom:15px;">

<img src="app-preview/app-preview/phr-web6.png" alt="Effect Categories Browsing" width="40%" style="padding-right:15px;padding-bottom:15px;">

<img src="app-preview/app-preview/phr-web2.png" alt="App page" width="40%" style="padding-right:15px;padding-bottom:15px;">

<img src="app-preview/app-preview/phr-web3.png" alt="Order Tracking" width="40%" style="padding-right:15px;padding-bottom:15px;">

<img src="app-preview/app-preview/phr-web7.png" alt="Flow Chart of Orders" width="40%" style="padding-right:15px;padding-bottom:15px;">

</div>

### Authentication

#### Secure login and registration process for users.

![Authentication](app-preview/phr1.png)

### Medication - Manufacturer Browsing

#### Browse through medications and view manufacturer details and effects.

![Medication Browsing](app-preview/phr5.png)

### Medication Details

#### Read all details, mark as favorite, select quantity, and add to cart.

![Medication Details](app-preview/phr3.png)

### Cart Management

#### Manage your cart, edit quantities, and place orders.

![Cart Management](app-preview/phr7.png)

### Order Tracking

#### Track the status of your orders in real-time.

![Order Tracking](app-preview/phr6.png)

### Order Details and Analytics

#### View detailed order information and analytics.

![Order Details and Analytics](app-preview/phr4.png)

### Notifications - Profile

#### Receive real-time notifications from Firebase.

![Notifications](app-preview/phr2.png)

## 👥 Team Members

| S.No. | Team Member Name  | GitHub                                                     | Technology      |
| ----- | ----------------- | ---------------------------------------------------------- | --------------- |
| 1.    | Ahmad Nour Haidar | [@Ahmad-Nour-Haidar](https://github.com/Ahmad-Nour-Haidar) | Flutter Mobile  |
| 2.    | Ayman Albonny     | [@Ayman2023bo](https://github.com/Ayman2023bo)             | Flutter Mobile  |
| 3.    | Osama Saddik      | [@osamasaddik](https://github.com/osamasaddik)             | Laravel Backend |
