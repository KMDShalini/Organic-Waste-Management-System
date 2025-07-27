# Organic-Waste-Management-System

📌 Introduction
Organic Waste Management System is a web-based platform designed to help users efficiently submit and categorize their organic waste. It simplifies the process for sellers or individuals to report the type, amount, and moisture content of organic waste, making it easier for municipal or private waste management entities to process and utilize.

🏗️ Project Overview
Key Features:
🌿 Waste Type Classification: Users can select common organic waste types or specify others manually.

🧪 Wetness Measurement Input: Capture the moisture percentage to assist in composting and processing.

⚖️ Weight Input: Enter the weight in kilograms for precise tracking.

📝 Additional Details: Users can leave contact info and comments for further clarification.

✅ Responsive UI: Clean and mobile-friendly interface.

Technology Stack:
Frontend: HTML, CSS, JavaScript

Backend (Optional): PHP (e.g., submit.php for form processing)

Server: XAMPP (Apache & MySQL stack)

📋 How to Use
Setup Instructions:
XAMPP Installation:

Install and open XAMPP.

Start Apache (and MySQL if backend/database is used).

Project Placement:

Copy your project folder (e.g., miniproject) into:

makefile
Copy
Edit
C:\xampp\htdocs\
Access the Web Page:

Open your browser and go to:

arduino
Copy
Edit
http://localhost/miniproject/seller.html
If the page doesn’t open, ensure:

Apache is running.

Your file path is correct.

The file is named seller.html and inside the correct folder.

Optional (Form Handling):

If using submit.php, ensure PHP is correctly set up and connected to a backend handler or database.

🌐 Features
👤 Seller Form:
Select waste category: Wet or Dry

Choose waste type: Fruit, Vegetable, Meat, Dairy, etc.

Optional: Add custom waste type

Input wetness percentage (0-100%)

Input weight in kg

Add contact info and any other notes

🧾 Folder Structure
cpp
Copy
Edit
miniproject/
├── seller.html
├── img1.jpg
├── submit.php (optional)
├── style.css (if separated)
└── ... (other supporting files)
🏆 Contributors
Katikireddy Shalini

[Add other contributors if applicable]

📌 Notes
Ensure the image file img1.jpg exists in the same directory or correct path; otherwise, the background won’t display.

If submit.php is not being used, the form submission won't go anywhere unless handled by JavaScript or another backend method.
