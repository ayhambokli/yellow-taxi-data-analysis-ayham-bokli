# 🚕 Yellow Taxi Data Analysis — LYNX Data Analyst Assignment

---

## 🎯 Objective
This project analyzes the **NYC Yellow Taxi Trip Records dataset** to identify operational trends, customer behavior, and revenue insights.  
The task was provided as part of the **Data Analyst assignment for LYNX Broker Germany**.

The analysis covers:
- Data cleaning and preprocessing  
- Feature engineering (time, distance, financial metrics)  
- Demand & Operations Analysis
- Revenue & Pricing Analysis
- Airport Trip Analysis
- Customer & Tip Behavior Analysis
- Spatial Demand & Route Revenue Analysis
- Visual insights and management recommendations  

---

## 📂 Dataset Information
The dataset is a public sample of the **NYC Taxi and Limousine Commission (TLC)** trip records.  
It contains trip-level information including timestamps, locations, fares, tips, and surcharges.

🔗 **Dataset Source:**  
[NYC TLC Yellow Taxi Data (GitHub)](https://github.com/m-gauer/NYC_TLC_Yellow_Taxi_Data)

📘 **Data Dictionary:**  
📄 **Data Dictionary:**  
[Data Dictionary – Yellow Taxi Trip Records (March 18, 2025)](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

---

## ⚙️ Tools & Libraries
This analysis was developed in **Python** using the following core libraries:
- `pandas` — data cleaning & transformation  
- `matplotlib` & `seaborn` — data visualization  
- `numpy` — numerical computation  

All code runs within a standard Jupyter Notebook environment.

---

## 📊 Analysis Overview
### 1️⃣ Data Cleaning & Preparation
- Handled missing and inconsistent values  
- Converted datetime columns and extracted time-based features  
- Removed unrealistic distances and negative fare values  

### 2️⃣ Feature Engineering
- Created derived metrics such as `trip_duration_min`, `fare_per_mile`, and `tip_rate`  
- Added congestion indicators and time-based demand profiles  

### 3️⃣ Exploratory Insights
- **Demand & Operations Analysis
- **Revenue & Pricing Analysis
- **Airport Trip Analysis
- **Customer & Tip Behavior Analysis
- **Spatial Demand & Route Revenue Analysis

---

## 💡 Key Findings

| Category | Insight |
|-----------|----------|
| **Demand** | Most trips are concentrated in Manhattan and airport areas (JFK, LaGuardia). |
| **Revenue** | Airport and Midtown routes generate the highest total revenue. |
| **Payment Behavior** | Credit card payments dominate and show higher average tips. |
| **Trip Efficiency** | Short-distance trips (<3 miles) are most frequent and operationally efficient. |
| **Congestion** | Higher congestion surcharges correlate with longer average fares. |

---

## 🧭 Recommendations

- **Optimize Demand & Operations:** Increase driver availability during peak hours and use demand forecasts for better fleet scheduling.  
- **Dynamic & Distance-Based Pricing:** Apply surge pricing during peak times and adjust long-trip fares to improve revenue per mile.  
- **Customer & Tip Optimization:** Promote digital payments, reward high tip performance, and focus service training on evening shifts.  
- **Spatial Strategy:** Deploy more drivers in Midtown and airport zones while expanding coverage in underrepresented boroughs.  
- **Strategic Impact:** Boosts revenue per trip, improves operational efficiency, and enhances customer satisfaction.

- **Strategic Impact:** Improves trip profitability, driver efficiency, and customer satisfaction — enabling sustainable revenue growth and stronger market presence.


---

## 📘 Notebook
All steps, explanations, and visualizations are contained in the Jupyter Notebook:  
[`Ayham_Bokli_Yellow_Taxi_Data_Analysis.ipynb`](./Ayham_Bokli_Yellow_Taxi_Data_Analysis.ipynb)

---

### 🏁 Summary
This analysis demonstrates an end-to-end data analytics workflow — from cleaning and feature engineering to deriving actionable business insights.  
The focus was on clarity, reproducibility, and interpretability for non-technical stakeholders.
