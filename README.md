# LILLY STORE SALES ANALYSIS

### Project Overview
The Lily Store sales report provides an overview of the store’s sales performance, customer behavior, order status, payment methods, product categories, regions, age groups, gender distribution, coupon usage, and payment channels.

### Data Source 
Lilly Store sales data: format ".csv" file containing detailed information about the sales made from lilly store.

Type: Retail sales and customer transaction data

Used for: Analysing sales, customers, regions, products, payments, and order status.


### Tools: 

Microsoft Excel, Power query, PivotTables, PivotCharts, Excel Formular, Dashboard, github.

Data availability: The dataset was provided by lilly store to help understand their sales performance.

### Data Cleaning Steps

- Imported the sales dataset into Excel.
- Inspected the available columns and records.
- Checked for missing values.
- Checked for duplicate records.
- corrected inconsistent formating in product category names.
- Checked order status values.
- Checked payment method values.
- Checked customer demographic fields.
- Verified numerical fields such as sales/revenue.
- Converted relevant columns into appropriate data types.
- Created a cleaned dataset for analysis.

### Exploratory Data analysis (EDA)

The sales dataset was explored to understand its structure, identify data-quality issues, and discover patterns in revenue, orders, customers, products, regions, payment methods, and order status before developing the final dashboard.

### Data Analysis 

Total Revenue Generated 

~~~Excel 
=sum(sales[totalsales])
~~~

~~~Cancelled Order
=countif(sales[product_category],sales[order_status],"cancelled")
~~~

### Findings

The store generated a total revenue of ₦4,299,449.11 from 15,120 orders, with an average customer rating of 4.04. Overall, the dashboard indicates a relatively strong and diversified sales performance, although the high number of returned and cancelled orders requires management attention.

#### Key Performance Indicators

- Total Revenue     ₦4,299,449.11 
- Revenue Generated  ₦4,299,449.11
- Total Orders   15,120
- Average Rating    4.04 / 5
- Orders Returned   2,994
- Orders Cancelled  2,976
- Orders Completed  3,035


### Recommendations 

Based on the analysis, Lilly Store should:

1. Reduce order cancellations and returns by investigating common causes such as product quality, delivery delays, incorrect orders, and customer expectations.
2. Strengthen online sales, since online transactions generate the highest revenue among the payment channels.
3. Target customers aged 26–55 with personalized promotions, loyalty programs, and product recommendations.
4. Maintain and expand high-performing categories, particularly Clothing, Household, Sports, and Automotive.
5. Review regional performance** and develop targeted marketing campaigns for lower-performing regions.
6. Evaluate coupon effectiveness by comparing revenue, order frequency, and profitability between coupon and non-coupon orders.
7. Improve customer experience to maintain or increase the current 4.04 average rating.
8. Monitor the relationship between payment method, order status, returns, and cancellations to identify potential operational problems.

### Limitations 

None




