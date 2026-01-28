# Transactions-Node-Api

A simple REST API built with **Node.js** and **TypeScript** to practice backend development concepts.  
The project simulates a financial transaction system where clients can perform **credit** and **debit** operations and check their balance.

---

## 📌 About the Project

This API allows:

- Creating clients
- Performing credit transactions
- Performing debit transactions
- Viewing transaction history
- Checking client balance

The main goal of this project is to practice:

- TypeScript with Node.js
- REST API structure
- Business logic implementation
- Database migrations and organization

---

## 🚀 Technologies Used

- Node.js
- TypeScript
- Express
- Knex (Query Builder)
- SQLite / PostgreSQL (depending on configuration)
- ts-node-dev (development)

---

## 📂 Project Structure

src/
├── controllers/
├── routes/
├── db/
│ ├── migrations/
├── middlewares/
└── server.ts

Main configuration files:

- `knexfile.ts`
- `.env`
- `package.json`
- `tsconfig.json`

---

## ⚙️ Installation

### 1. Clone the repository

git clone https://github.com/JoaoVictorMartins05/Transactions-Node-Api.git

2. Navigate into the project folder
cd Transactions-Node-Api

3. Install dependencies
npm install

4. Configure environment variables

Copy the example file (if available):

cp .env.example .env


Then configure your database settings inside the .env file.

🗃️ Run Database Migrations

Before starting the server, run:

npm run knex -- migrate:latest

▶️ Running the Application
Development mode
npm run dev
