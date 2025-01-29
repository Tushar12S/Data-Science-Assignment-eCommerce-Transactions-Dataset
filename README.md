# Data-Science-Assignment-eCommerce-Transactions-Dataset

This repository contains **Exploratory Data Analysis (EDA)**, a **Lookalike Model**, and **Customer Segmentation (Clustering)** for an eCommerce dataset.

## 📌 Project Overview
**Objective:** Analyze eCommerce transactions to extract insights, predict customer behavior, and improve business strategies.

**Dataset:**
- `Customers.csv` – Customer details (ID, region, signup date).
- `Products.csv` – Product details (ID, category, price).
- `Transactions.csv` – Purchase records (customer, product, quantity, total value).

---

## 🔍 Key Features

### **1️⃣ Exploratory Data Analysis (EDA)**
- Analyzed customer distribution, product performance, pricing trends, and revenue growth.
- Key insights:
  - **South America** has the highest number of customers.
  - **Books & Electronics** are the top-selling categories.
  - Revenue peaks in **December & July** due to promotions.
  
📄 Report: [Business Insights from EDA](reports/Business%20Insights%20from%20EDA.pdf)

---

### **2️⃣ Lookalike Model**
- Identifies **top 3 similar customers** based on purchase behavior.
- Uses **clustering-based similarity analysis**.

📄 Output: [Lookalike Customers](outputs/Tushar_Shetty_Lookalike.csv)

---

### **3️⃣ Customer Segmentation (Clustering)**
- Segmented customers into **2 clusters** using the **Davies-Bouldin Index (DBI = 0.63)**.
- **Cluster 0:** Low spenders → Target with discounts.
- **Cluster 1:** High-value customers → Retain with loyalty programs.

📄 Report: [Customer Clustering Report](reports/Tushar_Shetty_Clustering.pdf)

---
