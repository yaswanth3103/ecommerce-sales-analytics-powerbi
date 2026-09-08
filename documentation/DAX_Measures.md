DAX Measures

This document lists the DAX measures created for the E-Commerce Sales Analytics Dashboard.

1. Total Sales

DAX: Total Sales = SUM(Sales_Data[Sales])

Purpose: Calculates total revenue generated from sales.

2. Total Profit

DAX: Total Profit = SUM(Sales_Data[Profit])

Purpose: Calculates total profit generated from sales.

3. Total Quantity

DAX: Total Quantity = SUM(Sales_Data[Quantity])

Purpose: Calculates the total number of units sold.

4. Profit Margin %

DAX: Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

Purpose: Measures profitability relative to total sales.

Format: Percentage, 2 decimal places.

5. Average Discount

DAX: Average Discount = AVERAGE(Sales_Data[Discount])

Purpose: Calculates the average discount applied across sales transactions.

Format: Percentage, 2 decimal places.

Measure Design

The dashboard uses DAX measures for key business metrics so that the calculations respond dynamically to filters and slicers applied to the report.

The measures are stored in the Sales_Data table in the Power BI model.
