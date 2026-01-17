# 📈🚀 StockTradePro – Full Stack Fintech Trading Platform
A modern, production-style stock trading platform inspired by Upstox

---

## 🌟 Overview

- StockTradePro is a full-stack fintech web application that simulates a real-world stock trading platform.
- Users can securely register, explore stock market data, buy and sell stocks, manage portfolios and watchlists, and track complete transaction history.
- The project is built with modern frontend and backend architectures, focusing on clean code, scalability, security, and real-world trading logic.
- ⚠️ Market prices are simulated via backend logic to mimic real trading behavior without relying on paid third-party APIs.

---

## 📁 Repository Structure (Important)

This is the **parent repository** for StockTradePro.

- The `frontend/` and `backend/` folders in this repository are **Git submodules**.
- Clicking them will redirect to their respective GitHub repositories.
- Full source code, commits, and history are maintained in those repositories.

---

## 🔗 Project Repositories
### 🖥️ Frontend (React + Redux + Tailwind)

👉 **[https://github.com/aditya32193213/stocktradepro-frontend](https://github.com/aditya32193213/stocktradepro-frontend)**

### 🛠️ Backend (Node.js + Express + MongoDB)

👉 **[https://github.com/aditya32193213/stocktradepro-backend](https://github.com/aditya32193213/stocktradepro-backend)**

---

## 🌐🚀 Live Deployment

### Frontend (Vercel)
👉 **[https://stocktradepro-frontend.vercel.app/](https://stocktradepro-frontend.vercel.app/)**

### Backend (Render)
👉 **[https://stocktradepro-backend.onrender.com/](https://stocktradepro-backend.onrender.com/)**

### Swagger API Docs
👉 **[https://stocktradepro-backend.onrender.com/api-docs](https://stocktradepro-backend.onrender.com/api-docs)**

---

## 🎥 Demo Video
👉 **[https://drive.google.com/file/d/1dp0UI6vS5NAvLS0D4DkQ2Sd_xJomQXfh/view?usp=sharing](https://drive.google.com/file/d/1dp0UI6vS5NAvLS0D4DkQ2Sd_xJomQXfh/view?usp=sharing)**


## 🎯 Core Features

- 🔐 Authentication & Security
- 👤 Secure user registration (Email, Mobile, PAN validation)
- 🔑 JWT-based authentication
- 🛡️ Protected routes (frontend & backend)
- 🔒 Password hashing using bcrypt
- 🚦 Rate limiting & secure headers (Helmet)
- 📈 Stock Market
- 🔍 Search stocks by name or symbol
- 🏷️ Filter by sector
- 📄 Pagination support
- 📊 Simulated live price metrics (price, change %, volume, P/E, market cap)
- 📉 Stock Detail Page
- 📊 Interactive price charts
- 🏢 Company details
- 🟢 Buy / 🔴 Sell stock with quantity validation
- ⭐ Add / remove from watchlist
- 💼 Portfolio & Dashboard
- 💰 Available balance
- 📦 Current holdings
- 📈 Invested vs market value
- 📉 Profit / Loss calculation
- 🧭 Dashboard market summary
- 💸 Trading System
- 🟢 Buy stocks with balance validation
- 🔴 Sell stocks with ownership checks
- 🔄 Atomic balance & transaction updates
- ❌ Prevent overspending / overselling
- 🧾 Transaction History
- 📜 Complete buy/sell history

### 🔎 Filter by:
- Type (BUY / SELL)
- Date range
- Stock

### 📤 Export transactions:
- 📄 PDF
- 📑 CSV

- ⭐ Watchlist
- ➕ Add stocks
- ➖ Remove stocks
- 🚫 Prevent duplicates
- 👤 User-specific lists
- 🎨 User Experience
- 📱 Fully responsive (mobile-first)
- 🎉 Toast notifications
- ⏳ Skeleton loaders
- 🧩 Clean, intuitive UI
- 🌓 Light/Dark theme ready (planned)

---
  
## 📸 Screenshots

###📂 Screenshots are available in the frontend repository under /screenshots

Includes:

- 🏠 Landing Page
- 📝 Register
- 🔐 Login
- 📊 Dashboard
- 📈 Stock Market
- 📉 Stock Detail
- 💼 Portfolio
- 🧾 Transactions
- 🧾 PDF Export
-ℹ️ About & FAQ

---

## 🛠️ Tech Stack

### Frontend

- ⚛️ React + Vite
- 🔄 Redux Toolkit & Thunk
- 🎨 Tailwind CSS
- 🛣️ React Router
- 📊 Recharts
- 🌐 Axios

### Backend

- 🟢 Node.js (ESM)
- ⚡ Express.js
- 🍃 MongoDB + Mongoose
- 🔐 JWT Authentication
- ✅ express-validator
- 🛡️ Helmet, Rate Limiting
- 📄 Swagger (OpenAPI)

---

### 🧪 Testing

###Frontend
- ⚡ Vitest
- 🧩 React Testing Library
- 🧠 jsdom

### Backend

- 🧪 Jest
- 🔬 Supertest (basic coverage)

---

### 📁 Architecture Overview

```plaintext
Client (React)
   ↓
Redux Store
   ↓
REST APIs
   ↓
Express Controllers
   ↓
MongoDB
```

---

### 📄 API Highlights

- POST /api/v1/auth/register
- POST /api/v1/auth/login
- GET /api/v1/stocks
- GET /api/v1/stocks/:id
- POST /api/v1/transactions/buy
- POST /api/v1/transactions/sell
- GET /api/v1/transactions
- GET /api/v1/transactions/export/pdf
- GET /api/v1/watchlist
- POST /api/v1/watchlist

---
  
### 📘 Full documentation available via Swagger UI

- 🧠 Market Data Strategy

To avoid dependency on paid or restricted APIs:

-  📦 Stock data is seeded into MongoDB
- 🔁 Prices fluctuate via backend logic
- 📊 Enables realistic trading simulations
- ✅ Fully API-driven & deterministic

---

### 🚀 Future Enhancements

- 📡 Real-time updates via WebSockets
- 🧑‍💼 Role-based access (RBAC)
- 💳 Wallet top-up (Stripe)
- 🔐 Google OAuth 2.0
- 📊 Advanced analytics dashboard
- ⚡ Redis caching

---
  
### 👨‍💻 Author

Aditya
🚀 Full Stack Developer
📍 Bangalore, India 🇮🇳

---

### ⭐ Final Note

This project was built to reflect real-world fintech engineering standards, not just to pass a capstone.

If you find this useful, please ⭐ the repositories!
