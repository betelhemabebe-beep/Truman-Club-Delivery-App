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

### Step 1: Clone the Repository
```bash
git clone https://github.com/betelhemabebe-beep/Truman-Club-Delivery-App.git
cd Truman-Club-Delivery-App
```

### Step 2: Set Up the Backend
```bash
cd back
```

#### Navigate to the .env file in the back folder
Replace "ethbettyabebe" with your actual MySQL Workbench password

#### Install backend dependencies
```bash
npm install
```

#### Start the backend server
```bash
npm start
```

### Step 3: Set Up the Frontend
```bash
cd ../frontend
```

#### Install frontend dependencies
```bash
npm install
```

#### Start the frontend server
```bash
npm start
```

### Step 4: Set Up the Database
 Open MySQL Workbench and New Query Tab
```bash
CREATE DATABASE truman_clubs_delivery;
USE truman_clubs_delivery;
```

#### Navigate to the 'database' folder
 Run each .sql file in MySQL Workbench 

 ## Demo

https://github.com/betelhemabebe-beep/Truman-Club-Delivery-App/tree/master/Videos/student.mp4





