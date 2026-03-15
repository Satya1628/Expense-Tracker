# Capital View – Personal Expense Tracker

Capital View is a modern personal finance tracking web application designed to help users monitor, manage, and understand their financial activity. The goal of the project is to provide a simple yet powerful interface where users can track their income and expenses, visualize spending patterns, and gain insights into their financial behavior.

This application is built entirely using **HTML, CSS, and JavaScript** and runs directly in the browser without requiring a backend server or external database. All financial data is stored locally using the browser's **Local Storage**, ensuring complete privacy and control for the user.

Capital View focuses on simplicity, performance, and accessibility while still providing useful financial insights through visual charts and structured transaction management.

---

# Project Overview

Managing personal finances can often become overwhelming without proper tools. Many applications require cloud storage, subscriptions, or complex setups. Capital View takes a different approach by offering a lightweight solution that works entirely on the client side.

Users can create an account, record financial transactions, categorize expenses, and instantly view summaries of their financial activity. The application also includes visual analytics through charts that help users understand spending habits across different categories and months.

The project demonstrates the use of modern frontend development techniques including interactive UI components, dynamic DOM manipulation, and data visualization.

---

# Key Features

## User Authentication

The application includes a basic authentication system allowing users to create and manage their accounts locally.

Features include:

- User registration
- Login functionality
- Session-based authentication
- Logout capability

User credentials are stored securely within the browser using **Local Storage**, allowing the system to recognize returning users without external authentication services.

---

## Transaction Management

Capital View allows users to manage their financial transactions easily.

Users can:

- Add new income or expense transactions
- Edit existing transactions
- Delete transactions
- Assign categories to expenses
- Record the date, description, and amount for each transaction

Each transaction is saved in the browser's storage, making it instantly accessible when the user logs in again.

---

## Financial Summary Dashboard

The dashboard provides a quick overview of the user's financial situation.

It automatically calculates and displays:

- **Total Income**
- **Total Expenses**
- **Net Cash Flow**

These summaries update dynamically whenever transactions are added, edited, or removed.

---

## Interactive Data Visualization

To help users better understand their financial habits, the application provides interactive charts powered by **Chart.js**.

### Expense Distribution Chart

A doughnut chart displays how expenses are distributed across different categories such as:

- Food & Groceries
- Transport
- Shopping
- Rent
- Bills & Utilities
- Entertainment
- Investments
- Personal Care
- Miscellaneous

This visualization helps users identify where most of their money is being spent.

### Monthly Expense Trend

A second chart shows how expenses change over time.

Users can switch between:

- **Bar Chart View**
- **Line Chart View**

This feature makes it easier to analyze spending trends month by month.

---

## Search and Filtering

The application includes advanced filtering options that allow users to quickly find specific transactions.

Users can filter transactions by:

- Description (search field)
- Month
- Category

This functionality makes it easy to analyze specific spending behaviors or locate past transactions.

---

## Export to CSV

Capital View allows users to export their transaction history as a **CSV file**.

This enables users to:

- Open financial data in Excel
- Perform advanced financial analysis
- Maintain external backups

The exported file includes all transaction details such as date, description, amount, type, and category.

---

## Privacy and Data Ownership

One of the core principles of Capital View is user privacy.

Unlike many financial tools, this application:

- Does not require a backend server
- Does not transmit data to external services
- Stores all information locally within the browser

This ensures that the user has full ownership and control over their financial data.

---

# Technology Stack

The project is built using modern frontend technologies.

### Frontend Technologies

- **HTML5** – structure of the application
- **CSS3** – styling, layout, and responsive design
- **JavaScript (Vanilla JS)** – application logic and interactivity

### Libraries

- **Chart.js** – used to generate interactive financial charts and visualizations

### Data Storage

- **Browser Local Storage**

Local Storage is used to persist user credentials and transaction data directly in the user's browser.

---

# How the Application Works

1. A new user registers an account.
2. The credentials are stored locally in the browser.
3. When the user logs in, their personal transaction data is loaded from Local Storage.
4. Users can add income or expense entries with categories and descriptions.
5. The application processes this data to generate:
   - transaction tables
   - financial summaries
   - interactive charts
6. All updates are automatically saved in the browser.

Because the application runs entirely on the client side, it requires no server infrastructure.

---

# Project Structure

```
Capital-View/
│
├── index.html        # Main application file containing UI, styles, and scripts
├── README.md         # Project documentation
```

All styling and application logic are embedded directly within the HTML file for simplicity and portability.

---

# Application Pages

The application includes three main sections:

### Login / Registration

Allows users to create an account or log in.

### Dashboard

Displays:

- financial summaries
- expense distribution charts
- monthly spending trends

### Transactions Page

Allows users to:

- add transactions
- edit transactions
- delete transactions
- search and filter financial records

### About Page

Provides information about the project and the development team.

---

# Developer Team

**Developer Team: Alpha**

Team Members:

- Nayanesh Uppu
- Satyanarayana Reddy

This project was developed as part of a learning initiative to explore frontend web development and financial data visualization.

---

# Future Improvements

Although Capital View provides a solid foundation for personal expense tracking, several enhancements could improve the system further.

Possible improvements include:

- Backend integration using Node.js or Firebase
- Cloud-based data synchronization
- Mobile-friendly responsive layout
- Budget planning and spending alerts
- AI-based financial recommendations
- Dark mode support
- Multi-user financial dashboards

These additions could transform the project into a fully featured financial management platform.

---

This project is created for educational and portfolio purposes.  
You are free to explore, modify, and improve the project for learning or personal use.
