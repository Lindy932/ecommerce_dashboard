# 🛍️ E-Commerce Sales & Operations Dashboard 

## 📌 Project Overview

This Power BI dashboard simulates how a data/business analyst would support an e-commerce company in understanding and improving sales, logistics, and customer satisfaction. This project explores patterns in order delays, product demand, customer reviews, and churn risks to support stakeholder decision-making.

## Tools
 - PostgreSQL
 - PgAdmin
 - Power BI
 - DAX
 - Power query
 - Forecast


## 🎯 Key Stakeholder Questions

| Stakeholder         | Key Business Questions |
|---------------------|------------------------|
| **Operations Team** | Are we delivering on time across all regions? Where are the delays? |
| **Customer Success**| Are delivery issues causing poor reviews or churn? |
| **Marketing**       | Which segments/categories drive the most revenue and loyalty? |
| **Leadership**      | Are we growing month over month? How healthy is the business overall? |


## 📊 Dashboard Pages

### 1. ✅ Executive Overview
- KPIs: Total Orders, % Delayed, Avg Delivery Time, Delivery Success Rate
- Monthly Order Trend (Line)
- Orders by Region (Donut)
- Order Lifecycle (Funnel)


---

### 2. 🚚 Logistics & Delivery
- Delay Trends (Line)
- Delivery Delays by State (Map)
- Worst Performing Cities (Bar)
- Freight vs. Weight (Scatter)
- Seller Delay Metrics (Matrix)



---


### 4. 📦 Product & Category Insights
- Revenue by Category (Treemap)
- Category Growth Trend (Line)
- Top Categories by Volume (Bar)
- Forecasting Demand (Line)
- Category Metrics Table


---

### 3. 💔 Customer Retention & Churn
- Churn Risk Segmentation (Bar)
- Monthly Buyers (Line)
- Review Score Heatmap by Region (Map)
- Review by Category (Bar)
- Customer Detail Table (High-risk focus)



---


## 🔎 Global Filters (Slicers)
- Date Range  
- Customer State  
- Product Category  
- Order Status  
- Churn Risk  

---

## 🛠 Skills Used

- **Power BI**: Slicers, Drill-throughs, Custom DAX Measures
- **Data Modeling**: Relationships between orders, sellers, customers, products
- **DAX Metrics**: Delayed % Orders, Avg Freight, Churn Risk Tagging
- **Visualization Design**: Multi-layered pages, clean UX

---

## 📁 Dataset

- **Source**: [Kaggle - Brazilian Olist E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Tables used: Orders, Customers, Sellers, Products, Reviews, Payments

- This big data set includes over 95k+ records of customer orders, which is then filtered and cleaned through Excel and queried in PostgreSQL after database is created. Relationships are then established, visualized and calculated in Power BI.
 

---

## 🌱 Future Improvements

- RFM Analysis for Customer Segmentation  
- Add Marketing Campaign Data  
- Connect to Live SQL or Cloud Source  
- Role-based Stakeholder Views  

---

## 📸 Sample Dashboard Screenshots

<p align="center">
  <img width="980" height="543" alt="Screen Shot 2025-07-31 at 2 29 18 AM" src="https://github.com/user-attachments/assets/4ed45d50-65d9-430d-99cd-7eadfd4f1172" />
</p>

<p align="center">
 <img width="980" height="543" alt="Screen Shot 2025-08-05 at 1 43 13 AM" src="https://github.com/user-attachments/assets/682602ee-54c3-4ccf-a88c-6feca33ef6bb" />


</p>

<p align="center">
 <img width="980" height="540" alt="Screen Shot 2025-07-31 at 2 30 25 AM" src="https://github.com/user-attachments/assets/8ded6a54-0837-423f-90d7-ab29fe44483c" />

</p>

<p align="center">
<img width="980" height="540" alt="Screen Shot 2025-08-05 at 1 40 49 AM" src="https://github.com/user-attachments/assets/db249c1b-e2e3-435a-8e90-7746490b489e" />
</p>


