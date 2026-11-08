# 🎓 CodeAlpha Java Internship Tasks

- **Intern Name:** Shaik Faheemunnisa
- **Internship:** CodeAlpha Online Java Internship
- **Language:** Java
- **IDE:** Visual Studio Code
- **Requirements:** JDK 8 or higher

---

## 📌 Task 1 - Student Grade Tracker
A console-based Java program that manages student names and their grades.

**Features**
- Add students with their grades
- View all students with letter grades (A, B, C, D, F)
- View summary report with average, highest, and lowest scores
- Input validation for grades

**How to Run**
```bash
cd Task1
javac StudentGradeTracker.java
java StudentGradeTracker
```

**Sample Output**
```text
========================================
     WELCOME TO STUDENT GRADE TRACKER   
========================================

--- MENU ---
1. Add Student
2. View All Students
3. View Summary Report
4. Exit
Enter your choice: 1

Enter student name: Faheema
Enter grade (0-100): 95
Student Faheema added successfully!

--- MENU ---
1. Add Student
2. View All Students
3. View Summary Report
4. Exit
Enter your choice: 2

--- ALL STUDENTS ---
No. | Name         | Grade | Letter Grade
----+--------------+-------+-------------
1   | Faheema      | 95.0  | A

--- MENU ---
1. Add Student
2. View All Students
3. View Summary Report
4. Exit
Enter your choice: 3

===== SUMMARY REPORT =====
Total Students : 1
Average Score  : 95.00
Highest Score  : 95.00 (Faheema)
Lowest Score   : 95.00 (Faheema)
==========================

--- MENU ---
1. Add Student
2. View All Students
3. View Summary Report
4. Exit
Enter your choice: 4

Thank you! Goodbye.
```

---

## 📌 Task 2 - Stock Trading Platform
A console-based Java program that simulates a basic stock trading environment with fixed, simulated prices.

<!-- Uncomment after Stock_Trading_Platform is pushed:
> A more advanced version is in my [Stock_Trading_Platform](https://github.com/Faheema328/Stock_Trading_Platform) repo.
-->

**Features**
- View available market stocks
- Buy stocks with balance deduction
- Sell stocks with profit/loss calculation
- View personal portfolio
- Track overall portfolio performance

**How to Run**
```bash
cd "Task 2"
javac StockTradingPlatform.java
java StockTradingPlatform
```

**Sample Output** *(repeated menus omitted)*
```text
============================================
      WELCOME TO STOCK TRADING PLATFORM     
============================================
Your Starting Balance: Rs. 50000.00

--- MAIN MENU ---
1. View Market Stocks
2. Buy Stock
3. Sell Stock
4. View My Portfolio
5. View Portfolio Performance
6. Exit
Enter your choice: 1

--- MARKET STOCKS ---
Symbol     | Company Name                | Price/Share
-----------+-----------------------------+------------
APPLE      | Apple Inc.                  | Rs. 15000.00
GOOGLE     | Google LLC                  | Rs. 12000.00
AMAZON     | Amazon Inc.                 | Rs. 18000.00
TESLA      | Tesla Inc.                  | Rs. 8000.00
MICROSOFT  | Microsoft Corp.             | Rs. 11000.00
INFOSYS    | Infosys Ltd.                | Rs. 1500.00
TCS        | Tata Consultancy Services   | Rs. 3500.00
RELIANCE   | Reliance Industries         | Rs. 2500.00

Enter your choice: 2

--- BUY STOCK ---
Available Balance: Rs. 50000.00
Enter stock symbol to buy: APPLE
Stock: Apple Inc.
Price: Rs. 15000.0 per share
Enter quantity to buy: 2

========================================
      STOCK PURCHASED SUCCESSFULLY!     
========================================
Stock    : Apple Inc.
Quantity : 2
Price    : Rs. 15000.0
Total    : Rs. 30000.0
Remaining Balance: Rs. 20000.00
========================================

Enter your choice: 3

--- SELL STOCK ---
Enter stock symbol to sell: APPLE
You own 2 shares of APPLE
Enter quantity to sell: 1

========================================
       STOCK SOLD SUCCESSFULLY!         
========================================
Stock      : APPLE
Quantity   : 1
Sell Price : Rs. 15000.00
Amount     : Rs. 15000.00
Profit     : Rs. 0.00
New Balance: Rs. 35000.00
========================================

Enter your choice: 4

--- MY PORTFOLIO ---
Available Balance: Rs. 35000.00
Symbol     | Quantity | Buy Price   | Current Value
-----------+----------+-------------+--------------
APPLE      | 1        | Rs. 15000.00| Rs. 15000.00

Enter your choice: 5

--- PORTFOLIO PERFORMANCE ---
Total Invested    : Rs. 15000.00
Current Value     : Rs. 15000.00
Total Profit      : Rs. 0.00
Available Balance : Rs. 35000.00

Enter your choice: 6

Thank you for using Stock Trading Platform. Goodbye!
```

---

## 📌 Task 3 - Rule-Based Chatbot
A console-based Java chatbot that uses rule-based keyword matching to respond to user queries.

**Features**
- Responds to greetings and general questions
- Answers questions about Java and coding
- Displays current date and time
- Tells jokes
- Default response for unknown inputs

**How to Run**
```bash
cd "Task 3"
javac AIChatbot.java
java AIChatbot
```

**Sample Output**
```text
========================================
        WELCOME TO AI CHATBOT           
========================================
Hi! I am your AI Assistant.
You can ask me anything!
Type 'bye' to exit.

You: Good Morning
Chatbot: Good morning! Have a wonderful and productive day!

You: Hello
Chatbot: Hello! How are you doing today?

You: How are you?
Chatbot: I am doing great, thank you for asking! How about you?

You: What is your name?
Chatbot: I am an AI Chatbot created by Shaik Faheemunnisa for CodeAlpha internship!

You: How old are you?
Chatbot: I am a program, so I do not have an age. But I was created in 2026!

You: What is the weather now?
Chatbot: I cannot check live weather, but I suggest you check weather.com for updates!

You: What time is it?
Chatbot: The current date and time is: Sun Nov 08 12:40:56 IST 2026

You: What do you say about coding in java?
Chatbot: Java is a popular programming language. It is object-oriented and platform independent!

You: Tell me a joke
Chatbot: Why do programmers prefer dark mode? Because light attracts bugs! Ha ha!

You: Bye
Chatbot: Goodbye! Have a great day!
```

---

## 📌 Task 4 - Hotel Reservation System
A console-based Java program that allows users to search, book, and manage hotel rooms.

**Features**
- Search available rooms by category (Standard, Deluxe, Suite)
- Book rooms with payment simulation
- Cancel bookings with refund message
- View all current bookings

**How to Run**
```bash
cd "Task 4"
javac HotelReservationSystem.java
java HotelReservationSystem
```

**Sample Output** *(repeated menus omitted)*
```text
============================================
     WELCOME TO HOTEL RESERVATION SYSTEM    
============================================

--- MAIN MENU ---
1. Search Available Rooms
2. Book a Room
3. Cancel Booking
4. View All Bookings
5. Exit
Enter your choice: 1

--- SEARCH AVAILABLE ROOMS ---
1. Standard  - Rs. 1500/night
2. Deluxe    - Rs. 3000/night
3. Suite     - Rs. 6000/night
4. Show All Available Rooms
Enter your choice: 2

Available Rooms:
Room No. | Category  | Price/Night | Status
---------+-----------+-------------+----------
201      | Deluxe    | Rs. 3000.00 | Available
202      | Deluxe    | Rs. 3000.00 | Available
203      | Deluxe    | Rs. 3000.00 | Available

Enter your choice: 2

--- BOOK A ROOM ---
Enter your name: Faheema
Enter room number to book: 201
Enter number of nights: 1

--- PAYMENT DETAILS ---
Room Number  : 201
Category     : Deluxe
Price/Night  : Rs. 3000.0
Nights       : 1
Total Amount : Rs. 3000.0

Confirm payment? (yes/no): yes

========================================
   BOOKING CONFIRMED SUCCESSFULLY!
========================================
Guest Name   : Faheema
Room Number  : 201
Category     : Deluxe
Nights       : 1
Amount Paid  : Rs. 3000.0
========================================

Enter your choice: 4

--- ALL BOOKINGS ---
Guest Name    | Room No. | Category  | Nights | Total Amount
--------------+----------+-----------+--------+-------------
Faheema       | 201      | Deluxe    | 1      | Rs. 3000.00

Enter your choice: 3

--- CANCEL BOOKING ---
Enter your name to cancel booking: Faheema
Enter room number to cancel: 201

Booking cancelled successfully for Faheema in Room 201
Refund of Rs. 3000.0 will be processed.

Enter your choice: 5

Thank you for using Hotel Reservation System. Goodbye!
```

---

## 🛠️ Technologies Used
- Java
- Object Oriented Programming (OOP)
- ArrayList
- Scanner for user input

## 👩‍💻 Author
- **Shaik Faheemunnisa**
- B.Tech 1st Year
- CodeAlpha Java Internship 2026