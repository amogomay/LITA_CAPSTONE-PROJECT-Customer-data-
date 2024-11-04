# LITA_PROJECT_Customer_data
This repository contains the analysis of customer data with respect to the segmentation of their subscription services

##Project Report: Customer Segmentation for a Subscription Service

##Prepared by: Mary Amogo

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

Total Customers by Region: Determined the number of customers per region, highlighting areas with high user engagement.
Popular Subscription Type: Found the subscription type with the highest number of customers, which is critical for understanding customer preferences.
Early Cancellations (within 6 months): Identified customers who canceled early, which can be valuable for improving retention strategies.
Average Subscription Duration: Calculated across all customers for overall duration trends.
Long-Term Subscribers (>12 months): Filtered customers with long-term subscriptions to analyze loyalty factors.
Revenue by Subscription Type: Aggregated total revenue by subscription type to evaluate revenue-generating segments.
Top Regions by Cancellations: Found the top 3 regions for cancellations, allowing the identification of regions with potential retention challenges.
Subscription Status: Provided counts of active vs. canceled subscriptions to assess overall subscription health.
