# 📊 Detailed Insights from E-commerce Analysis

## 🧩 1. Revenue Trends & Seasonality

* Monthly analysis shows clear **seasonal variation** in revenue.
* Peak revenue observed during **May–August**, indicating higher customer activity during mid-year.
* Noticeable decline in **September–October**, suggesting potential demand drop or seasonal slowdown.

---

## 📈 2. Year-over-Year Growth

* Revenue increased significantly from **2017 to 2018**.
* 2016 shows very low revenue, likely due to incomplete data or early business stage.

---

## 💰 3. Product Category Performance

* **'beleza_saude'** is the top-performing category (~1.4M revenue).
* Other strong categories include:

  * relogios_presentes
  * cama_mesa_banho
  * esporte_lazer

📌 **Key Observation:**

* High revenue is primarily driven by **order volume**, not necessarily high product price.

---

## 🚚 4. Delivery Performance Analysis

* **Median delivery time:** ~10 days (typical customer experience)
* **Average delivery time:** ~12 days (slightly skewed by delays)
* Majority of orders delivered within **5–15 days**

### ⚠️ Outliers:

* **672 orders** experienced delivery times greater than **50 days**
* Maximum delivery time observed: **~209 days**

---

## 🔍 5. Delivery Time vs Revenue (Critical Insight)

* Initial observation suggested:

  > Longer delivery times → higher revenue

* Further investigation revealed:

  * This is a **correlation**, not causation

### ✅ Root Cause:

* Higher-priced products:

  * Generate more revenue
  * Require longer delivery times

📌 **Correct Interpretation:**

* Delivery time does **not directly influence revenue**
* Both are influenced by **product price and complexity**

---

## 📦 6. Price vs Delivery Relationship

* Analysis shows a clear trend:

  * **Higher-priced products tend to have longer delivery times**

### Possible Reasons:

* Complex logistics and handling
* Supplier-based fulfillment
* Limited availability or sourcing delays

---

## ⚠️ 7. Data Characteristics & Limitations

* Presence of outliers significantly affects average metrics
* Missing values in product categories required imputation
* No customer feedback or review data available

📌 **Impact:**

* Limits ability to analyze customer satisfaction or perception

---

## 🧠 Final Key Takeaways

* Revenue is driven primarily by **product demand and pricing**
* Delivery system is efficient for most orders but shows **inconsistency due to outliers**
* Higher delivery times are linked to **product characteristics**, not poor performance
* Identifying hidden relationships (price → delivery time) is critical for accurate analysis

---

## 🚀 Recommendations

* Optimize logistics for high-value products
* Investigate causes of extreme delivery delays
* Focus on high-performing categories for revenue growth
* Implement monitoring for delivery performance consistency
