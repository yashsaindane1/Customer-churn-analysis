

## 1. 📌 Project Title / Headline

**📉 Churn Insights: End-to-End Telecom Customer Churn Analysis Dashboard**
An interactive, data-driven Power BI report built to analyze and predict customer churn for a telecom company — combining SQL-based ETL, advanced DAX measures, and a Machine Learning model to deliver actionable retention strategies.

---

## 2. 📝 Short Description / Purpose

This project focuses on understanding and reducing customer attrition by examining customer data to identify patterns and reasons behind customer departures. The dashboard enables businesses to visualize churn across demographic, geographic, payment, and service dimensions — and goes a step further by using a machine learning model to predict future churners, empowering teams to take proactive retention actions.

---

## 3. 🛠️ Tech Stack

The project uses Microsoft SQL Server for the ETL process, Power BI for dashboard creation, and Python (Jupyter Notebook) with a Random Forest algorithm for the machine learning model. Key tools include:

- 📊 **Power BI Desktop** – Data visualization and reporting
- 🗄️ **SQL Server (SSMS)** – ETL, data cleaning, and staging
- 🧠 **DAX** – Calculated measures and KPIs
- 🐍 **Python (Jupyter Notebook)** – Machine Learning model (Random Forest)
- 📁 **File Format** – `.pbix` for Power BI, `.csv` for raw data

---

## 4. 📂 Data Source

Source: Telecom customer dataset covering customer demographics, payment & account info, service usage, and churn status (Stay vs. Churned), loaded into a staging table `stg_Churn` inside a SQL Server database named `db_Churn`.

Key fields include: Customer ID, Gender, Age, State, Contract Type, Payment Method, Monthly Charges, Total Revenue, Churn Category, and Churn Reason.

---

## 5. ✨ Features / Highlights

**🔴 Business Problem**
In a competitive business environment, effective customer retention strategies are essential. Churn analysis helps understand and reduce customer attrition by examining patterns and reasons for customer departures.

**🎯 Goal of the Dashboard**
Create an entire ETL process in a database and a Power BI dashboard to visualize & analyze customer data at demographic, geographic, payment & account, and services levels — and identify a method to predict future churners.

**📊 Walkthrough of Key Visuals**

- **KPI Cards** — Total Customers, Total Churn, Churn Rate, New Joiners
- **Demographic View** — Churn by gender, age group, and marital status
- **Geographic View** — Churn rate by state across the US
- **Service Analysis** — Churn breakdown by internet type, contract, and add-on services
- **Payment View** — Churn patterns by payment method and monthly charges
- **Churn Reason Analysis** — Top reasons customers left (competitor, dissatisfaction, etc.)
- **ML Prediction Page** — Predicted future churners using Random Forest model integrated into Power BI

**💼 Business Impact & Insights**
The project provides hands-on experience in SQL, Power BI, and ML, reinforcing the importance of data-driven decision-making. An interactive churn probability predictor adds significant business value by helping marketing and retention teams target at-risk customers before they leave.
 
## 6. Screenshots / Demos
Show what the dashboard looks like. Example:
(https://github.com/yashsaindane1/Customer-churn-analysis/blob/main/Customer%20churn%20report.png)
