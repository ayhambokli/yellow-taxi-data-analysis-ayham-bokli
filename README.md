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
See the included file:  
[`data_dictionary.pdf`](./data_dictionary.pdf)

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
| **Demand** | Trips are heavily concentrated in Manhattan and airports |
| **Payment** | Credit card payments dominate and show higher tipping rates |
| **Revenue** | JFK and LaGuardia routes are top contributors to revenue |
| **Congestion** | High congestion surcharges correlate with longer average fares |
| **Trip Efficiency** | Short urban routes (<3 miles) occur most frequently |

---

## 🧭 Recommendations
- **Dynamic pricing optimization:** Adjust pricing for high-demand routes (JFK ↔ Midtown).  
- **Driver allocation:** Increase availability in peak evening hours and airport zones.  
- **Customer insight:** Encourage digital payments for higher tipping potential.  
- **Data integration:** Combine trip data with weather or event datasets for demand forecasting.  

---

## 📘 Notebook
All steps, explanations, and visualizations are contained in the Jupyter Notebook:  
[`Ayham_Bokli_Yellow_Taxi_Data_Analysis.ipynb`](./Ayham_Bokli_Yellow_Taxi_Data_Analysis.ipynb)

---

### 🏁 Summary
This analysis demonstrates an end-to-end data analytics workflow — from cleaning and feature engineering to deriving actionable business insights.  
The focus was on clarity, reproducibility, and interpretability for non-technical stakeholders.
