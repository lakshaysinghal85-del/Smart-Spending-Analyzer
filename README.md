# 💰 SpendWise – Smart Spending Analyzer

SpendWise is a web-based personal finance management application developed to help users track their daily expenses, manage income, analyze spending patterns, and maintain better control over their finances. It provides a centralized dashboard for viewing financial summaries, managing transactions, setting monthly budgets, and analyzing bank statements.

## 🎯 Objectives

- Record and manage daily income and expenses.
- Organize transactions using different categories.
- Analyze spending patterns through visual charts.
- Monitor monthly budgets and spending limits.
- Import and analyze bank statements.
- Generate useful financial insights.
- Store financial records using an SQLite database.

## ✨ Features

- **Dashboard:** Displays total spending, total income, net balance, and recent transactions.
- **Transaction Management:** Add, view, update, and delete income and expense records.
- **Spending Analytics:** Visualize expenses through charts and category-wise breakdowns.
- **Monthly Budgets:** Set spending limits for different categories.
- **Smart Insights:** Displays spending observations, largest expenses, and budget alerts.
- **Bank Statement Analysis:** Upload CSV and Excel bank statements to analyze income, expenses, and transaction history.
- **Password-Protected Excel Support:** Analyze password-protected Excel workbooks using the correct password.
- **Financial Summary:** Calculates total income, total expenses, and net balance.
- **Database Integration:** Stores and manages transaction records using SQLite.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python 3.11 | Backend programming |
| Flask | Backend framework and API development |
| SQLite | Database storage |
| SQL | Database operations |
| Pandas | Data processing and analysis |
| HTML | Web page structure |
| CSS | User interface design |
| JavaScript | Frontend interactions |
| Plotly / Charts | Financial data visualization |
| OpenPyXL | Excel file reading |
| Msoffcrypto-tool | Password-protected Excel support |

## 🏗️ System Architecture

The application follows a client-server architecture.

- **User Interface:** HTML, CSS, and JavaScript provide the interactive dashboard.
- **Application Layer:** Python and Flask handle application logic and API requests.
- **Data Processing Layer:** Pandas processes financial records and bank statement data.
- **Database Layer:** SQLite stores transaction and financial records.
- **Visualization Layer:** Charts display spending patterns and financial summaries.

## 🗄️ Database Design

The project uses SQLite as its database management system.

The transaction records contain:

- Transaction ID
- Transaction name or description
- Amount
- Category
- Transaction date
- Transaction type (Income or Expense)

SQL operations are used to:

- **INSERT:** Add new transaction records.
- **SELECT:** Retrieve existing records.
- **UPDATE:** Modify transaction information.
- **DELETE:** Remove unwanted records.

## ⚙️ Prerequisites

- Python 3.11
- Visual Studio Code
- Flask
- Pandas
- SQLite
- OpenPyXL
- Msoffcrypto-tool
- A modern web browser

## 🚀 Setup and Installation

1. Clone or download the project repository.
2. Open the project folder in Visual Studio Code.
3. Create and activate a Python virtual environment.
4. Install the required Python packages.
5. Initialize the SQLite database.
6. Start the Flask backend:

   ```bash
   python backend/app.py
   ```

7. Open the frontend in your browser.
8. Start adding transactions and exploring the financial analysis features.

## 🔒 Security Notes

- Excel passwords are used only for the statement analysis request.
- Do not upload real bank statements containing sensitive personal information to a public repository.
- Do not commit database passwords, private financial records, or environment variables.
- Use sample financial data for demonstrations and testing.

## 🎓 Project Information

- **Project Name:** SpendWise – Smart Spending Analyzer
- **Student:** Lakshay
- **UID:** 26MCD10093
- **Program:** Master of Computer Applications (MCA) – Data Science
- **Section:** B
- **Semester:** 1st Semester
- **University:** Chandigarh University
- **Academic Session:** 2026–27
- **Project Type:** Python Mini Project

## 🔮 Future Scope

- Integrate Google authentication for individual user accounts.
- Support additional bank statement formats.
- Improve automatic transaction categorization.
- Generate downloadable monthly and yearly financial reports.
- Introduce advanced spending predictions.
- Add recurring expense reminders.
- Support multiple user profiles.

---

**SpendWise — Track your money, understand your spending, and make smarter financial decisions.**