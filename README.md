# Zero-Based Budgeting App

A **Python desktop application** for managing your personal finances using the **Zero-Based Budgeting** principle:  
> **Income – (Expenses + Savings) = 0**  
Every rupee is assigned a purpose — nothing is left unallocated.

Built with **Tkinter** for the interface and **SQLite** for data storage, this app helps you track incomes, expenses, and savings in real time.

---

## Features

- Add & Manage income, expenses, and savings  
- Real-Time Budget Status: See if you’ve completed or overspent your budget  
- Export & Import data in CSV or Excel format  
- Clear/Delete entries individually or in bulk  
- View Totals for each category  
- Validations for cleaner and more accurate data entry  
- Persistent Storage using SQLite database  
- Zero-Based Budgeting Formula enforcement

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/zero-budget-app.git
cd zero-budget-app
```

### 2. Install Dependencies
Make sure Python 3.x is installed, then:
```bash
pip install pandas openpyxl xlsxwriter
```

### 3. Run the App
```bash
python zero_budget_app_1.5.py
```

---

## Screenshots
*(Add screenshots of the interface here)*

---

## Tech Stack

- **Python 3.x**
- **Tkinter** – GUI framework  
- **SQLite** – Lightweight database  
- **Pandas** – CSV/Excel export/import  
- **OpenPyXL** / **XlsxWriter** – Excel support  

---

## Export & Import

- **Export**: Save data as `.csv` or `.xlsx`  
- **Import**: Load `.csv` or `.xlsx` with matching column structure  
- Import validation ensures correct format for each table:  
  - **Income**: id, name, amount  
  - **Expense**: id, name, category, amount  
  - **Saving**: id, name, amount  

---
