
# 🏦 Bank Loan Report Dashboard using Power BI & Microsoft SQL Server

## 📘 Project Overview
This project focuses on developing a **Bank Loan Report Dashboard** using **Power BI**, with data sourced directly from **Microsoft SQL Server (MSSQL)**. The dashboard provides an end-to-end analytical solution for monitoring loan performance, repayment trends, and borrower financial health through interactive visuals and KPIs.

The project includes **three key dashboards** — **Summary**, **Overview**, and **Details** — each designed to give different levels of insights into the bank’s lending operations.

---

## 🎯 Problem Statement

### **Dashboard 1: Summary**
The **Summary Dashboard** provides a holistic view of the bank’s key performance indicators (KPIs) to monitor lending performance and financial health.

#### **KPI Requirements:**
1. **Total Loan Applications** – Total applications received, with Month-to-Date (MTD) and Month-over-Month (MoM) tracking.  
2. **Total Funded Amount** – Total amount disbursed as loans, with MTD and MoM comparisons.  
3. **Total Amount Received** – Amount received from borrowers to analyze repayment patterns (MTD & MoM).  
4. **Average Interest Rate** – Average interest rate of all loans (MTD & MoM) to track changes in lending costs.  
5. **Average Debt-to-Income Ratio (DTI)** – Average borrower DTI, providing insights into financial stability (MTD & MoM).

#### **Good Loan vs Bad Loan KPIs**
**Good Loan Metrics:**
- Good Loan Application Percentage  
- Good Loan Applications  
- Good Loan Funded Amount  
- Good Loan Total Received Amount  

**Bad Loan Metrics:**
- Bad Loan Application Percentage  
- Bad Loan Applications  
- Bad Loan Funded Amount  
- Bad Loan Total Received Amount  

#### **Loan Status Grid View**
A grid report categorized by *Loan Status* showing:
- Total Loan Applications  
- Total Funded Amount  
- Total Amount Received  
- MTD Funded Amount  
- MTD Amount Received  
- Average Interest Rate  
- Average DTI  

This grid allows for better loan performance assessment and data-driven decision-making.

![image alt](https://github.com/asif684/Bank-Financial-Analytics-PowerBI-MSsql-Server-Dashboard/blob/5581aafd694b5f7a37eca3e82e2163d1cd3c65b0/image4-bank-mssql.png)

---

### **Dashboard 2: Overview**
The **Overview Dashboard** visualizes trends and distributions to understand lending behavior across time, geography, and borrower demographics.

#### **Charts Included:**
1. **Monthly Trends by Issue Date (Line Chart):** Identify seasonality and trends in loan issuance.  
2. **Regional Analysis by State (Filled Map):** Compare lending activities across regions.  
3. **Loan Term Analysis (Donut Chart):** Analyze loan distribution by term duration.  
4. **Employee Length Analysis (Bar Chart):** Understand how borrower employment length impacts loan behavior.  
5. **Loan Purpose Breakdown (Bar Chart):** Visualize loan distribution by purpose.  
6. **Home Ownership Analysis (Tree Map):** Show how home ownership status affects loan patterns.  

**Metrics Displayed:**  
- Total Loan Applications  
- Total Funded Amount  
- Total Amount Received  

![image alt](https://github.com/asif684/Bank-Financial-Analytics-PowerBI-MSsql-Server-Dashboard/blob/5581aafd694b5f7a37eca3e82e2163d1cd3c65b0/image2-bank-mssql.png)

---

### **Dashboard 3: Details**
The **Details Dashboard** acts as a **comprehensive data view** for deeper exploration of loan-level information.

#### **Objective:**
To provide a one-stop, user-friendly interface for exploring:
- Borrower details  
- Loan applications  
- Repayment behavior  
- Performance metrics  

This dashboard enhances transparency and supports in-depth analysis of the loan portfolio.

![image alt](https://github.com/asif684/Bank-Financial-Analytics-PowerBI-MSsql-Server-Dashboard/blob/5581aafd694b5f7a37eca3e82e2163d1cd3c65b0/image3-bank-mssql.png)

![image alt](https://github.com/asif684/Bank-Financial-Analytics-PowerBI-MSsql-Server-Dashboard/blob/5581aafd694b5f7a37eca3e82e2163d1cd3c65b0/image4-bank-mssql.png)

---

## ⚙️ Functionalities Used

### **In Microsoft SQL Server:**
- **Database Creation & Table Design**
- **Data Retrieval & Manipulation:**
  - `SELECT`, `GROUP BY`, `ORDER BY`, `LIMIT`, `COUNT`, `DISTINCT`
- **Date & Time Functions:**
  - `DATENAME`, `DATEPART`, `MONTH`, `DAY`, `HOUR`, `QUARTER`
- **Type Conversion:**
  - `CAST`, `DECIMAL`
- **Common Table Expressions (CTE)**
- **Partitioning for Aggregations**

### **In Power BI:**
- **Data Connection:** Direct connection to SQL Server  
- **Data Cleaning & Modelling:** Using **Power Query**  
- **Data Processing:** Building relationships and defining hierarchies  
- **Date Tables & Time Intelligence:** MTD, QTD, YTD metrics  
- **DAX Functions:**
  - Date Functions  
  - Text Functions  
  - Filter Functions  
  - `CALCULATE`, `SUM`, `SUMX`
- **Creating KPIs & Cards:** For Total, MTD, and MoM metrics  
- **Chart Visuals:** Line, Donut, Bar, Tree Map, and Filled Map  
- **Formatting & Navigation:** Enhanced UX with interactive visuals and report navigation  

---

## 🧩 Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| Database | Microsoft SQL Server |
| Data Visualization | Power BI |
| Data Processing | Power Query, DAX |
| Languages | SQL, DAX |
| Functions | Time Intelligence, Aggregation, Filtering |

---

## 📊 Key Insights

- Track **loan performance** across time and geography.  
- Compare **good vs bad loans** for better risk management.  
- Monitor **fund disbursement and repayments** effectively.  
- Analyze **borrower profiles** based on employment, purpose, and home ownership.  
- Improve **decision-making** through interactive and real-time dashboards.

---

## 🚀 How to Run the Project

1. **Connect SQL Server to Power BI**
   - Open Power BI Desktop  
   - Select **Get Data → SQL Server**  
   - Enter the server and database name  
   - Load or transform data as needed  

2. **Data Modelling**
   - Create relationships and define a **Date Table**  
   - Use **DAX** measures for KPIs and Time Intelligence  

3. **Build Visuals**
   - Add KPIs, charts, and grid views according to the dashboard structure  

4. **Publish the Report**
   - Publish the Power BI report to the Power BI Service for sharing and collaboration  

---

## 🧠 Future Enhancements
- Integration with **Real-Time SQL Data Streaming** for live updates  
- Implementation of **Row-Level Security (RLS)** for user-specific access  
- Predictive analytics using **Machine Learning Models** for loan default prediction  
- Adding **Drillthrough Pages** for borrower-level deep analysis  

---

## 👨‍💻 Author
**Mohammed Asif Ameen Baig**  
*B.Tech in Robotics and Automation Engineering | Data Science & AI Enthusiast*    
- 💬 LinkedIn: [www.linkedin.com/in/mohammedasifameenbaig]
- 🐙 GitHub: [asif684](https://github.com/asif684)

---

