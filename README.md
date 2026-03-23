# Agriculture-Analysis-Power-Bi-Dashboard
Agriculture Analytics Dashboard (AWS+SnowFlake+PowerBI-Dashboard)

Project Overview

This project focuses on analyzing agriculture data using Snowflake and Power BI to derive meaningful insights. The dashboard provides a clear visualization of crop production, rainfall patterns, and seasonal trends to support data-driven decision-making.
________________________________________
Objectives

•	Analyze agricultural data efficiently

•	Identify trends in crop yield, rainfall, and temperature

•	Compare production across locations and seasons

•	Build an interactive and professional dashboard
________________________________________
Tools & Technologies Used

•	Snowflake (Cloud Data Warehouse)

•	Power BI (Data Visualization)

•	SQL (Data Processing)

•	AWS S3 (Data Storage)
________________________________________
Dataset Description

The dataset includes the following fields:

•	Year


•	Location

•	Area

•	Rainfall

•	Temperature

•	Soil Type

•	Irrigation

•	Yields

•	Humidity

•	Crops

•	Price

•	Season

•	Year Group

•	Rainfall Groups
________________________________________
Data Pipeline

1.	Data stored in AWS S3 bucket
2.	Connected to Snowflake using Storage Integration
3.	Data loaded into Snowflake table using COPY INTO
4.	Data cleaned and transformed
5.	Connected Snowflake to Power BI for visualization
________________________________________
Dashboard Features

•	KPI Cards:

o	Total Production

o	Average Rainfall

o	Total Area

o	Average Price

•	Visualizations:

o	Bar Chart (Production by Location)

o	Line Chart (Yearly Trends)

o	Pie Chart (Crop Distribution)

o	Column Chart (Rainfall vs Yield)

o	Matrix (Heatmap-style for Location vs Crops)

•	Filters (Slicers):

o	Year

o	Location

o	Season

o	Soil Type

o	Rainfall Groups
________________________________________
Key Insights

•	Identified top-performing locations based on yield

•	Observed relationship between rainfall and production

•	Seasonal impact on crop yield

•	Crop-wise contribution to total production
________________________________________
How to Run the Project

1.	Upload dataset to AWS S3
2.	Configure Snowflake Storage Integration
3.	Create database, schema, and table
4.	Load data using COPY INTO command
5.	Connect Power BI to Snowflake
6.	Build dashboard using visuals
________________________________________
Future Enhancements

•	Add predictive analysis (ML models)

•	Include real-time data updates

•	Improve dashboard interactivity

Author

Vidyashree Kotri BSC(Cs) Student | Aspiring Data Analyst
