# 📈 Stock Portfolio Performance Tracker

## 📌 Project Overview

The **Stock Portfolio Performance Tracker** is a Python-based application that helps users manage their stock investments and monitor portfolio performance. It allows users to add stocks, update current prices, calculate profit or loss, and generate investment summary reports.

The application uses CSV files to store portfolio information permanently, making it easy to retrieve and manage investment data.

## ✨ Features

- **Add Stock:** Add stocks with ticker symbols, purchase prices, and share quantities.
- **Update Stock Price:** Update the current market price of stocks.
- **View Portfolio:** Display all stocks and their investment details.
- **Calculate Performance:** Calculate total investment, market value, profit, and loss.
- **Return Percentage:** Calculate the percentage return on investments.
- **Export Summary:** Generate detailed portfolio reports in CSV format.
- **Remove Stock:** Remove stocks from the portfolio.
- **Save Portfolio:** Store portfolio information in a CSV file.
- **Load Portfolio:** Automatically load previously saved stock information.

## 🛠️ Technologies Used

- Python 3
- CSV Module
- OS Module
- Datetime Module

## 📂 Project Structure

```text
Stock-Portfolio-Tracker/
│
├── main.py
├── portfolio.csv
├── portfolio_summary.csv
└── README.md
```

**Note:** `portfolio.csv` and `portfolio_summary.csv` are generated automatically when the application saves portfolio data or exports a summary.

## ⚙️ Installation and Setup

### Step 1: Install Python

Download and install Python 3 from:

https://www.python.org/downloads/

### Step 2: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 3: Open the Project

Open the downloaded project folder in Visual Studio Code.

### Step 4: Run the Application

Open the VS Code terminal and execute:

```bash
python main.py
```

## 🖥️ Application Menu

```text
1. Add Stock
2. Update Current Stock Price
3. View Portfolio
4. Calculate Performance
5. Export Summary to CSV
6. Remove Stock
7. Save Portfolio
8. Exit
```

## 📊 Performance Calculations

**1. Total Investment**

Total Investment = Purchase Price × Number of Shares

**2. Current Market Value**

Market Value = Current Price × Number of Shares

**3. Profit or Loss**

Profit/Loss = Market Value − Total Investment

**4. Return Percentage**

Return (%) = (Profit or Loss / Total Investment) × 100

## 🎯 Learning Outcomes

- Understanding Python functions and dictionaries.
- Working with CSV files.
- Handling user input and exceptions.
- Performing mathematical calculations.
- Managing data using file handling.
- Developing a menu-driven Python application.

## 🚀 Future Enhancements

- Integrate live stock market prices.
- Add graphical performance charts.
- Implement stock search functionality.
- Add a graphical user interface (GUI).
- Generate detailed investment reports.

## 👩‍💻 Author

**Sneha Reddy Madduri**

## 📄 License

This project is created for educational and learning purposes.
