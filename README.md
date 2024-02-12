# Movie_PHP_Web_App
This is my project about creating a Managing Movie PHP Web Application

Project Overview
This project involves the development of a small web application designed to manage movie entities through the basic operations of creation, reading, updating, and deleting (CRUD). The application will interact with a MySQL database to persistently store and retrieve movie data. It is to be developed using PHP, HTML, and optionally JavaScript and CSS, without reliance on any frameworks or external libraries.

Project Requirements
Technologies Used:

The application must be developed using PHP, HTML, and optionally JavaScript and CSS.
Compatibility with PHP version 8.2.0 or earlier is required.
Direct use of the MySQLi PHP extension for database interactions.
All SQL queries and statements must employ parameterized statements to prevent SQL injection attacks.
Database Setup:

A MySQL database is to be utilized for data storage.
XAMPP is MySQL database server management
A table named movies must be created with the following specifications:
id: INT, NOT NULL, PRIMARY KEY, AUTO-INCREMENT
title: VARCHAR(128), NOT NULL
director: VARCHAR(64), NOT NULL
year: INT, NOT NULL
date_created: DATETIME, NOT NULL, DEFAULT CURRENT_TIMESTAMP()
Insert test values into the movies table for initial setup.
Web Application Structure:

The application will feature two main web pages:
Entity Creation Page: A form for adding new movie records to the database. This page uses the POST HTTP method for form submission, leading to the creation of a new movie record based on user input, followed by redirection to the entity display page.
Entity Display, Edition, and Deletion Page: A form (or multiple forms) for displaying, editing, and deleting movie records. This page also uses the POST HTTP method and ensures certain entity properties are not editable by users. It dynamically displays values from a requested entity.
Business Logic:

Implement endpoints to handle form requests for CRUD operations.
Use root/<empty> as the default username/password for database connection.
Organize code into small, readable functions to facilitate maintenance and understanding.
Security and Validation:

Server-side validation of input values to ensure data integrity and prevent malicious input.
Testing:

Perform tests to verify the application's functionality, including the creation of a new movie record, modification of an existing record, and deletion of a record from the database.
Development Phases
Part 1: Project Setup

Initialize project directory and set up a PHP development environment compatible with PHP 8.2.0 or earlier.
Establish a MySQL database connection.
Part 2: Database Creation

Create the movies table within the MySQL database and populate it with initial test data.
Part 3: Developing the Business Logic

Develop PHP scripts to handle CRUD operations with the database, ensuring secure database interactions through parameterized queries.
Part 4: Entity Creation Page Development

Design and implement the entity creation page with a form for adding new movies.
Part 5: Entity Display, Edition, and Deletion Page Development

Develop the page(s) for displaying, editing, and deleting movie entities, ensuring dynamic content loading and secure modification/deletion processes.
Part 6: Application Testing

Thoroughly test the application using predefined test cases to ensure all functionalities work as intended and data integrity is maintained throughout the operations.
This project will demonstrate proficiency in web application development using PHP and MySQL, emphasizing secure coding practices, database management, and user interaction through web forms.
