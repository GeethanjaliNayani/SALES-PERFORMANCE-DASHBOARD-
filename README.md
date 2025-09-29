****Sales Performance Analytics Dashboard****

This Power BI dashboard provides insights into company sales performance across markets, customers, and products. It tracks key KPIs, revenue trends, and top contributors to help stakeholders make data-driven business decisions.

**Features**
1. KPIs: Total Revenue and Total Sales Quantity.
2. Revenue by Market → Regional sales performance across Indian cities.
3. Customer Analysis → Sales quantity and revenue by customer.
4. Revenue Trend → Monthly revenue trend over multiple years.
5. Top 5 Customers → Highest contributors by revenue.
6. Top 5 Products → Best-selling products by revenue.

**Dataset & Model**
The model follows a Star Schema for efficiency:
1. Fact Table:
   sales_transactions → Contains sales amount, sales quantity, customer, market, product, and date references.

2. Dimension Tables:
     1. sales_products → Product code, product type.
     2. sales_customers → Customer name, customer code, customer type.
     3. sales_markets → Market code, market name, zone.
     4. sales_date → Calendar details (date, month, year).

<img width="1026" height="579" alt="image" src="https://github.com/user-attachments/assets/d5497a1c-7e4f-4991-b920-7c4c0fe0cea7" />


**Documentation**

1. User Guide
 → How to read and navigate the dashboard.

2. Data Dictionary
 → Explanation of dataset fields.

3. Version Log
 → Track changes and updates.

**Tools Used**
1. Power BI → Dashboard creation and visualization.
2. SQL → Data preparation and cleaning.
3. GitHub → Version control and documentation.

**Insights Gained**
1. Delhi contributes the highest sales revenue among all markets.
2. A few customers (e.g., Electricalsara Stores) dominate total revenue.
3. Top-selling products significantly drive revenue concentration.
4. Sales trend shows seasonality with peaks and dips across months.

**How to Use**
1. Clone this repository.
2. Open the .pbix file in Power BI Desktop.
3. Explore insights interactively using year/month filters.

**Versioning**
1. Check version_log.md for release history and updates.
