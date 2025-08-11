🏨 AtliQ Grands Hospitality Analysis

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

1. Occupancy Rate Comparison:

Delhi records the highest weekend occupancy rate (~78%), while Bangalore experiences the lowest weekday occupancy percentage.

The Presidential room category has the highest occupancy rate (59.28%), followed closely by the Standard category at 57.89%.

Weekends witness the highest occupancy rate at ~73%, compared to ~51% on weekdays, indicating stronger guest demand during leisure periods.

2. Revenue Trend:

Mumbai’s Elite rooms generate the highest revenue (₹232M), while Delhi’s Presidential rooms bring in the least (₹60M) among all city–room class combinations.

Weekday revenues contribute 62.6% of total earnings, while weekends account for 37.4%, highlighting stronger revenue generation during weekdays.

Atliq Exotica leads with ₹320.26M in revenue, followed by Atliq Palace at ₹304.08M, whereas Atliq Seasons significantly lags behind with only ₹66.09M, highlighting a substantial performance gap among properties.

Over 40% of revenue comes from the undefined 'Others' category, with MakeYourTrip as the top contributor among named platforms.

3. ADR (Average Daily Rate) Trends:

Atliq Seasons leads in ADR across months, peaking in June 2022, while most other properties, led by Atliq Exotica, remain stable within ₹14.3k–₹15.5k.

Weekdays have a total ADR nearly 2.4 times higher than weekends, accounting for about 70.6% of the overall ADR.

4. Cancellation Patterns:


