# Truman Club Delivery 

## Introduction
The Truman Club Delivery platform is a web-based application designed to connect students and clubs for ordering and managing services, with administrative oversight. The system supports three roles:

- **Students**: Place orders for services provided by clubs.
- **Clubs**: Manage services and handle incoming orders.
- **Admins**: Approve club registrations, monitor platform activities, and manage users.

## Technologies Used:
- **Frontend**: React.js
- **Backend**: Node.js with Express
- **Database**: MySQL
- **Authentication**: JWT (JSON Web Token)

## Installation Instructions

### Prerequisites:
1. Install Node.js (LTS version recommended).
2. Install MySQL (Workbench preferred for database setup).

# Clone the Repository
git clone https://github.com/betelhemabebe-beep/Truman-Club-Delivery-App.git
cd Truman-Club-Delivery-App

# Set Up the Backend
cd back
# Open the .env file and configure the database credentials:
# Replace "your_mysql_password" with your actual MySQL Workbench password.
echo "DB_PASSWORD=your_mysql_password" > .env

# Install backend dependencies and start the server:
npm install
npm start

# Set Up the Frontend
cd ../frontend
# Install frontend dependencies and start the client:
npm install
npm start

# Set Up the Database
# Open MySQL Workbench and create the database:
mysql -u root -p -e "
CREATE DATABASE truman_clubs_delivery;
USE truman_clubs_delivery;
"

# Navigate to the db folder in the project directory. For each .sql file, open it in MySQL Workbench and run it:
# Example:
# 1. File > Open SQL Script and select the .sql file.
# 2. Execute the script (click the lightning bolt icon).



