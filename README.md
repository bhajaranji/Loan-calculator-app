# 💸 Loan Calculator App BY ABHINAY KOLKUR

A responsive and themeable Loan EMI Calculator built with **React** and **Material UI**, featuring real-time **currency conversion** using the [ExchangeRate API](https://www.exchangerate-api.com/).

---

## 📌 Project Overview

This web app allows users to calculate monthly EMIs (Equated Monthly Installments) for a loan based on:

* Loan amount
* Interest rate
* Loan duration (in months)
* Currency (auto-converted from USD to selected currency)

The interface supports **light/dark mode toggling** and gracefully handles invalid routes with a 404 page.

## Demo Link: https://proj-loancalculator.netlify.app/

---

## 🧰 Tech Stack

* **React** (v18+)
* **Material UI** (MUI v5)
* **React Router DOM** for routing
* **Axios** for API calls
* **ExchangeRate API** for live currency conversion

---


## 🔑 API Integration

We use the **ExchangeRate API** to fetch live currency rates.

### Example API:

```
https://v6.exchangerate-api.com/v6/your_api_key/latest/USD
```

### Environment Setup:

You can optionally place your key in a `.env` file:

```env
REACT_APP_EXCHANGE_RATE_API_KEY=your_api_key
```

And reference it in code:

```js
const API_KEY = process.env.REACT_APP_EXCHANGE_RATE_API_KEY;
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/bhajaranji/Loan-calculator-app.git
cd loan-calculator-app
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the Development Server

```bash
npm start
```

App will be live at: `http://localhost:3000`

---

## ✅ Features

* 💡 Light/Dark mode toggle
* 🌍 Real-time currency conversion
* 📊 EMI calculation using standard financial formula
* 📱 Responsive MUI layout for mobile/desktop
* 🚫 404 error handling for unknown routes

