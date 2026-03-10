# 📊 Retail Sales Performance Analysis

This project analyzes the **Online Retail Dataset** to identify sales trends, product performance, customer behavior, product returns, and geographic revenue distribution.

The analysis was performed using **SQL for data processing** and **Tableau Public for visualization**.

🛠 Tools: SQL (SSMS), Excel, Tableau Public  
📁 Dataset: Online Retail Dataset (Dec 2010 – Nov 2011)

---

## 🎯 Project Objective

Transform raw transactional data into **business insights** that help understand:

- Seasonal sales patterns
- Product revenue distribution
- Geographic sales concentration
- Customer data gaps
- Product return patterns

---

## 🧹 Data Preparation

Key preprocessing steps:

- Created **Revenue column**  
  `Revenue = UnitPrice × Quantity`

- Identified invoice types:
  - Normal sales invoices
  - Credit notes (sales returns)
  - Adjustment entries (accounting adjustments)

- Removed records with:
  - Missing product descriptions
  - Zero revenue
  - Accounting adjustment entries

- Converted Excel dataset to **CSV** for SQL analysis.

---

## 📈 Key Insights

**Seasonal Sales Pattern**
- Revenue peaks between **September and November 2011**.

**Product Distribution**
- ~3,800+ products in dataset  
- Top 10 products contribute **~9.5% of revenue**

**Geographic Concentration**
- **~84% of revenue comes from the UK**

**Customer Data Gap**
- **14.7% of revenue** comes from transactions without CustomerID.

**Product Returns**
- Returns concentrated in a small number of items, particularly **Stock Code 23166**.

---

## 📊 Dashboard

The Tableau dashboard visualizes:

- Monthly revenue trends
- Revenue by country
- Top-performing products
- Product return patterns

<img width="1150" height="588" alt="4  Dashboard_screenshot" src="https://github.com/user-attachments/assets/9978d194-dee8-4604-b843-7f836fc1aa15" />


🔗 [View Tableau Dashboard](https://public.tableau.com/app/profile/shraddha.patil7431/viz/OnlineRetailSales_17730061003910/Dashboard1?publish=yes)

---

## 📁 Repository Structure

Online_Retail_Sales_Performance_Analysis

1. Raw_Data
2. Cleaned_Data
3. SQL_Analysis
4. Tableau_Dashboard
5. README.md

---

