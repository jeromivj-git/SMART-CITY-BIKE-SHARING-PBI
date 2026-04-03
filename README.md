🚲 Smart City Bike Sharing Analysis
📌 Project Overview

This project analyzes a smart city bike-sharing dataset containing station-level information such as location, capacity, availability, and operational status. The data enables monitoring of bike supply and demand, supporting operational efficiency, reporting, and decision-making for urban mobility systems.

🎯 Project Objectives
Analyze station capacity and bike availability across different contracts
Identify underutilized and overutilized stations
Enable data-driven decision-making for rebalancing bikes
Build interactive dashboards for monitoring system performance
Support predictive analysis for future demand trends
📂 Data Source

The dataset consists of bike-sharing station data including:

Station details (name, address, contract city)
Geographic coordinates (latitude, longitude)
Availability metrics (bikes and stands)
Operational status (OPEN/CLOSED)
Timestamp of last update
🛠️ Tools & Technologies
Microsoft Excel – Data loading and initial inspection
Power Query – Data cleaning and transformation
Power BI – Data modeling, DAX calculations, and dashboards
🧹 Data Pre-Processing
Converted data types (boolean, integer, datetime)
Split position field into latitude and longitude
Handled missing values and validated numeric fields
Standardized text fields (OPEN/CLOSED, trimmed spaces)
Created calculated columns (occupancy rate, availability rate)
Removed duplicate records using latest timestamp
🧩 Data Modeling
Designed a Star Schema model
Central fact table: Fact_Bike_Status
Dimension tables: Dim_Station, Dim_Contract, Dim_Date, Dim_Status
Established relationships using primary and foreign keys
Optimized for efficient querying and reporting
🔍 Exploratory Data Analysis (EDA)
Analyzed distribution of stations across contracts
Evaluated bike and stand availability trends
Compared operational status across stations
Identified top and bottom performing stations
Explored geographic patterns using location data
📊 Key Visualizations
KPI cards (Total Stations, Bikes Available, Utilization %)
Bar charts for contract-level comparison
Line charts for time-based trends
Maps for geographic distribution of stations
Ranking visuals for station performance
💡 Key Insights
Certain stations frequently experience low bike availability
High-demand areas show imbalance in bike distribution
Some stations remain underutilized despite high capacity
Availability patterns vary significantly across contracts
Operational status impacts overall system performance
✅ Recommendations
Implement bike rebalancing strategies across stations
Introduce automated alerts for empty or full stations
Prioritize maintenance for frequently closed stations
Optimize station capacity based on demand trends
Monitor KPIs through real-time dashboards
▶️ How to Use
Load the dataset into Excel or Power BI
Apply data cleaning steps using Power Query
Build the data model with fact and dimension tables
Create DAX measures for KPIs and analysis
Develop dashboards to visualize insights
Use insights for operational and strategic decision-making
