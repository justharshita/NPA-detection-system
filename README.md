# 📊 NPA Early Warning Analytics System

## 🔹 Problem Statement
In fintech and lending businesses, identifying potential Non-Performing Assets (NPAs) early is critical to reduce financial risk. Traditional methods rely heavily on manual analysis and often detect defaults too late.

This project builds an analytics system to identify high-risk loan accounts **3–6 months in advance** using structured data pipelines and dashboard insights.


## 🔹 Objective
- Build an end-to-end data pipeline for loan data
- Generate analysis-ready datasets
- Track key financial risk KPIs
- Enable early identification of high-risk customers


## 🔹 Data Pipeline Architecture
The project follows a **Bronze → Silver → Gold** layered ETL approach:

- **Bronze Layer:** Raw loan and transaction data
- **Silver Layer:** Cleaned and transformed data
- **Gold Layer:** Aggregated, analysis-ready datasets


## 🔹 Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn)
- **SQL concepts** (joins, aggregations, filtering)
- **Excel** (data validation & sanity checks)
- **Data Pipeline Design (ETL)**
- **Dashboarding (Python)**


## 🔹 Key Features
- Automated ETL pipeline for data processing  
- Risk segmentation of customers  
- KPI tracking for loan performance  
- Early warning system using classification model  


## 🔹 Key KPIs Tracked
- Default Rate (%)  
- Loan Aging Buckets  
- High-Risk Customer Count  
- Segment-wise Risk Distribution  


## 🔹 Key Insights
- Customers with high loan exposure show increased default probability  
- Early warning signals can be detected months before actual default  
- Risk varies significantly across customer segments  


## 🔹 Business Impact
- Enables proactive risk management  
- Reduces manual effort in identifying risky accounts  
- Improves decision-making for lending strategies  

---

## 🔹 Project Structure

NPA-Detection-System/
│
├── app/                # Dashboard application
├── data/               # Bronze, Silver, Gold datasets
├── models/             # Saved ML models
├── src/                # Pipeline and configurations
├── run_pipeline.py     # Main pipeline script
├── requirements.txt
└── README.md
