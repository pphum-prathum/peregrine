# Peregrine — Online Tutor Platform

A web platform connecting tutors and students through profile discovery, 
session booking, and account management.

## Team
- Chanisara Jonsomjid
- Thareerat Phothithum
- Phanphum Prathumsuwan
- Pran Tantipiwatanaskul
- Paranee Wannasorn

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript (Express static server)
- **Backend:** Node.js, Express
- **Database:** MySQL

## Getting Started

### Prerequisites
- Node.js
- MySQL (with MySQL Workbench or equivalent)

### 1. Install dependencies

In the frontend directory:
```bash
cd sec3_gr8_fe_src
npm install express nodemon dotenv
```

In the backend directory:
```bash
cd sec3_gr8_ws_src
npm install express nodemon dotenv mysql2 cors
```

### 2. Configure the database

Create a `.env` file inside `sec3_gr8_ws_src`:
```env
DB_HOST=localhost
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_NAME=peregrine
```

Grant the user privileges in MySQL under **Users and Privileges**.

### 3. Run the project

Open two terminals and run in each:
```bash
npm start
```

Then open your browser and go to `http://localhost:3030`