# 🚖 Uber Data Analysis Project using EDA

## Introduction
Uber Technologies, Inc., commonly referred to as Uber, is an American multinational transportation company that provides ride-hailing services, courier services, food delivery, and freight transport. It is headquartered in San Francisco, California, and operates in approximately 70 countries and 10,500 cities worldwide. It is the largest ridesharing company worldwide with over 150 million (15 Crores) monthly active users and 6 million (60 Lakhs) active drivers and couriers. It facilitates an average of 28 million (2.8 Crore) trips per day and has facilitated 47 billion (4700 Crore) trips since its inception in 2010.Uber generated $37.2 billion revenue in 2023

## 📄 Overview
This project involves performing **Exploratory Data Analysis (EDA)** on Uber ride data from 2016 to uncover insights and patterns. The dataset provides details about trip start/end times, locations, distances, and purposes, allowing us to explore Uber's usage trends.

## 📊 Dataset
- **Source**: Uber rides dataset 
- **Size**: 1,156 rows, 7 columns
- **Key Features**:
  - `START_DATE`, `END_DATE`: Start and end times of each trip
  - `CATEGORY`: Trip type (Business, Personal)
  - `START`, `STOP`: Locations of the trip
  - `MILES`: Distance traveled
  - `PURPOSE`: Purpose of the trip (e.g., Meeting, Errand)

## ⚙️ Process

### 🧹 Data Preprocessing
- Handled missing values, particularly in the `PURPOSE` column.
- Converted the `START_DATE` and `END_DATE` columns to **datetime** format.
- Created new features like `time`, `day`, `month`, and `day-night` to assist in the analysis.

### 📈 Data Visualization
- **Trip Categories**: Business trips dominate the dataset.
- **Trip Purposes**: Common purposes include meetings, errands, and customer visits.
- **Time of Day**: More trips were taken during the evening and night.
- **Distance Distribution**: Most trips were under 10 miles, with a few long-distance trips.

### 🔑 Key Insights
- **Business Trips**: Majority of the trips were for business purposes, suggesting Uber is widely used for work travel.
- **Time Trends**: Evening and night trips were the most frequent.
- **Trip Length**: Short-distance trips were common, with a few outliers representing longer trips.

## 📊 Visualizations
- **Bar Plots**: To show the distribution of trip categories and purposes.
- **Box Plots**: To visualize the spread of trip distances.
- **Line Plots**: Month-wise trends in Uber trips.

## 🛠 Technologies Used
- **Language**: Python
- **Libraries**: pandas, numpzy, seaborn, matplotlib

## Questions  to  analysis the uber data
- **1)** In which category do people book the most Uber rides?
- **2)** For which purpose do people book Uber rides the most?
- **3)** At what time do people book cabs the most from Uber?
- **4)** In which months do people book Uber rides less frequently?
- **5)** On which days of the week do people book Uber rides the most?
- **6)** How many miles do people usually book a cab for through Uber?

## ✅ Conclusion
The analysis revealed key insights into Uber’s usage patterns, highlighting its frequent use for business travel, especially during the evening and night. This project demonstrates the power of **EDA** in turning raw data into actionable insights.
