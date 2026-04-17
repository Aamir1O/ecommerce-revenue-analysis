# 📊 E-commerce Revenue Analysis & Dashboard

## 📌 Project Overview

This project analyzes an e-commerce dataset to uncover insights into revenue trends, product performance, and delivery efficiency.

The objective was to transform raw, multi-table data into meaningful business insights using data cleaning, feature engineering, and visualization.

---

## ⚙️ Tools & Technologies

* Python (Pandas)
* Tableau Public (Web)
* VS Code
* Git & GitHub

---

## 🧩 Dataset

* Olist Brazilian E-commerce Dataset (Kaggle)
* Multi-table relational dataset including:

  * Orders
  * Customers
  * Products
  * Order Items

---

## 🔧 Data Processing

* Cleaned missing values and handled inconsistencies
* Converted timestamp columns to datetime
* Merged multiple tables into a unified dataset
* Created key features:

  * **Revenue = price + freight_value**
  * **Delivery time (in days)**
  * **Order month and year**

---

## 📊 Dashboard


<img width="978" height="678" alt="Screenshot_2026-04-17_18-12-41" src="https://github.com/user-attachments/assets/067e3b69-4a60-4293-9dea-b192b12c3a44" />

---

## 🔍 Key Insights

### 📈 Revenue Trends

* Revenue shows seasonal patterns with peaks during mid-year (May–August)
* Drop observed during September–October

### 💰 Category Performance

* 'beleza_saude' is the top-performing category (~1.4M revenue)
* High revenue driven by order volume rather than price

### 🚚 Delivery Performance

* Median delivery time: ~10 days
* Average delivery time: ~12 days
* Most deliveries occur within 5–15 days
* 672 orders experienced delays greater than 50 days

### 🔍 Key Analytical Insight

* Higher revenue for longer delivery times was initially observed
* Further analysis revealed:

  * Higher-priced products take longer to deliver
  * Delivery time does NOT directly increase revenue
  * Price is the underlying factor influencing both

---

## 📌 Conclusion

The analysis highlights how product pricing, demand, and logistics influence revenue and delivery patterns. Identifying hidden relationships (such as price impacting delivery time) is critical for accurate business decision-making.
