# Swiggy_Dashboard
📌 Project Title
  
   Swiggy Analytics: End-to-End Data Pipeline & Interactive Dashboard

📝 Short Description
This repository features an end-to-end data analytics project that cleans, processes, and visualizes Swiggy's food delivery data. The project demonstrates a complete data engineering and analytics workflow: transforming messy raw data using Python (Pandas), building a robust connection string to export data into a structured MySQL Database, optimizing database storage, and finally connecting it live to Power BI to build an interactive business dashboard for tracking key performance indicators (KPIs) like revenue, top dishes, and customer ratings.

🛠️ Tech Stack
Data Manipulation & ETL: Python 3.14 (Pandas)

Database & Storage: MySQL Server / MySQL Workbench

Database Connectivity Drivers: SQLAlchemy, PyMySQL / mysql-connector-python, Cryptography

Business Intelligence & Visualization: Power BI Desktop

📊 Data Source
Dataset: Swiggy Restaurant & Orders Dataset (Cleaned_swiggy_Data.csv)

Data Points Included: Order Date (Year, Month, Day), Restaurant Name, Location (City, State), Dish Category (e.g., Recommended, North Indian Gravy), Dish Name, Price, Rating, and Rating Count.

🚀 Key Features
Automated Python ETL Pipeline: Cleaned structural anomalies, handled missing data, and filtered records using Pandas. Used SQLAlchemy to systematically load data frames directly into SQL tables.

Secure & Optimized MySQL Storage: Implemented database connections handling secure modern authentication protocols (caching_sha2_password). Optimized schemas by managing text constraints and handling URL-encoded password characters (%40).

Interactive Cross-Filtering Dashboard: Developed a Power BI report featuring automated cross-filtering where selecting a specific City or Category instantly updates all associated charts.

Dynamic Business KPIs: Built clean, borderless KPI summary cards tracking global metrics like Top Best-Sellers (such as the "Recommended" category), Average Ratings, and Order Volumes.

Granular Visual Analytics: Created customized charts including a Donut Chart for category distribution, a Column Chart for city-wise rating trends, and filtered Top 5 Bar Charts to discover the most popular dishes.
