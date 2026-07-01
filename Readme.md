# Crypto & Currency Converter Dashboard

## Project Description

The Crypto & Currency Converter Dashboard is a web application developed using HTML, CSS, and JavaScript. It provides a secure login system, real-time currency conversion, cryptocurrency market insights, historical Bitcoin price visualization, and personalized favorite currency pairs for each user.

This project demonstrates API integration, local storage management, user authentication, DOM manipulation, and data visualization using Chart.js.

---

## Features

### 1. User Authentication
- Login system using a local JSON file (`user.json`)
- Username and password verification
- Redirects authenticated users to the dashboard
- Prevents unauthorized access to the dashboard

### 2. Currency Converter
- Convert between multiple currencies:
  - USD
  - INR
  - EUR
  - GBP
  - JPY
  - AUD
  - CAD
- Fetches live exchange rates using an external API
- Displays conversion results instantly

### 3. Personalized Favorite Pairs
- Save favorite currency pairs
- Favorites are stored separately for each user
- Uses Local Storage for persistence

### 4. Cryptocurrency Historical Chart
- Displays Bitcoin price history for the last 7 days
- Uses real-time data from CoinGecko API
- Visualized using Chart.js

### 5. Session Management
- Stores logged-in username using Local Storage
- Logout functionality clears the session
- Redirects users back to the login page

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- JSON
- Local Storage
- Fetch API
- Chart.js

---

## APIs Used

### Exchange Rate API
Used for real-time currency conversion.

Example Endpoint:

https://api.exchangerate-api.com/v4/latest/USD

### CoinGecko API
Used for fetching Bitcoin historical price data.

Example Endpoint:

https://api.coingecko.com/api/v3/coins/bitcoin/market_chart?vs_currency=usd&days=7

---

## Project Structure

```text
CRYPTO_PROJECT
│
├── index.html
├── dashboard.html
├── user.json
└── README.md
```

---

## Login Credentials

### Admin Account

```text
Username: admin
Password: password123
```

### Student Account

```text
Username: student
Password: jsbasic2026
```

---

## How to Run the Project

1. Open the project folder in Visual Studio Code.
2. Ensure the following files are present:
   - index.html
   - dashboard.html
   - user.json
3. Install the Live Server extension.
4. Right-click on `index.html`.
5. Select **Open with Live Server**.
6. Login using one of the credentials provided in `user.json`.

---

## Functionalities Implemented

- JSON-based Login Authentication
- Dashboard Access Control
- Real-Time Currency Conversion
- API Integration using Fetch API
- Historical Bitcoin Price Chart
- Local Storage Management
- Personalized Favorite Currency Pairs
- Logout Functionality
- Responsive User Interface

---

## Learning Outcomes

This project helped in understanding:

- API Integration
- Asynchronous JavaScript
- JSON Data Handling
- User Authentication
- Local Storage
- DOM Manipulation
- Data Visualization with Chart.js
- Responsive Web Design

---

## Future Enhancements

- Add more cryptocurrencies (Ethereum, Solana, etc.)
- Dark Mode support
- User Registration page
- Remove favorite pair functionality
- Searchable currency list
- Multi-currency comparison charts

---

## Author

Mini Project developed for learning JavaScript, API Integration, Local Storage, and Data Visualization concepts.