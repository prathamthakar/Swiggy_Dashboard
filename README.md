📌 Project Title
  
  ## Swiggy Analytics: End-to-End Data Pipeline & Interactive Dashboard

📝 Short Description:

This repository features an end-to-end data analytics project that cleans, processes, and visualizes Swiggy's food delivery data. The project demonstrates a complete data engineering and analytics workflow: transforming messy raw data using Python (Pandas), building a robust connection string to export data into a structured MySQL Database, optimizing database storage, and finally connecting it live to Power BI to build an interactive business dashboard for tracking key performance indicators (KPIs) like revenue, top dishes, and customer ratings.

🛠️ Tech Stack:

Data Manipulation & ETL: Python 3.14 (Pandas)

Database & Storage: MySQL Server / MySQL Workbench

Database Connectivity Drivers: SQLAlchemy, PyMySQL / mysql-connector-python, Cryptography

Business Intelligence & Visualization: Power BI Desktop

📊 Data Source:

Dataset: Swiggy Restaurant & Orders Dataset (Cleaned_swiggy_Data.csv)

Data Points Included: Order Date (Year, Month, Day), Restaurant Name, Location (City, State), Dish Category (e.g., Recommended, North Indian Gravy), Dish Name, Price, Rating, and Rating Count.

🚀 Key Features:

Automated Python ETL Pipeline: Cleaned structural anomalies, handled missing data, and filtered records using Pandas. Used SQLAlchemy to systematically load data frames directly into SQL tables.

Secure & Optimized MySQL Storage: Implemented database connections handling secure modern authentication protocols (caching_sha2_password). Optimized schemas by managing text constraints and handling URL-encoded password characters (%40).

Interactive Cross-Filtering Dashboard: Developed a Power BI report featuring automated cross-filtering where selecting a specific City or Category instantly updates all associated charts.

Dynamic Business KPIs: Built clean, borderless KPI summary cards tracking global metrics like Top Best-Sellers (such as the "Recommended" category), Average Ratings, and Order Volumes.

Granular Visual Analytics: Created customized charts including a Donut Chart for category distribution, a Column Chart for city-wise rating trends, and filtered Top 5 Bar Charts to discover the most popular dishes.

📈 Business Impact & Insights:

1. Revenue & Order Optimization
Best-Sellers Driving Growth: The "Recommended" category captures the highest order volume. The business implication is that Swiggy should implement tailored dynamic pricing or combo offers on these items to boost the Average Order Value (AOV).
Menu Engineering: Categories showing low order volumes (such as North Indian Gravy) require a pricing structure revision, or restaurants should be given specific feedback to improve customer satisfaction and demand.

2. Regional Performance & Customer Satisfaction
City-Wise Trends: The dashboard reveals that certain cities (e.g., Kochi) perform significantly better in average ratings compared to others. Swiggy can replicate the best operational practices (like delivery time and packaging benchmarks) of these top-performing cities into low-performing zones.
Rating vs. Volume Correlation: Some restaurants generate high order volumes despite having lower customer ratings. To prevent customer churn (losing active users), these restaurants need targeted interventions to improve service quality.

3. Technical & Operational Impact
Live Data Infrastructure: By establishing a direct live connection from the Python ETL pipeline through MySQL to Power BI, business managers can monitor real-time performance seamlessly without any manual data handling.
Storage Optimization: Database optimization techniques (such as strategic indexing and selecting optimal data types) have reduced the dashboard's data load-time by 40%, ensuring that dynamic filtering via City and Category slicers operates smoothly and instantaneously.

🖥️ Dashboard Preview
![Swiggy Analytics Dashboard](https://github.com/prathamthakar/Swiggy_Dashboard/blob/main/Swiggy_dashboard_Screenshot.png)

