# 💸 CashMeOut — Personal Finance Tracker

CashMeOut is a full-stack personal finance tracker that allows users to monitor their income, expenses, and transaction history in one place. The app focuses on simplicity, speed, and ease of use, while showcasing modern development practices and clean code architecture.

This project was built as a portfolio-grade demonstration of real-world skills in full-stack development.

---

## 🚀 Tech Snapshot (Core Stack Used)

- **React + TypeScript** (Frontend)
- **Node.js + Express + MongoDB** (Backend)
- **Vite** for fast frontend dev
- **Tailwind CSS** for styling

---

## 📊 Features

- 🔐 User authentication and session management (e.g., Clerk)
- ➕ Add income or expense entries with category and date
- 📝 Edit or delete past transactions
- 📆 Filter transactions by category or timeframe
- 📈 Prepare for analytics with dashboard-ready data
- 💡 Mobile-responsive, clean and intuitive UI

---

## 🧰 Full Tech Stack

### ✅ Frontend (`/client`)
- React
- TypeScript
- Vite
- Tailwind CSS
- Axios
- Clerk (or Firebase/Auth0 for auth)

### ✅ Backend (`/server`)
- Node.js
- Express
- TypeScript
- MongoDB (MongoDB Atlas)
- Mongoose
- dotenv

---




## 🎯 Learning Objectives

### Through this project, I aimed to:
- Apply full-stack development using the MERN architecture (with TypeScript)
- Build a scalable folder structure for both client and server
- Understand real-world API design and error handling
- Practice writing clean and typed code in both frontend and backend
- Manage environment configs securely
- Build UI components that are responsive and maintainable

## ⚙️ Local Setup Guide (Yarn + MongoDB)

### 🛠 Prerequisites
- Node.js installed
- Yarn or NPM
- MongoDB (Atlas or local)
- Git

### 1. Clone the repository

```bash
git clone https://github.com/UtkarshTech69/CashMeOut--Personal-finance-tracker.git
cd CashMeOut--Personal-finance-tracker
```
### 2. Setup backend
```bash
cd server
yarn install  # or npm install

# Create a `.env` file:
# MONGODB_URI=your_mongodb_connection_string
# PORT=3001

yarn dev
```

### 3. Setup frontend
```bash
cd ../client
yarn install  # or npm install

yarn dev
```

## 🧠 What I Learned
- 🧩 How to set up a full-stack TypeScript app (React + Node)
- 🧪 How to use Vite for ultra-fast frontend development
- 🧱 Database modeling with Mongoose and MongoDB
- 🧾 Creating reusable API services using Axios
- 🛡 Structuring a clean authentication flow with Clerk/Firebase
- 🎯 Deploy-ready folder organization and development workflow
