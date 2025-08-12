# 🏨 AtliQ Grands Hospitality Analysis

📌 Problem Overview

AtliQ Grands, a leading luxury hotel chain in India, has been operating for over 20 years. Due to aggressive competition and ineffective decision-making, the company has seen a decline in market share and revenue in the luxury/business hotels category.

To reverse this trend, the Managing Director decided to leverage Business & Data Intelligence for more informed and strategic decision-making.

This project performs data extraction, cleaning, exploratory data analysis (EDA), and actionable recommendations to help AtliQ Grands regain market share and profitability.

🎯 Problem Statement

“How can AtliQ Grands use historical booking and revenue data to identify key patterns, improve decision-making, and enhance business performance in the competitive hospitality industry?”

🎯 Objectives

Understand performance trends across different hotels and locations.

Identify factors influencing revenue and guest ratings.

Recommend strategies to improve occupancy, guest satisfaction, and overall profitability.

🛠️ Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)

MySQL (Data storage & querying)

Jupyter Notebook (Development environment)

Excel/CSV (Data storage format)

🗂 Project Workflow

1️⃣ Data Acquisition & Storage

Source: CSV files containing df_rooms, df_hotels, dim_date, fact_aggregated_bookings, fact_bookings data.

Database Creation:

Created a MySQL database named hotel_booking_db.

Imported CSV datasets into MySQL tables for structured querying.

2️⃣ Database to Python Integration

Connected MySQL database to Jupyter Notebook using sqlalchemy-python.

Loaded data into pandas DataFrames for further analysis.

3️⃣ Data Cleaning & Preparation

Removed duplicates.

Handled missing values.

Standardized column names and data formats.

Ensured correct data types for date, numerical, and categorical variables.

Outlier removal using the third standard deviation rule.

4️⃣ Exploratory Data Analysis (EDA)

Univariate Analysis: Studied individual variables (e.g., booking status, room type distribution,Revenue Realized).

Bivariate Analysis: Compared metrics like ADR vs. occupancy, booking channels vs. cancellations, Revenue by room class & city.

Time-Series Trends: Analyzed monthly/yearly booking and revenue patterns.

Correlation Study: Generated heatmaps to identify relationships between numerical variables.

Seasonality Detection: Highlighted high-demand and low-demand periods for pricing strategies.

📊 Key Insights

Atliq Blu has the highest occupancy at 63.14% but generates (₹260M)in revenue, while Atliq Exotica, with 57.85% occupancy, leads revenue at (₹320M). Atliq Seasons shows the lowest occupancy (44.51%) and revenue (₹66M), indicating underperformance.

Mumbai’s Elite rooms lead revenue at ₹232M despite moderate occupancy (~57.6%), while Delhi’s Presidential rooms have the highest occupancy (63.25%) but lower revenue (₹60.5M). This suggests revenue is driven by pricing and demand differences across cities and room classes.

The Presidential room category has the highest occupancy rate (59.28%), followed closely by the Standard category at 57.89%.

Weekdays earn more revenue (₹1.07B) despite lower occupancy (51.8%), while weekends have higher occupancy (74%) but generate less revenue (₹639M).

Mumbai leads in bookings and cancellations, affecting efficiency; Hyderabad and Bangalore have better booking-to-cancellation ratios, while Delhi records fewer bookings.

Atliq Blu leads in customer ratings, indicating strong guest satisfaction, whereas Atliq Seasons’ low rating of 2.30 highlights potential service or quality issues impacting its performance.

“Others” lead bookings but also cancellations. MakeMyTrip has high bookings with fewer cancellations, and offline direct bookings have the lowest cancellations.

Over 40% of revenue comes from the undefined 'Others' category, with MakeYourTrip as the top contributor among named platforms.

Atliq Seasons leads in ADR across months, peaking in June 2022, while most other properties, led by Atliq Exotica, remain stable within ₹14.3k–₹15.5k.

Revenue stayed steady from May to July 2022, peaking in May (₹582M) and slightly dipping in June before recovering in July.




