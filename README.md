# Library Management 

This project contains an SQL schema and ER diagram for a basic Library Management System.

## 📁 Project Structure

- `schema.sql` – SQL script to create database schema with relationships
- `LibDB.png` – (Optional) Entity-Relationship Diagram for visual understanding
- `README.md` – Project overview and instructions

## 🧰 Tools Used

- MySQL Workbench
- GitHub

## 📚 Schema Overview

The schema includes the following tables:

1. **Authors** – Stores author details
2. **Books** – Stores book details, linked to Authors
3. **Members** – Stores member details
4. **Borrowings** – Tracks which members borrowed which books

## 🔗 Relationships

- One author can write many books (1:M)
- One member can borrow many books (M:M via Borrowings)
- Each borrowing record links one book and one member

## 🚀 Getting Started

To use this project:

1. Clone or download the repo
2. Open `schema.sql` in MySQL Workbench or pgAdmin
3. Run the script to create all tables
4. (Optional) View `LibDB.png` for visual representation
