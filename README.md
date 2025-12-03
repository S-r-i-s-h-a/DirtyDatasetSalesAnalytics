Sales Analytics Project (Python + Pandas)

This project performs an end-to-end analysis of a 100,000-record sales dataset using Python.
It includes data cleaning, enrichment using lookup tables, creation of a consolidated Master Sales File, and visual insights such as top customers and top products by revenue.

📌 Project Features
1️⃣ Data Cleaning & Preparation

Date formatting

Handling duplicates & missing data

Feature engineering:

TotalAmount

DiscountedPrice

Month-Year, Monthly Sales

Return flags

High-value orders & suspicious order detection

2️⃣ Lookup Table Creation

Customer Lookup

CustomerName

TotalCustomerOrders

AvgSpend

Region, City, ReturnRate

Product Lookup

Product

Category

AvgProductPrice

Units sold

Product return metrics

3️⃣ Master Sales File

The cleaned dataset is merged with both lookup tables to create a single analytics-ready file containing:

OrderID

OrderDate

CustomerName

Product

Category

Price

Quantity

TotalAmount

Returned

AvgProductPrice

TotalCustomerOrders

4️⃣ Visual Insights

Charts included:

Top 5 Customers by Revenue

Top 5 Products by Revenue

These help identify where revenue is concentrated.
