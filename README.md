# 📈 React Stock Dashboard

**React Stock Dashboard** is a modular, high-performance frontend application built with **React**, **TypeScript**, and **Tailwind CSS**, designed to visualize **real-time stock data** retrieved from the [Alpha Vantage API](https://www.alphavantage.co/). It supports multiple rendering strategies — basic, virtualized, and paginated tables — and demonstrates best practices in UI responsiveness, routing, and performance optimization.

---

## 📚 Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Development](#development)
- [Testing](#testing)
- [Live Demo](#live-demo)
- [Further Improvements](#further-improvements)

---

## 🚀Introduction

This project implements a stock market dashboard using:

- **React + TypeScript** for component-based architecture and type safety
- **Tailwind CSS** for modern and responsive UI styling
- **Alpha Vantage API** for fetching 5-minute time series stock data
- **React Router** for SPA-style navigation
- **Custom table components** to demonstrate performance-aware rendering (virtualized, paginated)

### Key Features:

✅ Select stock symbols via dropdown  
✅ View real-time data in three modes:  
- **Basic Table**  
- **Virtualized Table**  
- **Paginated Table**

✅ Optimized performance with `useDeferredValue`  
✅ Graceful API error handling (e.g., rate limits)  
✅ Clean modular codebase with reusable UI components

---

## 🛠Technologies Used

- ⚛️ **React 18** – UI framework
- 🟦 **TypeScript** – Static typing
- 🌐 **React Router v6** – Page routing
- 🎨 **Tailwind CSS** – Utility-first CSS framework
- 📊 **Alpha Vantage API** – Stock market data source
- 📦 **Vite** or **CRA** – Build tool (depending on setup)
- 🧠 **React Hooks** – `useState`, `useEffect`, `useCallback`, `useDeferredValue`
- 🧪 (Optional) Jest – Unit testing

---

## ⚙️Setup and Installation

Clone the repository and run the app locally:

```bash
git clone https://github.com/ZeynabLiraki/Stockdashboard.git


# Install dependencies
npm install

# Start development server
npm start
Open your browser at:
🔗 http://localhost:3000/



🚀 Live Demo
🔗 View the Live App
(Replace with actual link when deployed to Vercel, Netlify, etc.)

🔮 Further Improvements
✨ Add charting (e.g., ECharts, Chart.js) to visualize trends
🌓 Add dark/light mode toggle
📦 Integrate React Query or SWR for better data caching
💾 Add localStorage or backend to persist selected symbol
🧪 Increase test coverage with integration/e2e tests
⚙️ Add loading spinners and skeletons for better UX

👩‍💻 Author
Zeynab Liraki
Frontend Developer – React | TypeScript | Real-Time Data
📍 Based in Vienna


