# 💹 Stock Trading Web App (CS50 Final Project)

This is a Flask-based web application that simulates stock trading. It was developed as the final project for Harvard's CS50x course and demonstrates backend development principles such as user authentication, API integration, database transactions, and templating.

---

## 🚀 Features

- 🔐 User registration and login with password hashing
- 📈 Real-time stock quote lookup via external API
- 💰 Buying and selling stocks with available balance
- 📊 Live portfolio tracking with dynamic updates
- 🧾 Transaction history (buy/sell logs)
- 🚫 Input validation and error handling
- 🔐 Secure session management via Flask-Session

---

## 🛠️ Technologies Used

- **Python 3**
- **Flask** (web framework)
- **SQLite** (relational database)
- **Jinja2** (templating engine)
- **IEX Cloud API** (stock data)
- **HTML/CSS** (frontend templates)
- **Bootstrap 4** (for layout and style)

---

## 📂 Project Structure

```bash
cs50-stock-trading-app/
├── app.py              # Main Flask app
├── helpers.py          # Helper functions (e.g., API lookup)
├── schema.sql          # SQL schema to build the database
├── static/
│   └── style.css       # Optional CSS styling
├── templates/
│   ├── layout.html     # Base layout for all pages
│   ├── index.html      # Portfolio overview
│   ├── login.html
│   ├── register.html
│   ├── quote.html
│   ├── quoted.html
│   ├── buy.html
│   ├── sell.html
│   └── history.html
