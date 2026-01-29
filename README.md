# E-commerce Customer Segmentation & Revenue Analysis

## Project Overview
This project analyzes an e-commerce transaction dataset to uncover revenue drivers, customer behavior patterns, and actionable customer segments.  
The analysis progresses from **exploratory data analysis (EDA)** to **RFM-based customer segmentation**, using both **rule-based logic** and **unsupervised clustering**, and concludes with **business recommendations and Power BI–ready outputs**.

The goal is to demonstrate an end-to-end analytics workflow that bridges data exploration, modeling, and business decision-making.


## Business Objectives
- Understand sales, product, geographic, and customer behavior patterns
- Identify revenue concentration and seasonality
- Segment customers based on purchasing behavior
- Translate data-driven segments into actionable business strategies
- Prepare clean, structured datasets for BI visualization


## Exploratory Data Analysis (EDA)
The EDA phase focuses on understanding the structure and quality of the data, including:

- Data cleaning and validation
- Identification of cancelled and invalid transactions
- Revenue and order volume trends
- Product performance analysis
- Geographic sales distribution
- Customer behavior analysis and revenue concentration
- Seasonality and time-based trends

Key insights include:
- Revenue is highly concentrated among a small subset of customers
- Sales peak during late Q3 and Q4, driven primarily by increased order volume
- Product revenue is driven by a mix of high-volume and high-value items


## Customer Segmentation (RFM)
Customer segmentation is performed using **Recency, Frequency, and Monetary (RFM)** features.

### Approach
1. Construct a customer-level feature table
2. Apply log transformation and scaling
3. Use K-Means clustering to identify natural customer groupings
4. Profile clusters and map them to business-friendly segments
5. Validate results against RFM behavior patterns

### Final Segments
- **Champions** – Highly active, frequent, and high-spending customers
- **Loyal Customers** – Consistent repeat buyers with stable engagement
- **Dormant High-Value Customers** – Historically high spenders with recent inactivity
- **Occasional Buyers** – Low-frequency, low-spend customers with recent activity
- **Hibernating** – Long inactive, low-value customers


## Business Recommendations
Segment-specific strategies are proposed to maximize impact:

- **Champions**: Retention through VIP programs and personalized engagement
- **Loyal Customers**: Cross-sell and upsell to increase share of wallet
- **Dormant High-Value Customers**: Win-back campaigns to recover lost revenue
- **Occasional Buyers**: Low-cost incentives to encourage repeat purchases
- **Hibernating**: Cost-efficient reactivation or deprioritization

This framework supports targeted marketing, churn reduction, and more efficient resource allocation.


## Power BI Integration
The project outputs two Power BI–ready datasets:
- `customer_segments.csv` – Customer-level segmentation and RFM metrics
- `df_sales.csv` – Transaction-level sales data

These datasets support dashboards for:
- Customer segmentation overview
- Revenue contribution by segment
- Sales trends and seasonality
- Product and geographic performance


## Tools & Technologies
- **Python** (Pandas, NumPy, Scikit-learn)
- **Jupyter / Google Colab**
- **Power BI**
- **GitHub**

## Key Takeaways
- Customer value is highly skewed, with a small segment driving most revenue
- Data-driven segmentation enables targeted, high-impact strategies
- Combining clustering with business interpretation yields robust, actionable segments
- Clean data modeling is critical for scalable BI reporting

[![Sales Dashboard Screenshot](sales_report.jpg)](https://app.powerbi.com/view?r=eyJrIjoiZmEyM2ZlNmUtM2Q2OC00OThhLWFlMmMtMWE1MzVlNDZhNTM3IiwidCI6IjlkZGFhY2ExLTM4OWYtNGNiMS1hMTEzLTA4MWJlNmNjMjVmYyIsImMiOjZ9)


