Hotel Management System

A Python + MySQL based console application to manage hotel operations including guest records, bookings, billing, and restaurant services.

📖 Overview

This project is a database-driven hotel management system that simulates real-world operations. It integrates Python with MySQL to ensure structured data storage and efficient workflow management.

🚀 Features
👤 Guest Management
Add and store guest details
Retrieve guest records using Guest ID
🛏️ Booking System
Manage check-in and check-out dates
Maintain booking records
💰 Room Management
Multiple room categories:
Ultra Royal — ₹10,000/day
Royal — ₹5,000/day
Elite — ₹3,500/day
Budget — ₹2,500/day
Automatic rent calculation
🍽️ Restaurant Billing
Menu-based ordering system
Dynamic bill calculation
🧾 Final Billing
Combines all charges
Displays complete invoice
🛠️ Tech Stack
Language: Python
Database: MySQL
Library: mysql-connector-python
🗄️ Database Schema
Table Name	Purpose
C_DETAILS	Guest information
BOOKING_RECORD	Booking details
ROOM_RENT	Room allocation & rent
Restaurant	Food orders
TOTAL	Final billing
⚙️ Setup Instructions
1️⃣ Install Dependencies
pip install mysql-connector-python
2️⃣ Run the Program
python your_file_name.py
3️⃣ Database Setup
Enter MySQL credentials when prompted
Database HMS will be created automatically
📋 Menu
1 → Add Guest Details  
2 → Booking Details  
3 → Room Rent  
4 → Restaurant Bill  
5 → View Guest  
6 → Generate Bill  
7 → Exit  
🧠 Key Concepts
SQL integration with Python
CRUD operations
Modular function design
Persistent data storage
⚠️ Limitations
No GUI (console-based)
Basic validation
Uses global variables
No authentication
🔮 Future Scope
GUI / Web-based interface
Login system
Payment integration
Advanced database design
👨‍💻 Author

Mayank Pawar

📎 Source

Code reference:

🔥 Why This Looks Professional
Proper heading hierarchy (#, ##, ###)
Clean spacing and sections
Use of bold text for emphasis
Tables for structure
Code blocks for commands
Emojis used sparingly for readability
