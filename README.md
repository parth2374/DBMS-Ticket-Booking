# Advanced Ticket Booking System

## MCA DBMS Mini Project

An advanced database management system project that simulates a real-world ticket booking platform with safe concurrent transaction handling and database consistency mechanisms.

---

## 🚀 Project Overview

This project demonstrates core DBMS concepts used in modern ticket booking platforms such as railway, movie, and airline reservation systems.

The system focuses on handling multiple users booking seats simultaneously while maintaining data integrity and preventing conflicts.

---

## 🔥 Key Concepts Implemented

* Transaction Management
* Row Level Locking
* Deadlock Handling
* Optimistic Locking
* Rollback Handling
* Isolation Levels
* Auto Seat Release

---

## 🛠 Technologies Used

* MySQL
* SQL Transactions
* Concurrency Control Mechanisms

---

## ✨ Features

* Prevents double booking of seats
* Safe concurrent ticket booking
* Parallel seat handling
* Waiting queue support
* Automatic rollback on transaction failure
* Seat release mechanism for inactive bookings

---

## 📚 DBMS Concepts Covered

### 1. Transaction Management

Ensures all booking operations follow ACID properties.

### 2. Row Level Locking

Locks only the required seat rows instead of the entire table to improve concurrency.

### 3. Deadlock Handling

Detects and resolves deadlock situations during simultaneous bookings.

### 4. Optimistic Locking

Allows better performance in low-conflict scenarios.

### 5. Isolation Levels

Prevents dirty reads, non-repeatable reads, and phantom reads.

### 6. Rollback Handling

Automatically restores data consistency if any transaction fails.

---

## 🎯 Use Cases

* Movie Ticket Booking
* Railway Reservation Systems
* Airline Seat Reservation
* Event Booking Platforms

---

## 👨‍💻 Author

**Parth Bansal**
