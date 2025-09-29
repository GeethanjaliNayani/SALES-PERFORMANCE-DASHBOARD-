**Fact Table – sales_transactions**
1. currency → Currency of transaction.
2. customer_code → Unique ID for customer.
3. market_code → Unique ID for market.
4. order_date → Date of the transaction.
5. product_code → Unique ID for product.
6. sales_amount → Revenue generated.
7. sales_qty → Quantity sold.

**Dimension Table – sales_products**
1. product_code → Product identifier.
2. product_type → Category/type of product.

**Dimension Table – sales_customers**
1. customer_code → Unique ID for customer.
2. customer_name → Customer’s name.
3. customer_type → Type of customer (e.g., retail, wholesale).

**Dimension Table – sales_markets**
1. markets_code → Unique ID for market.
2. markets_name → Market/city name.
3. zone → Region/zone grouping markets.
  
**Dimension Table – sales_date**
1. cy_date → Calendar date ID.
2. date → Actual date value.
3. date_yy_mmm → Year-month formatted date.

month_name → Month name.

year → Year.
