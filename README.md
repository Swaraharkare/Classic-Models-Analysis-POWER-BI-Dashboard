# Project Title: Classic-Models-Analysis-POWER-BI-Dashboard

<img width="1156" height="656" alt="image" src="https://github.com/user-attachments/assets/87249d94-2dda-4636-b373-7cbc86f3301f" />

## Overview
A comprehensive Power BI dashboard analyzing the **Classicmodels dataset**. This project explores sales trends, customer behavior, product performance, and employee efficiency within a simulated model car retailer business.

## Business Questions Answered
*   Which product lines generate the highest revenue?
*   Which employees are the top performers based on sales figures?
*   Where are our most valuable customers located, and what are their order patterns?
*   How do payments and order statuses correlate with sales cycles?

## Data Sources
The project utilizes the following standard CSV files from the Classicmodels database schema:

*   `**customers.csv**`: Contains customer information (names, contact details, credit limits).
*   `**employees.csv**`: Contains employee data and reporting structure.
*   `**offices.csv**`: Contains sales office locations and contact information.
*   `**order details.csv**`: Contains line-item details for each order (product code, quantity, price).
*   `**orders.csv**`: Contains main order information (order number, dates, status, customer number).
*   `**payments.csv**`: Contains records of customer payments.
*   `**productlines.csv**`: Contains categories and descriptions for product lines.
*   `**products.csv**`: Contains detailed product information (scale, vendor, price).

## Key Metrics & Calculations
Mention some of the key measures and calculations (DAX) you created.

*   **Total Sales:** Sum of the calculated price for each item sold.
*   **Average Order Value:** Total Sales / Count of unique orders.
*   **Sales per Employee:** Total Sales attributed to specific sales representatives.
*   **Customer Lifetime Value (CLV):** (Average Purchase Value) * (Number of Purchases) * (Customer Lifespan).

## Tools Used
*   **Microsoft Power BI Desktop:** For data transformation, modeling (star schema based on these files), and visualization.
*   **Power Query:** For cleaning and shaping the CSV data.
*   **DAX:** For creating complex measures and business logic.

## Insights & Findings
*   **Classic Cars** consistently outperform other product lines in revenue generation.
*   **Sales Representative performance** varies significantly by region (office location).
*   High-value customers typically purchase **more than 5 items** per order.

## Author
* SWARANJALI HARKARE-https://www.linkedin.com/in/swaranjali-harkare-364a592a8/



