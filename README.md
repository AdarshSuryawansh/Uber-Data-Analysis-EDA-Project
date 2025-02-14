# 🚖 Uber Data Analysis Project using EDA

## 📄 Overview
This project involves performing **Exploratory Data Analysis (EDA)** on Uber ride data from 2016 to uncover insights and patterns. The dataset provides details about trip start/end times, locations, distances, and purposes, allowing us to explore Uber's usage trends.

## 📊 Dataset
- **Source**: Uber rides dataset from 2016
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
- **Libraries**: pandas, seaborn, matplotlib

## ✅ Conclusion
The analysis revealed key insights into Uber’s usage patterns, highlighting its frequent use for business travel, especially during the evening and night. This project demonstrates the power of **EDA** in turning raw data into actionable insights.
