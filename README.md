# database-week-8

# Project Title
Library Management System Database

## Description
This project implements a complete relational database management system for a Library Management use case using MySQL. It includes tables for Authors, Books, Members, Loans, and Genres with proper constraints and relationships.

## How to run/setup the project
1. Import the `library_management.sql` file into your MySQL server.
2. Use a MySQL client or command line to execute the SQL script:
   ```bash
   mysql -u your_username -p your_database_name < library_management.sql
   ```
3. The script will create all necessary tables with constraints and relationships.

## ERD
A conceptual Entity-Relationship Diagram (ERD) for this database can be created using tools like MySQL Workbench or draw.io. It includes entities such as Authors, Books, Members, Loans, and Genres with their relationships.

You can create the ERD based on the schema defined in `library_management.sql`.

---

Question 1: Build a Complete Database Management System
Objective:
Design and implement a full-featured database using only MySQL.

What to do:

Choose a real-world use case (e.g., Library Management, Student Records, Clinic Booking System, Inventory Tracking, etc.)

Create a well-structured relational database using SQL.

Use SQL to create:

Tables with proper constraints (PK, FK, NOT NULL, UNIQUE)

Relationships (1-1, 1-M, M-M where needed)

Deliverables:

A single .sql file containing your:

CREATE TABLE statements

Submission Instructions

Push your complete project to a GitHub repository

📌 README file with:

Project Title

Description of what your project does

How to run/setup the project (or import SQL)

Screenshot or link to your ERD

The repo must include:



🧠 For Question 1:

Only one .sql file (well-commented)
## licence
MIT License

Copyright (c) 2025 joshua mwendwa

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

