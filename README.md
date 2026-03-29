Hotel Management System
A Python + MySQL powered backend project for real-world hotel operations

⚡ Quick Summary:
Manage guests, bookings, room allocation, restaurant billing, and generate invoices — all in one system.

🚀 Why This Project Matters

Most beginner projects are CRUD-only.
This one goes further by combining:

Database design
Business logic (billing, booking flow)
Multi-module interaction

👉 It reflects a mini real-world backend system

✨ Core Features
👤 Guest Module

✔ Register new guests
✔ Store complete profile data
✔ Retrieve records instantly

🛏️ Booking Module

✔ Manage check-in / check-out
✔ Maintain booking history

💰 Room Engine

Dynamic pricing system based on room type

Room Type	Price (per day)
Ultra Royal	₹10,000
Royal	₹5,000
Elite	₹3,500
Budget	₹2,500
🍽️ Restaurant Module

✔ Menu-driven ordering
✔ Quantity-based billing

🧾 Billing System

Combines all services into one final invoice

Room Rent + Restaurant Bill = Total Amount
🛠️ Tech Stack
+ Python          → Core logic
+ MySQL           → Data storage
+ mysql-connector → DB integration
🗄️ Database Design

Automatically created on first run

HMS DATABASE
│
├── C_DETAILS        → Guest info
├── BOOKING_RECORD   → Stay records
├── ROOM_RENT        → Room data
├── Restaurant       → Orders
└── TOTAL            → Final bill
⚙️ Setup (Simple & Fast)
1. Install dependency
pip install mysql-connector-python
2. Run project
python your_file_name.py
3. Enter MySQL credentials

✔ Database auto-created
✔ Tables auto-managed

🎮 How It Works
START
  ↓
Enter Guest → Booking → Room → Food → Bill
  ↓
END
📋 Menu Interface
1  → Guest Entry  
2  → Booking  
3  → Room Rent  
4  → Restaurant  
5  → View Guest  
6  → Generate Bill  
7  → Exit  
🧠 What You Learn
Real DB integration
Structured program flow
Multi-module coordination
Backend system thinking
⚠️ Current Limitations

❌ No GUI
❌ Minimal validation
❌ Global variables used
❌ No login/auth

🔮 Future Upgrades

✨ Web App (React / Flask)
✨ Admin Dashboard
✨ Payment Gateway
✨ Better DB normalization

👨‍💻 Author

Mayank Pawar
