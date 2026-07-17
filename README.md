# 🚲 Ford GoBike Trip Data - Exploratory Data Analysis

## 📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on **1.86 million Ford GoBike trips** recorded across the San Francisco Bay Area throughout **2018 (January–December)**. The goal is to uncover usage patterns, rider behavior, and station demand trends that can help optimize bike distribution, pricing strategy, and marketing decisions.

## 🎯 Business Objective
To analyze a full year of Ford GoBike trip data to identify usage patterns by time, location, and user type, and generate actionable insights that support data-driven business decisions around fleet management and rider growth.

## 📂 Dataset
- **Source:** Ford GoBike monthly trip data (Jan–Dec 2018)
- **Size:** 1,863,721 rows × 16 columns
- **Key fields:** trip duration, start/end time, start/end station, bike ID, user type (Subscriber/Customer), rider birth year, gender, bike-share-for-all flag

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn

## 🔍 Approach
1. **Data Wrangling** – Combined 12 monthly files, cleaned missing values, and engineered new features (trip duration in minutes, rider age, hour/day/month of trip, weekend flag).
2. **Univariate, Bivariate & Multivariate Analysis** – 15 visualizations covering trip duration, ride volume by hour/day/month, user type & gender distribution, station popularity, and more.
3. **Correlation Analysis** – Heatmap and pair plot of numeric variables.
4. **Business Recommendations** – Derived from patterns in commute behavior, station demand, and seasonal trends.

## 📊 Key Insights
- Ride volume peaks sharply at **8–9 AM and 5–6 PM on weekdays**, confirming commute-driven usage.
- **~85% of trips** are made by Subscribers; only ~15% by casual Customers.
- Subscribers take shorter, consistent trips; Customers take longer, more variable (leisure-style) trips.
- A small set of central stations account for a disproportionate share of pickups/drop-offs.
- Ride volume and trip duration both rise in warmer months and dip in winter.

## 💡 Business Recommendations
- Prioritize bike rebalancing at high-traffic stations before peak commute hours.
- Run weekend/leisure promotions to convert Customers into Subscribers.
- Schedule fleet maintenance during low-demand winter months.
- Investigate unusually long trips as potential lost/damaged bikes.

## 📁 Repository Contents
- `Sample_EDA_Submission_Template.ipynb` – Full analysis notebook with code, 15 visualizations, and written insights.

## ✍️ Author
Akanksha Singh
