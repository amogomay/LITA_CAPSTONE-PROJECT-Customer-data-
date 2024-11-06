# LITA_PROJECT_Customer_data
This repository contains the analysis of customer data with respect to the segmentation of their subscription services

## Project Report: Customer Segmentation for a Subscription Service

## Prepared by: Mary Amogo

## Project overview
This project aims to analyze customer data from a subscription service to identify key customer segments and subscription trends.
The goal is to understand customer behavior, track subscription types, and detect patterns in cancellations and renewals.
An interactive Power BI dashboard was used to presents insights into customer segmentation, subscription trends, and key metrics.

## Methodology
 Data Analysis Tools Used:
 Excel: For initial data exploration and pivot table analysis.
 SQL: For advanced querying and extraction of key metrics.
 Power BI: For data visualization and interactive dashboard creation.

### Excel Analysis
 1 The data set was cleaned in excel by removing duplicates.

 2 Created pivot tables to analyze subscription patterns by type, duration, and other factors.
 
 3 Calculated the average subscription duration.
 
 4 Identified the most popular subscription types based on the number of active users.

### Findings:
 - Average Subscription Duration by Subscription by type

![Average sub duration](https://github.com/user-attachments/assets/dee7b089-8245-4072-9f96-f415370fd473)


 - Popular Subscription Types: The most popular subcription type based on revenue generated

[![image](https://github.com/user-attachments/assets/1bb40615-a701-4f82-8e02-2f6c6dc5d0f1)
].

From the report above, we discoverd that  Basic is the most popular subscription with a total revenue of N33.78 Million

 - Revenue by Region

![image](https://github.com/user-attachments/assets/d7390ab4-5b5a-4b4d-9808-84a784e3bca6)

From our findings, the region with the highest revenue is East with the total revenue of N16.95Million


### SQL Analysis
Queries and Key Insights:

Total Customers by Region: 

```SQL
SELECT Region, COUNT(CustomerID) AS Total_Customers
FROM [dbo].[CUSTOMER_DATA]
GROUP BY Region;
```

Popular Subscription Type: 
```SQL
SELECT SubscriptionType, COUNT(CustomerID) AS Customer_Count
FROM [dbo].[CUSTOMER_DATA]
GROUP BY SubscriptionType
ORDER BY Customer_Count DESC
LIMIT;
```

Revenue by Subscription Type: 
```SQL
SELECT SubscriptionType, SUM(Revenue) AS Total_Revenue
FROM [dbo].[CUSTOMER_DATA]
GROUP BY SubscriptionType;
```
