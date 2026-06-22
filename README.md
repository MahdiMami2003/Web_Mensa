# Mensa Web Application

A database-driven web application displaying the university 
canteen menu, built as part of the Databases & Web Technologies 
module at FH Aachen.

## Features
- Dynamic menu display pulled from a MariaDB database
- Full CRUD operations via admin interface
- Clean separation of concerns via MVC architecture

## Tech Stack
PHP · SQL · MariaDB · HTML · CSS · MVC pattern

## Architecture
The application follows the Model-View-Controller (MVC) 
pattern:
- **Model** – database queries and data logic
- **View** – HTML/CSS templates
- **Controller** – request handling and routing

## How to Run
1. Clone the repo
2. Import `schema.sql` into a MariaDB/MySQL database
3. Update `config.php` with your database credentials
4. Run with XAMPP or any PHP server

## Context
University project – FH Aachen, WS 2025/26
