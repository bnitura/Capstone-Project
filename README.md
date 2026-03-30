# Capstone-Project
This repository contains files required for the Capstone Project

Problem Statement: E-commerce and retail companies struggle to personalize marketing efforts due to highly heterogeneous customer behaviour, leading to inefficient marketing spend and lower-than-optimal customer retention. While traditional RFM (Recency, Frequency, Monetary) identifies high-spenders, it fails to distinguish new loyalists from long-term regulars (missing Time) or capture customers willing to explore new product categories (missing Diversity). 

Objective: To segment the customer base using the RFMT-D model to identify distinct behavioural groups—specifically, "high-diversity loyalists" and "at-risk long-term customers"—to enable targeted marketing campaigns that increase retention and increase cross-selling revenue.

Task Type: (1) Unsupervised Learning / Clustering Analysis (using K-Means). (2) Descriptive Analytics (profiling segments based on RFMT-D scores) 

RFMT-D Feature Definition
•	Recency: Days since the last purchase.
•	Frequency: Total number of purchases.
•	Monetary: Total amount spent.
•	Time: Number of days between the first and last purchase.
•	Diversity: Unique count of different product categories purchased.

Data Dictionary

| Variable | Type | Description | Allowed Values | Notes |
| ----- | ----- | ----- | ----- | ----- |
| **InvoiceNo** | Numeric (Integer) | Invoice number composed of a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation. | 1-999999 | Alphanumeric detected |
| **StockCode** | Numeric (Integer) | Product (item) code composed of a 5-digit integral number uniquely assigned to each distinct product. | 1-99999 | Alphanumeric detected |
| **Description** | Text (String) | Product name | abc | Null value detected |
| **Quantity** | Numeric (Integer) | The quantities of each product (item) per transaction | 1-99999 | Negative value detected |
| **InvoiceDate** | Numeric | Invoice Date and time. The date and time when each transaction was generated. | MM/DD/YYYY HH:MM |   |
| **UnitPrice** | Numeric (Float) | Product price per unit | 1-99999 | Negative value detected |
| **CustomerID** | Numeric (Float) | Customer number composed of a 5-digit integral number uniquely assigned to each customer. | 1-99999 | Null value detected |
| **Country** | Text (String) | Country name. The name of the country where each customer resides. | abc |   |

Data used is from Kaggle customer_segmentation.csv

