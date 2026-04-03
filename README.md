# 🚲 Smart City Bike Sharing Analysis

## 📌 Project Overview
This project analyzes a smart city bike-sharing dataset containing station-level information such as location, capacity, availability, and operational status. The goal is to monitor bike supply and demand, enabling better operational efficiency and decision-making.

---

## 🎯 Project Objectives
- Analyze station capacity and bike availability across contracts  
- Identify underutilized and overutilized stations  
- Support data-driven bike rebalancing decisions  
- Build interactive dashboards for performance monitoring  
- Enable predictive insights for demand trends  

---

## 📂 Data Source
The dataset includes:
- Station details (name, address, contract city)  
- Geographic coordinates (latitude, longitude)  
- Availability metrics (bikes and stands)  
- Operational status (OPEN/CLOSED)  
- Timestamp of last update  

---

## 🛠️ Tools & Technologies
- Microsoft Excel – Data loading  
- Power Query – Data cleaning and transformation  
- Power BI – Data modeling, DAX, and visualization  

---

## 🧹 Data Pre-Processing
- Converted data types (boolean, integer, datetime)  
- Split position into latitude and longitude  
- Handled missing values and validated data  
- Standardized text fields (OPEN/CLOSED)  
- Created calculated columns (occupancy & availability rate)  
- Removed duplicates using latest timestamp  

---

## 🧩 Data Modeling
- Implemented Star Schema  
- Fact Table: Fact_Bike_Status  
- Dimension Tables: Dim_Station, Dim_Contract, Dim_Date, Dim_Status  
- Established relationships using primary and foreign keys  

---

## 🔍 Exploratory Data Analysis
- Distribution of stations across contracts  
- Bike and stand availability trends  
- Operational status comparison  
- Identification of top/bottom stations  
- Geographic analysis using map visuals  

---

## 📊 Key Visualizations
- KPI Cards (Total Stations, Availability %)  
- Bar Charts (Contract comparison)  
- Line Charts (Trend analysis)  
- Maps (Station locations)  
- Ranking visuals (Top/Bottom stations)  

---

## 💡 Key Insights
- Some stations frequently run out of bikes  
- High-demand areas show imbalance in distribution  
- Certain stations are underutilized  
- Availability varies across contracts  
- Operational status impacts performance  

---

## ✅ Recommendations
- Implement bike rebalancing strategies  
- Set alerts for empty/full stations  
- Prioritize maintenance for closed stations  
- Optimize station capacity based on demand  
- Monitor KPIs using dashboards  

---

## ▶️ How to Use
1. Load dataset into Excel or Power BI  
2. Clean data using Power Query  
3. Build data model (fact & dimension tables)  
4. Create DAX measures  
5. Develop dashboards  
6. Analyze insights for decision-making  

---
