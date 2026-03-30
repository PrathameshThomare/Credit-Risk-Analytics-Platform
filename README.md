# 🏦 Credit Risk Analytics Platform

## 📌 Project Overview

This project demonstrates an end-to-end credit risk analytics solution built using Azure, SQL, and Power BI. The objective is to analyze borrower behavior, identify default patterns, and provide actionable insights for financial decision-making.

---

## 🏗️ Architecture
Data Source (CSV / API / External DB)
        ↓
Ingestion Layer (Azure Data Factory / Blob Storage)
        ↓
Data Storage (Azure SQL Database - Staging + Final Tables)
        ↓
Data Processing (SQL Transformations, Views, Stored Procedures)
        ↓
Version Control (GitHub)
        ↓
CI/CD Pipeline (Azure DevOps)
        ↓
Semantic Layer (Power BI Dataset)
        ↓
Visualization (Power BI Reports & Dashboards)
        ↓
Automation (Power Automate Alerts)


---

## ⚙️ Tech Stack

- **Azure Data Factory** – Data ingestion pipeline  
- **Azure Blob Storage** – Raw & processed data storage  
- **Azure SQL Database** – Data processing & analytics layer  
- **SQL** – Data transformation & feature engineering  
- **Power BI** – Dashboard & visualization  

---

## 🔄 Data Pipeline

1. Raw loan dataset ingested using Azure Data Factory  
2. Stored in Azure Blob Storage (raw layer)  
3. Loaded into Azure SQL Database (staging tables)  
4. Transformed using SQL into analytics-ready dataset  
5. Connected Power BI to Azure SQL for reporting  

---

## 📊 Dashboard Overview

### 🟦 Credit Risk Overview

![Overview](Screenshot/Screenshot_2026-03-30_003623.png)

---

### 🟪 Loan Performance & Risk Insights

![Performance](Screenshot/Screenshot_2026-03-30_003649.png)

---

## 🧠 Key Features

- Default Risk Analysis  
- Loan Performance Tracking  
- Payment Behavior Analysis  
- Risk Segmentation  
- Financial Metrics Dashboard  

---

## 📈 Key Insights

- Lower credit grades (F, G) show significantly higher default rates  
- Longer loan terms (60 months) have increased risk  
- Payment behavior strongly correlates with default probability  
- Risk segmentation highlights opportunities for model improvement  

---

## 💼 Business Impact

This solution enables financial institutions to:

- Identify high-risk borrowers  
- Monitor loan performance effectively  
- Make data-driven lending decisions  
- Improve risk assessment strategies  

---

## 🚀 Future Enhancements

- Machine Learning model for default prediction  
- Real-time data pipeline integration  
- Advanced credit scoring model  

---

## 👨‍💻 Author

**Prathamesh Thomare**  
Aspiring Data Analyst | SQL | Power BI | Azure  

---
