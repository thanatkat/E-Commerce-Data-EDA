# E-Commerce Data EDA with Python
Typically e-commerce datasets are proprietary and consequently hard to find among publicly available data. However, The UCI Machine Learning Repository has made this dataset containing actual transactions from 2010 and 2011. The dataset is maintained on their site, where it can be found by the title "Online Retail".

**Link:** https://lookerstudio.google.com/reporting/0c3da5f8-a28d-4539-9989-4fcc45cdef73

**EDA steps**
- Load Data
- Prints information about the DataFrame
- Change InvoiceDate object to datetime
- Remove duplicate row
- Check missing values: Description, CustomerID
- Replace null value in CustomerID with '00000'
- Fill in missing Description using StockCode
- Put 'Unknown' to missing values on Description column
- I assume negative values in the Quantity are the ones which were cancelled
- Remove negative rows
- Filter the data
  - Find the most popular product: Knowing which products are the most popular can help businesses make informed decisions about inventory management.
  - Find total revenue: Help business to evaluate the effectiveness of promotions and marketing campaigns.
  - Find average order size: Understanding the purchasing behavior of customers.
  - Calculate the total revenue by day: Identifying sales patterns
  - Calculate the order count by week: Understanding the volume of sales over time.
 - Visualization
    - Plot the revenue by day
    - Plot the order count by week

**This dashboard displays:**
- sales metrics
- total sales
- sales by product, country, and date/time

![ecommerce_report](https://user-images.githubusercontent.com/124798930/233296649-0514b3da-2885-47c5-877c-004e4d24b0ed.png)
