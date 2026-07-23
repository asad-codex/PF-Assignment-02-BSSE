# C++ University Console Applications Collection 🚀

A comprehensive portfolio of console-based C++ applications developed using **procedural programming** principles as part of university software engineering coursework. Each project demonstrates modular function design, control structures, arrays, and business logic implementation in C++.

---

## 📑 Table of Contents
1. [LESCO Electricity Bill Management System](#1-lesco-electricity-bill-management-system)
2. [Grocery Mart Billing System](#2-grocery-mart-billing-system)
3. [Online Shopping System](#3-online-shopping-system)
4. [Personal Student Diary](#4-personal-student-diary)
5. [Restaurant Management System](#5-restaurant-management-system)
6. [Social Media Management System](#6-social-media-management-system)
7. [Prerequisites & Compilation Guide](#7-prerequisites--compilation-guide)

---

### 1. LESCO Electricity Bill Management System
* **Source File:** [`Electricity Bill LESCO.cpp`](./Electricity%20Bill%20LESCO.cpp)
* **Overview:** Designed to calculate automated electricity consumption bills for Lahore Electric Supply Company (LESCO) connections. It evaluates usage across progressive slab rates and computes heavy installation estimates for new connections.
* **Key Features:**
  - **Customer Registration:** Captures customer name, ID, connection type (`H` for Household / `C` for Commercial), and existing meter count.
  - **Progressive Slab Calculation:** Evaluates unit consumption across 8 distinct tiered slab rates.
  - **Tax & Duty Breakdown:** Automatically computes fixed charges, 1.5% electricity duty, income tax (10% household, 15% commercial), standard meter rent, TV fee, and 18% GST.
  - **New Connection Estimator:** Calculates installation fees including meter costs, cables, security deposits, and heavy proper connection charges.

---

### 2. Grocery Mart Billing System
* **Source File:** [`Grocery Mart Billing System.cpp`](./Grocery%20Mart%20Billing%20System.cpp)
* **Overview:** A complete point-of-sale (POS) and inventory checkout simulation for a grocery store supporting itemized carts, membership discounts, and loyalty point redemptions.
* **Key Features:**
  - **Item Catalog & Cart Management:** Browse 8 essential grocery items (Rice, Sugar, Cooking Oil, Milk, Tea, Flour, Eggs, Detergent) and manage quantities dynamically.
  - **Tax & Discount Logic:** Calculates category-based sales tax (10% on detergent, 5% on others), membership discounts (7% for members), and tier-based bill discounts (5% to 10%).
  - **Loyalty Program:** Automatically generates loyalty points based on total purchase amount (1 point per Rs. 100) with interactive point redemption options.
  - **Payment Handling:** Manages payment methods (Cash vs. Card with 2% processing fees) and prevents negative billing errors.

---

### 3. Online Shopping System
* **Source File:** [`Online Shopping System.cpp`](./Online%20Shopping%20System.cpp)
* **Overview:** An e-commerce console checkout system tailored for online retail management, handling multi-city deliveries, customer history tiers, and checkout taxes.
* **Key Features:**
  - **Product Catalog:** Features 8 popular fashion and tech items (T-Shirts, Jeans, Shoes, Watches, Handbags, Headphones, Mobile Covers, Perfumes).
  - **Smart Delivery Charges:** Automatically applies flat delivery rates based on destination city (Rs. 250 for major hubs like Lahore, Karachi, Islamabad; Rs. 500 for other regions).
  - **Discounts & GST:** Implements 17% GST, customer loyalty discounts (5% for new, 10% for returning), and heavy order-value promotional discounts (up to 12%).
  - **Secure Checkout:** Prompt-driven payment selection supporting Cash on Delivery (COD) and Credit/Debit Cards (with a 2.5% transaction surcharge).

---

### 4. Personal Student Diary
* **Source File:** [`Personal Student Diary.cpp`](./Personal%20Student%20Diary.cpp)
* **Overview:** A secure, password-protected digital journal application that allows students to store, manage, and search personal daily notes directly in the console.
* **Key Features:**
  - **Authentication System:** Secure registration and login portal to protect private diary entries.
  - **CRUD Operations:** Supports creating up to 20 diary entries, viewing all titles, reading specific entries by index, updating existing content, and deleting individual entries or clearing the entire diary.
  - **Keyword Search:** Instant search utility to locate specific journal entries using title-based string matching.

---

### 5. Restaurant Management System
* **Source File:** [`Resturant Management System.cpp`](./Resturant%20Management%20System.cpp)
* **Overview:** A comprehensive food ordering and billing application built for dining establishments, managing dine-in versus takeaway service fees and promotional discounts.
* **Key Features:**
  - **Interactive Food Menu:** Browse 8 fast-food and traditional items (Burgers, Pizzas, Biryani, BBQ Platters, Fries, Cold Drinks) with quantities.
  - **Service & Tax Charges:** Dynamically calculates service charges (10% for Dine-in, 5% for Takeaway) and standard 16% GST.
  - **Tiered Promotional Discounts:** Automatically applies bill-size discounts ranging from 5% to 15% on orders exceeding Rs. 3,000.
  - **Free Delivery Eligibility:** Automatically flags qualified orders above Rs. 5,000 for complimentary delivery.

---

### 6. Social Media Management System
* **Source File:** [`Social Media Management System.cpp`](./Social%20Media%20Management%20System.cpp)
* **Overview:** A specialized tool designed for digital marketing agencies to calculate campaign costs, ad handling fees, and content design expenses across major social platforms.
* **Key Features:**
  - **Multi-Platform Support:** Manages campaigns across Instagram, Facebook, and LinkedIn with distinct base management fees.
  - **Content Customization:** Computes design expenses for static posts, reel/video productions, and carousel graphics.
  - **Ad Budget Management:** Implements tier-based handling fees (5% to 10%) based on total ad spend budgets.
  - **Business-Tier Discounts:** Automatically calculates agency discounts ranging from 5% to 10% based on business scale (Small, Medium, Corporate).

---

## 🛠️ Prerequisites & Compilation Guide

All applications are written in standard **C++** and require a C++ compiler compatible with C++11 or later (such as GCC, MinGW, Clang, or MSVC).

