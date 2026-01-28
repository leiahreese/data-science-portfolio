# Retail Customer Segmentation: RFM Analysis

## 📌 Project Overview
This project focuses on analyzing retail transaction data to segment customers based on their purchasing behavior. By applying the **RFM (Recency, Frequency, Monetary)** framework, I categorized customers into distinct groups to help businesses tailor their marketing strategies.

## Tech Stack
* **Database:** PostgreSQL / MySQL (Data Extraction & RFM Calculation)
* **Analysis:** Python (Pandas)
* **Environment:** VS Code
* **Logic:** SQL CTEs (Common Table Expressions) and Aggregate Functions

## Methodology: What is RFM?
* **Recency (R):** How many days since the customer's last purchase?
* **Frequency (F):** How often does the customer shop?
* **Monetary (M):** How much total revenue does the customer generate?

Each customer is assigned a score from 1-5 for each metric, allowing us to identify:
* **Champions:** Our best customers.
* **At-Risk:** Customers who used to shop often but haven't returned lately.
* **New Customers:** High recency but low frequency.

## 📂 Project Structure
* `queries/`: Contains the SQL scripts used to clean data and calculate RFM scores.
* `notebooks/`: Python notebooks for data profiling and visualization.
* `data/`: (Optional) Sample of the dataset used.

## 💡 Key Insights
* Identified that **X%** of the customer base accounts for **Y%** of total revenue.
* Discovered a specific segment of "Loyal" customers who are ripe for a referral program.

---
*Developed as part of my Big Data Analytics specialization at PUP Manila.*
