# 🛒 SQL Ecommerce Data Analysis

## 📌 Project Overview
This project applies **SQL for Data Analysis** on a real-world **E-commerce dataset** (UK-based online retailer).  
Since the full dataset is over 40 MB, a **sample of 10,000 rows (`data_sample.csv`)** is used in this repo for demonstration and faster execution.  

The analysis is done using **SQLite inside Python** (via Pandas) inside a Jupyter notebook.

---

## 📂 Files in this Repository
- `ecommerce-data-analysis.ipynb` → Jupyter/Colab notebook with SQL queries + analysis  
- `data_sample.csv` → 10k-row dataset sample (GitHub-friendly)  
- `README.md` → Documentation  

---

## 🛠 Tools & Libraries
- Python  
- Pandas  
- SQLite (via `sqlite3`)  
- Matplotlib  
- Seaborn  

---

## 🔍 SQL Techniques Covered
- **Data Cleaning**: removed cancellations, negative values, missing IDs  
- **SELECT & WHERE** → Filtering  
- **ORDER BY** → Sorting results  
- **GROUP BY + Aggregations** → Revenue by product & country  
- **Subqueries** → Advanced filtering (e.g., above-average spenders)  
- **Views & Indexes** → For reusability and performance (demonstrated as optional)  

---

## ✅ Outcome
By completing this project, we practiced:
- Loading and cleaning retail transaction data  
- Running SQL queries inside Python  
- Extracting insights such as top products, customers, and countries by revenue  
- Identifying monthly sales trends  

This mirrors **real-world workflows** for data analysts in the Ecommerce domain.

---

## 🔗 Dataset
The full dataset (~40 MB, 500k+ rows) is available on Kaggle:  
[E-Commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  

This repo uses a **sample file (`data_sample.csv`, 10k rows)** for quick demo.
