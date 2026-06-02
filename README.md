# 🛒 E-Commerce Customer Behavioral & Revenue Analytics (SQL + Python Pipeline)

## 📌 Project Overview
This project demonstrates an **End-to-End Data Analytics Pipeline** that simulates how top-tier companies (e.g., E-commerce platforms, Telecoms, and Banks) extract data from relational databases and transform it into actionable business strategies. 

By connecting a relational **SQL database** directly to a **Python environment**, this analysis processes customer demographics and transactional records to discover key revenue drivers, segment customers based on behavioral attributes, and evaluate monthly growth trends.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Database Management & Querying:** Advanced SQL (SQLite), relational database design, complex `INNER JOINs`, conditional logic (`CASE WHEN`), date-time manipulation (`strftime`), and data aggregations (`GROUP BY`, `SUM`, `COUNT`).
* **Programming & Environment:** Python, Jupyter Notebook / Google Colab.
* **Data Manipulation:** Pandas (converting SQL queries directly into DataFrames, managing data structures).
* **Data Visualization:** Matplotlib & Seaborn (creating high-quality, production-ready Bar Charts, Donut Charts, and Line Plots with dynamic data annotations).
* **Business Intelligence:** Customer Segmentation, Trend Analysis, and Revenue Optimization.

---

## 📂 Database Architecture & Schema
The project utilizes an in-memory SQL database consisting of two relational tables:
1. **`Users` Table:** Contains demographic features including `user_id`, `join_date`, `country`, `age`, and `membership_type`.
2. **`Transactions` Table:** Contains purchasing behaviors including `transaction_id`, `user_id`, `purchase_date`, `amount`, `category`, and order `status` (Completed vs. Cancelled).

---

## 📊 Key Insights & Business Findings

### 1. Geographical Dominance (Bar Chart Analysis)
* **Finding:** **Kuwait** is leading the platform's revenue generation ($3,284.66 across 42 orders), followed closely by Jordan. Conversely, the UAE represents the lowest revenue segment.
* **Strategic Impact:** Indicates strong purchasing power or high customer acquisition success in Kuwait, marking it as a primary market.

### 2. Demographic Powerhouse (Donut Chart Analysis)
* **Finding:** The **"Middle Aged" segment (ages 31-50)** is the core driving force of the business, accounting for **52.4%** of total revenue. "Seniors" and "Young Adults" contribute equally at around 24% each.
* **Strategic Impact:** Highlights where product curation and user experience updates should be heavily focused.

### 3. Sales Trend Analysis (Line Chart Growth Tracking)
* **Finding:** Revenue peaked dramatically in **March 2026** reaching **$2,588.98**, driven by seasonal high-volume orders. However, a continuous downward trend was observed through April and May.
* **Strategic Impact:** Signals an immediate need for promotional interventions to counter post-peak revenue drops.

---

## 💡 Actionable Recommendations
1. **High-Value Market Localization:** Launch targeted loyalty rewards and localized marketing campaigns in Kuwait and Jordan to sustain and scale high-value transaction volumes.
2. **Tailored Platform Curation:** Optimize the platform's homepage layout, recommendations, and inventory selection to match the preferences of the **31-50 age bracket**, maximizing their high lifetime value (LTV).
3. **Q2 Recovery Strategy:** Investigate external seasonal or competitive factors causing the post-March decline. Deploy re-engagement email loops and flash sales for inactive users to reverse the current downward trend.

---

## 🚀 How to Run the Project
1. Clone this repository or download the `ECommerce_Customer_Behavior_Analytics.ipynb` file.
2. Open the file using Jupyter Notebook or Google Colab.
3. Run all cells sequentially. The SQL database will be automatically provisioned, populated with relational data, queried, and visualized instantly.
