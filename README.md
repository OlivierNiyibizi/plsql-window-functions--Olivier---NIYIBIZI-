# plsql-window-functions--Olivier---NIYIBIZI-

## problem definition 

The problem of business scenario is DATA Challenge Our analysis needs to identify the top 3 best-selling products by revenue within each sales region for the last quarter. The problem we have is that we have to rank products within their specific regions, not globally.  Also we need to calculate the total revenue of each product.
 Here there are the business context
Company Type: (Niyibizi Tech solutions) a multinational electronics retailer 
Departments: Marketing & inventory management 
Industry:  E-commerce & Retail.What this business context are expected to help the business For Marketing Department: the target is to list the top-performing products per region to focus on localized digital advertising campaigns and promotional offers.
For Inventory Management Department: the Data to validate and optimize regional warehouse stock levels, ensuring high availability for top sellers while reducing overstock of slower-moving items

## Success Criteria 

1.	Top 5 products per region/quarter → RANK (): we use this to identify the best-selling electronics items in each region every quarter 
2.	2. Running monthly sales totals → SUM () OVER (): we will use this to calculate cumulative monthly sales totals to truck growth.3.	Month-over-month revenue growth per product → we will apply LAG ()/LEAD () to compare each products revenue against the previous month and compare growth %
4.	Customer segmentation by spend classify customers into 4 quartiles (25% groups) with NTILE (4) based on lifetime electronics purchases.
5.	3-month moving average sales per product use → AVG () OVER () to smooth fluctuations in electronics sales trends 


