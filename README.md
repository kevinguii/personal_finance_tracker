# Expense Tracking Application

This project is a comprehensive expense-tracking application built using the MERN Stack (MongoDB, Express, ReactJS, and Node.js). The application allows users to track their expenses and income, view and analyze their spending habits over time, and make more informed financial decisions.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Authentication:** Secure login and registration functionality.
- **Expense Management:** Create, read, update, and delete expenses.
- **Income Management:** Track income and calculate total net income.
- **Dashboard:** Visualize total income, total expenses, and net balance.
- **Data Persistence:** Efficient data storage using MongoDB.
- **Real-time Updates:** Dynamic and interactive user interface with ReactJS.
- **Time-saving:** Saves 2-5 hours monthly on budget management.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/expense-tracking-app.git
    cd expense-tracking-app
    ```

2. **Install server dependencies:**
    ```bash
    cd backend
    npm install
    ```

3. **Install client dependencies:**
    ```bash
    cd ../frontend
    npm install
    ```

4. **Create a `.env` file in the backend directory and add the following:**
    ```
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

5. **Run the development server:**
    - Backend:
        ```bash
        cd backend
        npm run dev
        ```
    - Frontend:
        ```bash
        cd ../frontend
        npm start
        ```

6. **Open your browser and navigate to:**
    ```
    http://localhost:3000
    ```

## Usage

Once the application is running, you can:
- Register for a new account or log in with existing credentials.
- Add, edit, or delete expense and income entries.
- View your financial dashboard for an overview of your financial health.

## Project Structure
```
expense-tracking-app/
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── .env
│ ├── server.js
│ └── ...
├── frontend/
│ ├── public/
│ ├── src/
│ ├── .env
│ ├── package.json
│ └── ...
└── README.md
```
