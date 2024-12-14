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

### 1. Clone the Repository
Run the following commands in your terminal:
```bash
git clone https://github.com/betelhemabebe-beep/Truman-Club-Delivery-App.git
cd Truman-Club-Delivery-App

### 2. Set Up the Backend
```bash
cd back
Open the .env file and configure the database credentials:
```bash
DB_PASSWORD=your_mysql_password
(Replace your_mysql_password with your actual MySQL Workbench password.)

Install dependencies:
```bash
npm install
npm start

### 3. Set Up the Frontend
```bash
cd frontend
npm install
npm start

### 3. Set Up the Database
Open MySQL Workbench and create the database:
```bash
CREATE DATABASE truman_clubs_delivery;
USE truman_clubs_delivery;

Navigate to the db folder in the project directory. For each .sql file, open it in MySQL Workbench and run it:

# 1. File > Open SQL Script and select the .sql file.
# 2. Execute the script (click the lightning bolt icon).


