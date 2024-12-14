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

# Step 1: Clone the Repository
git clone https://github.com/betelhemabebe-beep/Truman-Club-Delivery-App.git
cd Truman-Club-Delivery-App

# Step 2: Set Up the Backend
cd back

# Create and configure the .env file for database credentials
# Replace "your_mysql_password" with your actual MySQL Workbench password
echo "DB_PASSWORD=your_mysql_password" > .env

# Install backend dependencies
npm install

# Start the backend server
npm start

# Step 3: Set Up the Frontend
cd ../frontend

# Install frontend dependencies
npm install

# Start the frontend server
npm start

# Step 4: Set Up the Database
# Open MySQL Workbench or use the MySQL CLI to create the database:
mysql -u root -p -e "
CREATE DATABASE truman_clubs_delivery;
USE truman_clubs_delivery;
"

# Navigate to the 'db' folder in the project directory
# Run each .sql file in MySQL Workbench or use the MySQL CLI to execute:
# Example:
# mysql -u root -p truman_clubs_delivery < path_to_file.sql




