# Customer Churn Segmentation and Analysis

## Project Overview
Identify at-risk customers, analyze purchasing behavior, and provide actionable insights to improve **customer retention** and **maximize revenue**. Merging transactional sales data with customer profiles provides a **360° view of customer behavior**, enabling data-driven marketing and retention strategies.

---

## Datasets

### 1. Sales Dataset (`synthetic_sales_dataset.csv`)
Each row represents a single transaction with columns:  
- `Customer_ID`  
- `Age`, `Gender`, `Region`  
- `Product_Category`, `Purchase_Amount_USD`, `Purchase_Date`  
- `Campaign`, `Returns`, `Satisfaction_Score`  

### 2. Customer Segmentation Dataset (`customer_segmentation_dataset.csv`)
Each row represents a customer profile with columns:  
- `Customer_ID`  
- `Age`, `Gender`  
- `Purchase_Amount_USD`, `Satisfaction_Score`, `Number_of_Orders`  

---

## Objectives
- Merge transactional and segmentation datasets to create a **unified dataset**  
- Identify **high-value** and **at-risk** customers  
- Analyze **purchase patterns** by segment, campaign, and product category  
- Calculate key metrics:  
  - `Customer Lifetime Value (CLV)`  
  - `Repeat purchase rate`  
  - `Average purchase amount`  
  - `Satisfaction` and `Return rates`  
- Provide actionable insights for **targeted marketing and retention**

---

## Methodology

### 1. Data Preparation
- Load CSV files  
- Inspect unique customers and overlapping columns  
- Merge datasets on `Customer_ID` using a left join  

### 2. Feature Engineering
- `Recency`: Days since last purchase  
- `Frequency`: Total number of orders  
- `Monetary`: Total spend  
- `Satisfaction` and `Returns` metrics  

### 3. Analysis
- Segment-level behavior analysis  
- Campaign and product performance by segment  
- Churn risk identification  

### 4. Visualization
- Revenue and purchase trends by segment  
- Churn risk heatmaps  
- Campaign effectiveness dashboards  

---

## Technologies
- `Python (pandas, numpy, matplotlib, seaborn)`  
- `SQL/PostgreSQL`  
- `Excel`  

---

## Expected Outcomes
- Segmented view of customers based on churn risk  
- Insights into purchasing behavior per segment  
- Recommendations for targeted campaigns  
- KPIs to monitor retention and revenue
