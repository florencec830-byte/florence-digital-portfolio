# Business Income & Expense Tracker

A simple Excel workbook that tracks income and expenses for a small business and calculates profit automatically. Built as a portfolio project for **LORA BEVERAGE**, a fictional juice business.

![Dashboard](dashboard.png)

## Features

- **Income records:** every sale is logged with date, description, category, customer, payment method and amount.
- **Expense records:** every cost is logged with date, description, category, vendor, payment method and amount.
- **Daily summary:** income, expenses and profit for any chosen day.
- **Monthly summary:** income, expenses, profit and profit margin for any chosen month, plus a January to December table.
- **Automatic profit calculation:** Profit = Income - Expenses.
- **Financial dashboard:** summary figures and three charts (income vs expenses by month, monthly profit trend, expenses by category).
- **Dropdown lists:** consistent categories and payment methods through data validation.
- **Conditional formatting:** profit shows green when positive and red when negative.
- **Naira formatting:** all amounts are shown in Nigerian naira (₦).

## Workbook structure

| Sheet | Purpose |
|---|---|
| Dashboard | View financial performance |
| Income | Record money received |
| Expenses | Record money spent |
| Instructions | Learn how to use the workbook |

## How it works

- Income and Expenses are stored as Excel Tables (`tblIncome` and `tblExpenses`), so formulas update automatically when rows are added.
- The Dashboard uses `SUMIFS` and `EOMONTH` to total amounts for the selected day or month.
- Change the month in cell B3 or the day in cell B4 to update the dashboard.

## Example

For 14-Nov-2026 with the original sample data:

| Description | Amount |
|---|---|
| Juice sales | ₦35,000 |
| Fruit purchases | ₦10,000 |
| Bottles and labels | ₦5,000 |
| Transportation | ₦2,000 |
| Other expenses | ₦3,000 |

Profit = ₦35,000 - ₦20,000 = **₦15,000**

## Tools used

- Microsoft Excel / WPS Office
- GitHub

## How to use

1. Download `LORA_Beverage_Financial_Tracker.xlsx`.
2. Add sales on the **Income** sheet and costs on the **Expenses** sheet.
3. Open the **Dashboard** and select the month or day to review.

## Limitations

This is a simplified tracker. Real business profit may also need to account for tax, depreciation, owner's pay and other costs.

## Author

Your Name
Your LinkedIn or contact link
