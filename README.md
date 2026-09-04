# E-Commerce Business Intelligence & Customer Analytics Dashboard

## Project Overview

Developed an end-to-end E-Commerce Business Intelligence solution using Power BI to analyze sales, customers, products, customer satisfaction, delivery operations, payments, and order risk using the Olist Brazilian E-Commerce dataset.

The project analyzes approximately 99K orders and 96K customers and converts raw transactional data into interactive dashboards and actionable business insights.

## Business Problems Addressed

- How is overall sales performance changing over time?
- Which product categories generate the highest sales?
- Which states contribute the most revenue?
- What is the customer retention level?
- How satisfied are customers?
- How efficient is the delivery process?
- Where are cancellation rates higher?
- What payment methods are most widely used?
- Which business areas require management attention?

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Star Schema
- Data Visualization

## Data Preparation

Used Power Query to:
- Clean and transform source datasets
- Standardize column names and data types
- Handle duplicate records
- Prepare date fields
- Merge product-category translation data
- Prepare datasets for relational analysis

## Data Model

Built a relational data model using:
- Customer Dimension
- Date Dimension
- Orders
- Order Items
- Products
- Payments
- Reviews

Created one-to-many relationships to support dynamic filtering and analysis.

## Key KPIs

| KPI | Value |
|---|---:|
| Total Sales | 13.59M |
| Total Orders | 99K |
| Total Customers | 96K |
| Average Order Value | 136.68 |
| Repeat Customer Rate | 3.1% |
| Average Review Score | 4.09 / 5 |
| Average Delivery Time | 12.5 Days |
| On-Time Delivery | 92% |
| Late Delivery | 8% |
| Cancelled Orders | 625 |
| Cancellation Rate | 0.6% |
| Total Payment Value | 16.01M |

## Dashboard Sections

### 1. Executive Overview
Provides a high-level view of sales, orders, customers, AOV and delivery performance.

### 2. Sales & Customer Intelligence
Analyzes sales trends, regional revenue, customer distribution and repeat purchasing behavior.

### 3. Revenue & Order Analysis
Analyzes revenue trends, order volume, average item price, freight burden and regional performance.

### 4. Product Performance
Identifies top-selling categories and products and compares sales, item volume, value and customer satisfaction.

### 5. Customer Experience
Analyzes customer ratings and delivery performance to understand service quality.

### 6. Delivery & Operations
Monitors delivery time, late deliveries, on-time performance and order status.

### 7. Business Insights & Recommendations
Converts analytical findings into business actions related to retention, product performance, delivery and cancellations.

### 8. Order & Payment Risk
Analyzes payment behavior, cancellations and regional order risk.

## Key Business Insights

- Repeat customer rate is 3.1%, highlighting a significant customer-retention opportunity.
- 92% of orders were delivered on time, while 8% experienced late delivery.
- 625 orders were cancelled, representing a 0.6% cancellation rate.
- Average customer review score is 4.09/5, indicating generally positive customer feedback.
- `beleza_saude` was the highest-selling product category in the analysis.

## Recommendations

- Develop loyalty and repeat-purchase campaigns.
- Investigate regions with higher delivery delays.
- Protect and scale high-performing product categories.
- Monitor cancellation hotspots by region and time.
- Continue monitoring customer feedback and service quality.

## Project Outcome

The dashboard transforms multi-table e-commerce transaction data into an interactive business intelligence solution that enables users to monitor performance, identify operational risks, understand customer behavior, and make data-driven decisions.
