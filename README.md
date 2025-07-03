# Sales Insights Data Analysis Project
A **Power BI** and **SQL**- integrated sales data analysis project simulating real-time business insights for a computer hardware company facing dynamic market challenges.

## **Overview**

This project simulates a real-world business scenario where a computer hardware company is struggling to maintain sales performance in a rapidly changing market. The Sales Director has commissioned a data analysis initiative to gain deeper visibility into customer behavior, regional performance, product demand, and revenue trends. Using **SQL** for data extraction and **Power BI** for visualization, this project aims to deliver actionable insights to support strategic decisions.

## **Objective**

To analyze historical sales data to uncover trends, identify underperforming areas, and help the leadership team make data-driven decisions through interactive Power BI dashboards and SQL queries.

## **Business Problem**

The company operates in a competitive computer hardware market and lacks real-time visibility into its sales performance. Key challenges include:
- Fluctuating revenue across regions
- Uncertainty around top-performing products
- Lack of clarity on customer purchasing patterns
- Inability to quickly respond to market changes due to delayed insights

The goal is to centralize and analyze data from different sources (sales, customers, products, and calendar) and deliver a dashboard that helps stakeholders:
- Track revenue performance
- Understand sales by region and time period
- Compare sales in multiple currencies
- Identify key contributors and bottlenecks

## **Tools and Technologies Used**

- **MySQL** for data querying and manipulation  
- **Power BI** for interactive dashboards and data transformation  
- **Excel** for initial data checks  
- **SQL** for business logic and metric calculations  

## **Data Model**

The database contains the following tables:
- `customers`: Customer demographics and IDs
- `transactions`: Sales transaction data including product, market, amount, and currency
- `products`: Product-level information
- `date`: Date dimension with year, month, day, and derived fields

## Business Questions

This project was designed to answer key business questions that help the company better understand its sales performance, customer behavior, and product demand. The following questions guided the analysis:

- What is the total number of customers in the database?
- How are sales distributed across different regions or markets?
- Which products generate the most revenue?
- What are the monthly and yearly sales trends?
- What is the total revenue generated in 2020?
- How does revenue vary by market (e.g., Chennai vs others)?
- How many transactions occurred in USD, and what is their impact on total revenue?
- Which months had the highest and lowest sales?
- What are the top-performing customers based on revenue?
- How does normalizing currency (USD to INR) impact overall revenue analysis?
- What percentage of revenue comes from repeat customers (if customer data allows)?
- Are there seasonal patterns in sales?
- What is the revenue contribution of each product category or product code?


## Key Insights

The analysis provided several actionable insights that can guide the company’s strategic decisions:

- Chennai emerged as one of the top-performing markets in terms of total revenue.
- Sales peaked in the months of January and December, indicating seasonal buying patterns.
- Transactions in USD had significant contribution, requiring normalization for accurate comparison.
- After currency normalization, overall revenue trends became clearer and more comparable.
- A small number of products contributed to a large percentage of total sales, highlighting the importance of focusing on high-performing SKUs.
- Customers with repeat transactions showed a higher average sales value, suggesting strong brand loyalty.
- Market-wise sales trends indicated opportunities for expansion in underperforming regions.
- The interactive Power BI dashboard enabled leadership to monitor KPIs and sales metrics in near real-time.

