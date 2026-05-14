# Trade AI — AI-Powered Financial Market Dashboard

## Overview

Trade AI is a modern full-stack financial analytics platform built using React, Vite, and Node.js. The application provides real-time stock market visualization, AI-powered trading insights, portfolio analytics, live charts, and an immersive fintech-inspired user experience.

The project focuses on combining modern frontend engineering, interactive UI/UX, and scalable backend architecture into a production-style fintech dashboard.

---

# Features

## Frontend Features

* Real-time stock market dashboard
* Interactive analytics charts
* Portfolio distribution tracking
* AI-powered market insights
* Responsive fintech UI design
* Animated dashboard interactions
* Watchlist management
* Search functionality for stocks
* Modern violet/white theme with blue action buttons
* Mobile responsive layout

---

## Backend Features

* REST API architecture
* Live market data integration
* Financial API integration
* Express.js backend server
* Environment variable support
* Modular backend structure
* API-ready scalable architecture

---

# Tech Stack

## Frontend

* React
* Vite
* JavaScript
* Tailwind CSS
* Framer Motion
* Recharts
* Lucide React

---

## Backend

* Node.js
* Express.js
* Axios
* dotenv
* cors

---

# Project Structure

```bash
trade-ai/
│
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── hooks/
│   ├── utils/
│   ├── context/
│   ├── data/
│   ├── App.jsx
│   └── main.jsx
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── services/
│   ├── middleware/
│   ├── models/
│   ├── config/
│   ├── server.js
│   └── .env
│
├── package.json
├── vite.config.js
└── README.md
```

---

# Installation Guide

## Clone Repository

```bash
git clone https://github.com/your-username/trade-ai.git
```

---

## Open Project Folder

```bash
cd trade-ai
```

---

# Frontend Setup

## Install Frontend Dependencies

```bash
npm install
```

---

## Run Frontend

```bash
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

# Backend Setup

## Go To Backend Folder

```bash
cd backend
```

---

## Install Backend Packages

```bash
npm install express cors dotenv axios
```

---

## Run Backend Server

```bash
node server.js
```

Backend runs on:

```bash
http://localhost:5000
```

---

# Environment Variables

Create:

```bash
backend/.env
```

Add:

```env
API_KEY=your_market_api_key
```

---

# Live Market APIs Used

* Financial Modeling Prep API
* Alpha Vantage API
* Yahoo Finance API
* Polygon.io API

---

# Deployment

## Frontend Deployment

Recommended:

* Vercel
* Netlify

---

## Backend Deployment

Recommended:

* Render
* Railway

---

# Future Improvements

* AI stock prediction engine
* User authentication
* Portfolio management system
* MongoDB integration
* Real-time WebSocket updates
* Dark/light themes
* Trading simulator
* AI chatbot assistant
* CSV upload support
* Live news sentiment analysis

---

# Why This Project Matters

Trade AI demonstrates:

* Advanced React development
* Full-stack architecture
* API integration
* Data visualization
* Dashboard engineering
* Modern UI/UX design
* Financial technology concepts
* Scalable project structure

---

# Resume Description

Built a full-stack AI-powered financial market dashboard using React, Node.js, and Express featuring real-time stock analytics, interactive charts, AI-driven insights, responsive fintech UI, and live market API integration.

---

# GitHub Repository Description

AI-powered financial analytics dashboard built with React, Vite, and Node.js featuring live market visualization, portfolio analytics, and modern fintech UI.

---

# Suggested Screenshots

Add screenshots for:

* Dashboard homepage
* Analytics chart section
* Portfolio distribution
* Watchlist panel
* AI insights section

---

# Author

Developed by Antaran Adhwaryu

---

# License

This project is open-source and available under the MIT License.




# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
