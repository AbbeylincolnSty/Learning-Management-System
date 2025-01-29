# Learning-Management-System
Design an LMS 

Task to create a learning management system in 
Node js
Mysql
javascript

1. Project Setup
a. Install Required Tools
Node.js: Ensure Node.js is installed on your system. You can download it from nodejs.org.
MySQL: Install MySQL or use an online database service like XAMPP or PHPMyAdmin.
Code Editor: Use a code editor like VS Code, IntelliJ, or Sublime Text.
b. Set Up the Project Directory
Create a new folder for your project:

mkdir lms-nodejs
cd lms-nodejs

c. Initialize the Node.js Project
Run the following command to initialize the project:

npm init -y

d. Install Dependencies
Install the required packages:

npm install express mysql cors bcryptjs dotenv

Express: Web framework for Node.js.
MySQL: Database driver for Node.js.
CORS: Enable Cross-Origin Resource Sharing.
bcryptjs: For password hashing.
dotenv: For environment variables.
jsonwebtoken: For JWT token generation (install later if needed).
2. Database Setup
a. Create a MySQL Database
Open your MySQL database management tool (e.g., phpMyAdmin or MySQL Workbench).
Create a new database named lms_db.
Create tables for users, courses, enrollments, etc.
b. Write SQL Scripts
