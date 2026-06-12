# 🌴 Passport to Paradise

> **An Interactive, Gamified Full-Stack Travel Challenge Web Application**

[![Live Demo](https://img.shields.io/badge/Demo-Live%20Website-brightgreen?style=for-the-badge&logo=internet-explorer)](https://passport-to-paradise.free.nf)
[![Walkthrough](https://img.shields.io/badge/Video-Walkthrough%20Demo-red?style=for-the-badge&logo=youtube)](YOUR_YOUTUBE_OR_VIMEO_LINK_HERE)

Passport to Paradise is a full-stack gamified travel challenge web application developed using **PHP, MySQL, JavaScript, HTML5, and CSS3**. Players progress through multiple holiday tiers—from *Budget* to *Paradise*—by completing interactive travel challenges, earning points, collecting passport stamps, and unlocking new destinations.

This repository serves as a public showcase of my practical software engineering skills, demonstrating secure backend architecture, relational database design, asynchronous JavaScript interactions, and fully functional back-office administration.

---

## 🔗 Project Links & Portals

* **🌐 Live Production Deployment:** [https://passport-to-paradise.free.nf](https://passport-to-paradise.free.nf)
* **🎬 Video Demonstration:** [Watch the App Walkthrough](YOUR_YOUTUBE_OR_VIMEO_LINK_HERE)

### 🔐 Interactive Showcase Credentials
To explore the live administrative dashboard capabilities without compromising database security, use the following sandbox credentials on the live application:
* **Admin Login Portal:** `https://passport-to-paradise.free.nf/admin/login.php`
* **Demo Username:** `admin` *(Or insert your safe sandbox username here)*
* **Demo Password:** `Password123!` *(Or insert your safe sandbox password here)*

---

## ✨ Key Features

### 🎮 Dynamic Challenge Engine
* **Database-Driven Mechanics:** Challenges and questions are pulled dynamically based on player state.
* **Server-Side Verification:** Form submissions pass securely through rigorous server-side answer checking.
* **Automatic Progression:** Points are accurately aggregated to compute immediate tier transitions.

### 📈 Real-Time Progress Tracking
* **Asynchronous Updates:** Live UI interaction handling via the native **JavaScript Fetch API**.
* **Seamless Experience:** Score updates, badge rewards, and lock metrics refresh in real time without annoying page reloads.

### 🛠️ Administrative Dashboard (Full CRUD)
* **Content Control:** Complete system management portal allowing verified admins to **Create, Read, Update, and Delete** Destinations, Challenges, and Holiday Tiers.
* **Analytics Views:** Track player metrics, attempts, and database state logs securely.

### 🔒 Secure System Design
* **SQL Injection Defenses:** 100% of communication queries run via strictly prepared SQL statements.
* **State Management:** Secure session structures protect user identities and validation parameters.
* **Data Safeguards:** Password hashing engines preserve user security.

---

## 🏗️ Architecture & Directory Overview

The application follows a clean, layered layout to ensure separation of concerns and maintainability:

```text
passport-to-paradise/
├── admin/                     # Admin Panels & Management APIs (CRUD Logic)
├── assets/                    # Presentation elements (CSS layouts, JavaScript Fetch modules, Audio/Images)
├── config/                    # System configurations & Core database connection strings (Masked for Public Safety)
├── includes/                  # Global application modules, validation logic, and template components
├── sql/                       # Relational database schema architecture file (.sql)
├── challenge.php              # Dynamic gameplay view interface
└── dashboard.php              # Live client progress profile metrics panel
