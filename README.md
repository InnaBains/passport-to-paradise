# 🌴 Passport to Paradise

> **An Interactive, Gamified Full-Stack Travel Challenge Web Application**

[![Live Demo](https://img.shields.io/badge/Demo-Live%20Website-brightgreen?style=for-the-badge\&logo=internet-explorer)](https://passport-to-paradise.free.nf)
[![Walkthrough](https://img.shields.io/badge/Video-Walkthrough%20Demo-red?style=for-the-badge\&logo=youtube)](https://passport-to-paradise.free.nf)

---

## 📖 Overview

**Passport to Paradise** is a full-stack gamified travel challenge web application developed using **PHP, MySQL, JavaScript, HTML5, and CSS3**.

Players progress through multiple holiday tiers—from **Budget** to **Paradise**—by completing interactive travel challenges, earning points, collecting passport stamps, and unlocking new destinations.

This repository showcases practical software engineering skills, including secure backend architecture, relational database design, asynchronous JavaScript interactions, and a fully functional administrative dashboard.

---

## 🔗 Project Links

### 🌐 Live Website

https://passport-to-paradise.free.nf

### 🎬 Video Walkthrough

https://passport-to-paradise.free.nf

---

## 🔐 Demo Admin Credentials

To explore the administrative dashboard safely, use the following sandbox credentials:

**Admin Login**

https://passport-to-paradise.free.nf/admin/login.php

| Username | Password    |
| -------- | ----------- |
| `admin`  | `Admin123!` |

---

# ✨ Features

## 🎮 Dynamic Challenge Engine

* Database-driven travel challenges
* Dynamic question loading based on player progress
* Secure server-side answer validation
* Automatic point calculation and tier progression

---

## 📈 Real-Time Progress Tracking

* JavaScript Fetch API integration
* Live score updates
* Instant badge rewards
* Seamless UI refreshes without page reloads

---

## 🛠️ Administrative Dashboard (CRUD)

The admin panel allows authorized users to manage application content through complete CRUD functionality.

### Includes management for:

* Destinations
* Challenges
* Holiday Tiers
* Player analytics
* Attempts monitoring
* Database records

---

## 🔒 Security Features

The application incorporates several security best practices:

* Prepared SQL statements throughout
* SQL injection protection
* Secure PHP session management
* Password hashing
* Server-side validation
* Controlled database access

---

# 🏗️ Project Structure

```text
passport-to-paradise/
│
├── admin/
│   └── Admin Panels & CRUD Management
│
├── assets/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── audio/
│
├── config/
│   └── Database configuration (masked in public repository)
│
├── includes/
│   └── Shared components and helper functions
│
├── sql/
│   └── Database schema (.sql)
│
├── challenge.php
├── dashboard.php
├── process_answer.php
├── restart_journey.php
├── start.php
└── index.php
```

---

# 📋 Layered Architecture

| Layer                    | Responsibility                                                  | Main Components                                             |
| ------------------------ | --------------------------------------------------------------- | ----------------------------------------------------------- |
| **Presentation Layer**   | Renders user interfaces and handles client interactions         | `index.php`, `challenge.php`, `dashboard.php`, `assets/js/` |
| **Business Logic Layer** | Controls gameplay rules, validation, sessions, and scoring      | `process_answer.php`, `start.php`, `restart_journey.php`    |
| **Data Access Layer**    | Performs secure database operations using parameterized queries | `config/db.php`, `includes/functions.php`, `sql/`           |

---

# 🔧 Technologies Used

## Backend

* PHP 8.x

## Database

* MySQL

## Frontend

* HTML5
* CSS3
* JavaScript

## Asynchronous Communication

* Fetch API
* JSON

## Responsive Design

* Mobile-friendly layouts
* Modern CSS styling

---

# 🚀 Future Improvements

* Refactor the application into a RESTful API architecture
* Implement global CSRF protection
* Improve accessibility to meet WCAG and ARIA standards
* Develop a decoupled SPA frontend using React or Vue.js

---

# 🎯 Portfolio Purpose

This project forms an important part of my software engineering portfolio and demonstrates:

* Full-stack web development
* Secure backend programming
* Relational database design
* CRUD application development
* Asynchronous JavaScript
* Session management
* Responsive UI implementation
* Clean project architecture
* Industry-standard web development practices

---

## 📝 Note

For security and intellectual property protection, sensitive information such as environment variables, production configuration files, secret keys, and database credentials has been intentionally omitted or masked from this public repository.
