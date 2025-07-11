# 🛒 Instacart Reorder Analysis (SQL Project)

A medium level SQL project analysing user reorder behavior based on Instacart's open-source dataset. Dataset downloaded from kaggle.
Link to the dataset: https://www.kaggle.com/c/instacart-market-basket-analysis/data
Disclaimer: I do not own any rights on the data. Used here for educational purposes only.

---

## 🔧 Tools Used
- **MySQL** (Workbench)
- **SQL** (Joins, Aggregations, Indexing)
- **Dataset**: 30K+ order counts sampled from Instacart 2017 Open Source Dataset (1M+ records)

---

## 📁 Dataset Tables
- `orders.csv` – order history for ~200K users
- `order_products__prior.csv` – product info for each past order
- `products.csv` – product names + category info
- `aisles.csv` and `departments.csv` – product hierarchy metadata

---

## 🚀 Key Features
- Sampled 2,000 unique users and built dependent tables
- Used SQL joins and aggregations to extract behavior insights
- Created performance indexes for fast querying

---

## 📊 Key Insights
- Top reordered products & departments
- Weekly retention & reorder % for sampled users
- Loyal user profiles based on order history

---

## 📂 How to Run
1. Clone the repo
2. Place CSVs in `sample_data/` folder
3. Use MySQL Workbench:
   - Run `instacart_project.sql` to create and load all tables
   - Adjust file paths in `LOAD DATA INFILE` if needed

---

## 📌 Sample Queries Included
- Total & loyal users
- Weekly retention metrics
- Reorder rates by aisle/product
- Top departments and customer behavior

---

## 🏁 Status
✅ Completed and tested with MySQL  
📂 Suitable for case studies, dashboards, and product analysis roles

---

## 📬 Contact
ag.yash1920@gmail.com
Made by [Yash Agarwal] — for project/portfolio use
