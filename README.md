# University Cafeteria Management System

A full-stack **University Cafeteria Management System** designed to simplify food ordering, cafeteria operations, inventory management, payment processing, delivery, and administrative activities.

[![React](https://img.shields.io/badge/Frontend-React-blue?logo=react)](https://react.dev/)
[![Redux](https://img.shields.io/badge/State%20Management-Redux-purple?logo=redux)](https://redux.js.org/)
[![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow?logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Backend-Node.js-green?logo=node.js)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/API-Express.js-lightgrey?logo=express)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-green?logo=mongodb)](https://www.mongodb.com/)

## Project Overview

The **University Cafeteria Management System** is a full-stack web application developed to provide an efficient and centralized platform for managing university cafeteria operations.

The system integrates **food ordering, payment processing, inventory management, delivery management, customer feedback, and administrative activities** into a single platform.

The application follows a **role-based architecture**, allowing different categories of users to access features relevant to their responsibilities.

## User Roles & Features

### Customer

* Browse available food items and menus.
* Place food orders online.
* Customize food orders.
* Specify dietary requirements.
* View previous orders and order history.
* Save favorite orders for future use.
* Provide feedback and ratings for food items.

### Admin

* Add, edit, and delete food items and menus.
* Manage user accounts and user roles.
* View and manage customer orders.
* Access order history.
* Generate sales and revenue reports.
* Monitor customer feedback.
* Monitor inventory and stock availability.

### Manager

* Manage staff schedules and shifts.
* Monitor sales and revenue trends.
* Analyze customer feedback and ratings.
* Manage menu items and promotions.
* Manage pricing-related activities.
* Monitor food quality and cafeteria hygiene standards.

### Cashier

* Process customer orders and payments.
* Manage cash register and POS operations.
* Handle refunds and returns.
* Assist customers with order-related issues.
* Maintain cafeteria orderliness and cleanliness.

### Delivery Personnel

* Receive and fulfill delivery orders.
* Track order progress.
* Update delivery status.
* Maintain delivery records and receipts.
* Ensure timely delivery of food orders.

## Key Features

* Role-based cafeteria management.
* Online food browsing and ordering.
* Food order customization.
* Dietary preference support.
* Customer order history.
* Favorite order management.
* Customer feedback and rating system.
* Food menu management.
* Inventory and stock management.
* User account and role management.
* Order and payment management.
* Sales and revenue monitoring.
* Customer feedback monitoring.
* Staff scheduling and shift management.
* Delivery order tracking.
* Delivery status updates.
* Refund and return management.

## System Modules

### Food & Menu

Manage food items, categories, prices, availability, and cafeteria menus.

### Order Management

Manage customer orders, order customization, order history, and delivery status.

### Inventory Management

Monitor stock levels, food availability, and inventory information to support cafeteria operations.

### Payment Management

Handle customer payments, POS operations, refunds, returns, and transaction-related activities.

### Delivery Management

Manage delivery orders, delivery progress, status updates, and delivery records.

### Staff Management

Manage staff members, schedules, shifts, and role-specific responsibilities.

### Reports & Feedback

Monitor sales, revenue, customer ratings, and feedback to support cafeteria management and operational decisions.

## Technology Stack

| Component            | Technology                 |
| -------------------- | -------------------------- |
| Frontend             | React                      |
| State Management     | Redux                      |
| Programming Language | JavaScript                 |
| Backend              | Node.js, Express.js        |
| Database             | MongoDB                    |
| ODM                  | Mongoose                   |
| API                  | REST API                   |
| Access Control       | Role-Based Access Control  |
| Architecture         | Full-Stack Web Application |

## System Architecture

The system follows a **full-stack REST-based architecture** consisting of:

**Frontend → REST API → Backend → MongoDB**

* **Frontend:** React and Redux provide the user interface and application state management.
* **Backend:** Node.js and Express.js handle server-side logic and REST API services.
* **Database:** MongoDB stores users, food items, orders, inventory, payments, feedback, and other application data.
* **Access Control:** Role-based access ensures that customers, administrators, managers, cashiers, and delivery personnel access the appropriate system functionality.

## Project Workflow

### Customer Workflow

```text
Browse Menu
     ↓
Select Food
     ↓
Customize Order
     ↓
Place Order
     ↓
Payment
     ↓
Order Processing
     ↓
Delivery / Collection
     ↓
Feedback & Rating
```

### Administrative Workflow

```text
User Management
      ↓
Menu Management
      ↓
Inventory Management
      ↓
Order Management
      ↓
Payment Monitoring
      ↓
Sales & Revenue Reports
      ↓
Feedback Analysis
```

## GitHub Repository

The complete source code of the **University Cafeteria Management System** is available on GitHub.

**Repository:**
https://github.com/shakil2022/Ecommerce-Website

## Project Information

**Project:** University Cafeteria Management System
**Architecture:** Full-Stack REST-Based Web Application
**Frontend:** React + Redux
**Backend:** Node.js + Express.js
**Database:** MongoDB + Mongoose
**Access Control:** Role-Based Access Control
**Primary Users:** Customers, Admins, Managers, Cashiers, Delivery Personnel
