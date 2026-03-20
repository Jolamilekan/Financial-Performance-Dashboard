# Financial-Performance-Dashboard

## Project Overview

This project is a web-based financial analytics dashboard that visualizes monthly financial performance and balance sheet information for multiple companies and cost centers.
The dashboard is designed to mimic the clean and interactive layout of modern business intelligence tools such as Power BI.
It enables users to upload financial data in CSV format and instantly generate interactive charts, KPIs, and financial insights.

## Dataset

The dataset contains monthly financial records with the following fields:
- Month
- Company
- Cost Center
- Sales
- COGS
- Operating Expenses
- Taxes
- Depreciation
- Assets
- Liabilities
- Current Assets
- Current Liabilities
Each row represents a financial record for a specific company, cost center, and month.

## Key Metrics Calculated
- The dashboard automatically calculates the following KPIs:

### Revenue
- Total Sales

### Net Profit
- Sales − COGS − Operating Expenses − Taxes − Depreciation

### Gross Margin
- (Net Profit / Sales) × 100

### Current Ratio
- Current Assets / Current Liabilities

### Assets vs Liabilities
- Total Assets compared to Total Liabilities

## Dashboard Pages

### 1. Executive Overview
   #### High-level financial performance indicators.
Includes:
- Total Revenue
- Net Profit
- Gross Margin
- Current Ratio
- Revenue Trend

### 2. Profitability Analysis
#### Breakdown of revenue and expenses.
Includes:
- Profit Trend
- Expense Breakdown

### 3. Balance Sheet
#### Financial health indicators.
Includes:
- Assets vs Liabilities

### 4. Company Ranking
- Compares companies based on revenue.

### 5. Profit Margin Heatmap
- Displays profitability by cost center.

## Features:

- Interactive charts using Chart.js
- CSV file upload for dynamic data updates
- Global filters for Month, Company, and Cost Center
- Multi-page dashboard navigation
- Light and Dark mode toggle
- Automatic KPI calculations

## How to Run the Dashboard:

- Download or clone the repository
- Open the HTML file: financial_dashboard_elite.html
- Upload the provided CSV file
- Interact with the dashboard using filters
- No installation or backend server is required.

## Technologies Used:

- HTML
- CSS
- JavaScript
- Chart.js
- PapaParse (CSV parser)

Author
This project was developed as part of a data analytics and financial modeling portfolio.















