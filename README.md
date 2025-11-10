[**English**](README.md) | [**فارسی**](README_FA.md)
---
# 🎬 **DVD Rental – SQL Analytics & Power BI Dashboard**

![Power BI](https://img.shields.io/badge/PowerBI-Visualization-yellow?logo=power-bi)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?logo=postgresql)
![SQL](https://img.shields.io/badge/SQL-Queries-purple)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📘 Project Overview  

This project explores the **DVDRental sample database** — a classic PostgreSQL dataset for learning SQL and business analytics.  
The focus is on extracting actionable business insights through SQL queries and visualizing results in **Power BI**.  

The analysis covers sales performance, film popularity, revenue trends, and customer behavior — giving a 360° view of the DVD rental business model.

---

## 🧩 Project Structure  

📂 **dvdrental_dashboard**  
├── [**dvdrental_dashboard.pbix**](dvdrental_dashboard.pbix)  
├── queries/  
│   ├── 1- Low demanded movies.sql  
│   ├── 2- Popular genres in each year.sql  
│   ├── 3- Short-long movies Revenue analysis.sql  
│   ├── 4- Branch revenue (sun-mon).sql  
│   ├── 5- Revenue Trend.sql  
│   └── 6- Category Revenue.sql  
└── README.md  

---

## ⚙️ Analysis Workflow  

### 1️⃣ Data Source  
**Database:** PostgreSQL sample – DVDRental  
**Tables Used:** `rental`, `payment`, `film`, `category`, `store`, `staff`, `customer`, `inventory`

Data imported directly into Power BI via PostgreSQL connector.  
Custom SQL queries were used to prepare and aggregate data for visuals.

---

### 2️⃣ SQL Queries Overview  

| File | Description |
|------|--------------|
| **1- Low demanded movies.sql** | Identifies films with the lowest rental demand. |
| **2- Popular genres in each year.sql** | Tracks the most popular film categories by year. |
| **3- Short-long movies Revenue analysis.sql** | Compares total revenue between short and long-duration movies. |
| **4- Branch revenue (sun-mon).sql** | Analyzes store revenue between Sunday and Monday. |
| **5- Revenue Trend.sql** | Displays the overall revenue trend over time. |
| **6- Category Revenue.sql** | Breaks down total revenue by film category. |

---

### 3️⃣ Dashboard Highlights  

The **Power BI dashboard** visualizes the SQL results and includes:  
- 📈 **Revenue Trends:** Monthly and yearly changes in total sales.  
- 🏆 **Top Performing Categories:** Genres driving the most revenue.  
- 🧩 **Branch Comparison:** Store-level performance and weekly variation.  
- 🎞️ **Low vs. High Demand Movies:** Identifies underperforming titles.  
- ⏱️ **Duration-based Revenue:** Impact of film length on rental income.  

---

## 🧠 Tools & Technologies  

| Category | Tools |
|-----------|--------|
| Database | PostgreSQL (DVDRental) |
| Query Language | SQL |
| Visualization | Power BI |
| Environment | Power BI Desktop |
| Data Source | PostgreSQL sample database |

---

## 🚀 How to Run Locally  

### Prerequisites  
- PostgreSQL 14+ with **dvdrental** sample database  
- Power BI Desktop  

### Steps  
1. Download and restore the sample database:  
   [DVDRental – PostgreSQL Sample](https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/)

2. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/dvdrental_dashboard.git
   cd dvdrental_dashboard

Open the .pbix file in Power BI.

Update the PostgreSQL connection settings (host, port, user, password).

Optionally, review the SQL scripts in the queries folder for query logic.

📊 Key Insights

Action and Sports categories generated the highest revenue across stores.

Store 1 consistently outperformed Store 2 in both rentals and income.

The summer months showed peak rental activity.

Movies longer than 90 minutes had lower rental frequency but higher per-rental revenue.

Low-demand movies represent potential opportunities for targeted promotions.

🧾 References

PostgreSQL DVDRental Sample Database

Power BI PostgreSQL Connector Docs

SQL Official Documentation

👤 Author

Omid Jabari
📧 jabbariomid7@gmail.com

🌐 https://github.com/ChiefOmid


![dvdrental1](https://github.com/user-attachments/assets/e0867376-319c-4464-8bf5-3b7ad98a92b5)
![dvdrental2](https://github.com/user-attachments/assets/811fed8e-3613-486a-a863-007f04fdd2e1)

