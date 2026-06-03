# Data-Analytics-Project
Customer Behaviour Analysis Using Python, SQL and Power BI

# 🛍️ Customer Shopping Behavior — End-to-End Data Analytics Project

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL%20%7C%20SQL%20Server-orange?logo=postgresql)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green?logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview

This is a complete, end-to-end data analytics project that explores retail customer shopping behavior across **3,900 transactions**. Starting from raw data ingestion in Python, through exploratory data analysis, SQL-based querying, and finally a Power BI interactive dashboard — this project demonstrates a full analytics workflow as seen in real-world business intelligence roles.

**Business Question:** *What patterns exist in how customers shop — by age, category, season, payment method, and purchase frequency — and what insights can drive smarter retail decisions?*

---

## 📂 Dataset

| Property | Details |
|---|---|
| **File** | `customer_shopping_behavior.csv` |
| **Records** | 3,900 rows |
| **Features** | 18 columns |
| **Domain** | Retail / E-commerce |
| **Source** | Synthetic retail dataset |

### Key Columns

| Column | Type | Description |
|---|---|---|
| `Customer ID` | Integer | Unique customer identifier |
| `Age` | Integer | Customer age (18 – 70) |
| `Gender` | Categorical | Male / Female |
| `Category` | Categorical | Clothing, Footwear, Outerwear, Accessories |
| `Purchase Amount (USD)` | Float | Transaction value ($20 – $100) |
| `Season` | Categorical | Spring, Summer, Fall, Winter |
| `Review Rating` | Float | Customer rating (1.0 – 5.0) |
| `Subscription Status` | Binary | Yes / No |
| `Payment Method` | Categorical | PayPal, Credit Card, Cash, Venmo, etc. |
| `Frequency of Purchases` | Categorical | Weekly → Annually |
| `Discount Applied` | Binary | Yes / No |
| `Shipping Type` | Categorical | Free, Express, Standard, etc. |

---

## 🛠️ Tools & Technologies

| Layer | Tool |
|---|---|
| **Language** | Python 3.10+ |
| **Data Manipulation** | Pandas, NumPy |
| **Notebook** | Jupyter Notebook |
| **Database** | PostgreSQL |
| **BI Dashboard** | Microsoft Power BI |
| **Presentation** | Canva (Microsoft Powerpoint) |
| **Report** | Microsoft Word (.docx) |

---

## 🔄 Project Workflow

```
Raw CSV  ──►  Python EDA  ──►  Data Cleaning  ──►  SQL Analysis  ──►  Power BI  ──►  Report & PPT
```

---

## 📋 Steps

### Step 1 — Load & Explore Data (Python)
- Loaded `customer_shopping_behavior.csv` using **Pandas**
- Inspected shape, dtypes, null values, and duplicate records
- Generated summary statistics for all numeric columns
- Identified distributions for categorical variables

### Step 2 — Exploratory Data Analysis (EDA)
- Distribution of purchase amounts, age groups, and review ratings
- Category-wise and season-wise transaction counts
- Gender split and subscription rate analysis
- Correlation heatmap between numerical features
- Visualizations using **Matplotlib** and **Seaborn**

### Step 3 — Data Cleaning
- Handled missing values in `Review Rating` column
- Standardized categorical labels (e.g., trimmed whitespace)
- Verified and confirmed correct data types for all columns
- Removed any duplicate `Customer ID` entries

### Step 4 — SQL Queries
Connected the cleaned dataset to a relational database and ran analytical queries.

> ✅ Compatible with **PostgreSQL**, **MySQL**, and **SQL Server** with minor syntax adjustments.

### Step 5 — Power BI Dashboard
- Imported cleaned CSV into Power BI Desktop
- Built calculated columns and DAX measures (Avg Purchase, Subscription Rate, etc.)
- Designed two dashboard pages:
  - **Overview** — KPI cards, category breakdown, payment methods, purchase frequency
  - **Demographics** — Age group analysis, gender split, shipping types, ratings by category
- Added slicers for Season, Gender, and Category

### Step 6 — Report & Presentation
- Generated a structured **Word report** (.docx) with dataset summary, findings, and dashboard screenshots
- Created an AI-powered **Canva presentation** summarizing the project for stakeholder communication

---

## 📊 Dashboard

> **File:** `customer_behavior_dashboard.pbix`  
> Open in **Power BI Desktop** to interact with all slicers and filters.

### Page 1 — Overview
| Visual | Insight |
|---|---|
| KPI Cards | Total customers, avg purchase, avg rating, subscriber % |
| Donut Chart | Subscription status split (27% subscribed) |
| Column Chart | Purchase count and avg spend by category |
| Bar Chart | Transactions by payment method |
| Column Chart | Purchase frequency distribution |

### Page 2 — Demographics
| Visual | Insight |
|---|---|
| Pie Chart | Gender distribution (68% Male, 32% Female) |
| Bar Chart | Customer count and avg spend by age group |
| Bar Chart | Orders by shipping type |
| Column Chart | Avg review rating by category |

---

## 📈 Key Results

| Insight | Finding |
|---|---|
| 🏆 Top Category | Clothing — 1,737 transactions (44.5%) |
| 💳 Most Used Payment | PayPal (677 transactions) |
| 📅 Most Common Frequency | Every 3 Months (584 customers) |
| ⭐ Avg Review Rating | 3.75 / 5.0 |
| 🎟️ Discount Usage | 43% of all transactions used a discount |
| 📦 Shipping Preference | Balanced across all 6 options |
| 🌱 Seasonality | Nearly uniform across all four seasons |
| 💰 Avg Purchase Amount | $59.8 (consistent across categories and age groups) |

---

## 📁 Project Structure

```
customer-shopping-analytics/
│
├── 📄 customer_shopping_behavior.csv     # Raw dataset
├── 📓 code.ipynb                         # Python EDA & cleaning notebook
├── 📊 customer_behavior_dashboard.pbix   # Power BI dashboard
├── 📝 customer_behavior_report.docx      # Detailed project report
├── 📑 README.md                          # This file
└── 🗄️ sql_queries.sql                    # All SQL analysis queries
```

---

## 🤝 Connect

If you found this project useful or have suggestions, feel free to connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)]([https://linkedin.com/in/yashraj-somnath-kakade])

[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/yashrajkakade)

---

*Built as part of a data analytics portfolio project.*
