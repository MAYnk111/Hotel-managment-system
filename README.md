Hotel Management System (HMS)

A Python-based Hotel Management System that uses MySQL database integration to manage guest details, bookings, room allocation, restaurant billing, and total bill generation.

📌 Project Overview

This project is a console-based application designed to simulate real-world hotel operations. It allows hotel staff to:

Register guests
Manage bookings (check-in/check-out)
Allocate rooms and calculate rent
Handle restaurant orders
Generate final bills

The system ensures data persistence using MySQL, making it more practical than basic file-based systems.

🛠️ Tech Stack
Programming Language: Python
Database: MySQL
Connector: mysql-connector-python
⚙️ Features
👤 Guest Management
Add new guest details (ID, name, address, contact, etc.)
Search existing guests using Guest ID
🛏️ Booking System
Record check-in and check-out dates
Store booking history
💰 Room Rent Calculation
Multiple room categories:
Ultra Royal (₹10,000/day)
Royal (₹5,000/day)
Elite (₹3,500/day)
Budget (₹2,500/day)
Automatic rent calculation based on number of days
🍽️ Restaurant Billing
Menu options:
Vegetarian Combo (₹300)
Non-Vegetarian Combo (₹500)
Veg & Non-Veg Combo (₹750)
Calculates bill based on quantity
🧾 Billing System
Combines:
Room rent
Restaurant bill
Generates final invoice
🗄️ Database Structure

The system automatically creates the following tables in the HMS database:

C_DETAILS → Guest information
BOOKING_RECORD → Check-in/check-out data
ROOM_RENT → Room booking and rent
Restaurant → Food orders
TOTAL → Final billing details
🚀 How to Run
1. Install Dependencies
pip install mysql-connector-python
2. Setup MySQL
Ensure MySQL server is running
Note your username and password
3. Run the Program
python your_file_name.py
4. Enter Credentials
Provide MySQL username and password when prompted
The system will automatically create the database
📋 Menu Options
1 → Enter Guest Details  
2 → Enter Booking Details  
3 → Calculate Room Rent  
4 → Calculate Restaurant Bill  
5 → Display Guest Details  
6 → Generate Total Bill  
7 → Exit  
🧠 Key Concepts Used
MySQL database connectivity
CRUD operations
Modular programming using functions
Global state handling
User input-driven workflows
⚠️ Limitations
Console-based UI (no GUI)
No authentication system
Limited error handling
Uses global variables (not scalable for large systems)
🔮 Future Improvements
Add GUI (Tkinter / Web App)
Implement authentication (admin/staff login)
Improve database normalization
Add online booking support
Integrate payment gateway
👨‍💻 Author

Mayank Pawar
Designed and Developed as an academic project
