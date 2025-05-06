# Coffee Shop Sales Analysis (Excel Project)

## Project Overview

This project presents a comprehensive sales analysis of a coffee shop business using Microsoft Excel. The dataset spans four years (2019–2022) and focuses on product performance, customer behavior, and sales across different countries. Key insights were derived using Excel’s powerful features such as Pivot Tables, Pivot Charts, and functions like `XLOOKUP` and `IF`.

The project aims to uncover patterns in sales and profitability, highlight top-performing products and customers, and offer recommendations for business improvement.


## Data Description

The analysis uses **three primary tables**:

1. **Product Table**
   - `Product ID`, `Coffee Type`, `Roast Type`, `Size`, `Unit Price`, `Price per 100g`, `Profit`

2. **Order Table**
   - `Order ID`, `Order Date`, `Customer ID`, `Product ID`, `Quantity`

3. **Customer Table**
   - `Customer ID`, `Customer Name`, `Email`, `Phone Number`, `Address Line 1`, `City`, `Country`, `Postcode`, `Loyalty Card`

##  Tools Used

- **Microsoft Excel**
  - Pivot Tables
  - Pivot Charts
  - XLOOKUP
  - IF Conditions
  - Data Formatting
  - Excel Tables

## Data Preparation & Cleaning

- Used `XLOOKUP` to merge data from the three tables into one master table.
- Added calculated columns: `Sales`, `Cost`
- Applied `IF` statements to handle null and replace values logically.
- Corrected data types (e.g., dates, currency, numeric formats).
- Converted the merged dataset into a structured Excel table for easy reference in Pivot Tables.

**Final Table Columns:**

Quantity | Customer Name | Country | Loyalty Card | Coffee Type | Coffee Type Name | Roast Type | Roast Type Name | Size | Unit Price | Profit | Sales | Cost

## Exploratory Data Analysis (EDA)

### KPIs Tracked

- **Total Sales**
- **Average Profit**
- **Total Quantity**
- **Total Cost**
- **Count of Sales**

### Slicers Used

- `Roast Type Name`
- `Coffee Size`

## Data Analysis & Insights

- **Top 5 Customers**: Identified using Pivot Table based on total sales.
- **Average Profit by Coffee Type by Year**: Evaluated to determine high-performing products.
- **Count of Sales by Country**: Tracked to assess regional performance.
- **Total Cost by Year**: Measured year-on-year spending.
- **Total Quantity by Country**: UK had the highest quantity sold.
- **Quantity Sold by Coffee Type & Loyalty Card**: Sales were higher among customers without a loyalty card.

## Key Findings

- **Liberia** had the **highest profit consistently** every year.
- The **UK** was the top-performing market by sales volume.
- **Non-loyalty card holders** accounted for the **most sales**.
- **2022** saw the **highest profit** across all years.
- **2022** also recorded the **lowest cost**.

## Recommendations

- Introduce or improve the **loyalty card program** since non-members currently dominate sales—this could help retain customers and boost repeat sales.
- Consider **targeted promotions in Liberia and the UK**, where the business already performs well.
- Focus on **high-profit coffee types** and roast categories from 2022 to sustain or improve profitability.

## Limitations

- The data does not include product return or refund information.
- Analysis was done in Excel; for scalability and automation, Power BI or Python-based analysis could be explored.
