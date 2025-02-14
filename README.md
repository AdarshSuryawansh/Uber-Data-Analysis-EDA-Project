# Uber-Data-Analysis-EDA-Project
This project focuses on conducting an Exploratory Data Analysis (EDA) of Uber trip data to uncover insights and patterns in user behavior, trip characteristics, and overall service performance. The EDA phase helps to understand the dataset's structure.

#  Title Slide
Title: Uber Data Analysis Project using EDA
Subtitle: Exploring Uber Ride Patterns from 2016
Name: Adarsh Suryawanshi

# Project Overview
Objective: Analyze Uber rides data from 2016 to uncover insights about trip patterns.
Data: Dataset containing trip details like start/end times, locations, distances, and purposes.

# Data Exploration & Preprocessing
Initial Dataset: 1,156 entries with 7 columns.
Data Cleaning:
Handled missing values in the 'PURPOSE' column.
Converted 'START_DATE' and 'END_DATE' to proper date-time format.
Created new features (day, time, month).

# Feature Engineering
## Created additional features:
Day-Night Categorization: Grouping trips by time of day (morning, afternoon, evening, night).
Trip Day: Grouping trips by weekday.
Month: Mapped dates to months for trend analysis.

# Data Visualization – Trip Categories
Bar Plot: Distribution of trips by category (e.g., business vs. personal).
Insight: Majority of trips were business-related.

#  Trip Timing Analysis
Day vs. Night Trips: Bar plot showing when most trips occurred (e.g., evening trips were more frequent).
Insight: Peak ride times were in the evening and night.

# Distance Analysis
Box Plot: Distribution of trip distances.
Insight: Most trips were short-distance, with a few outliers representing longer trips.

# Month-wise and Day-wise Trends
Line Plot: Trend of rides over months.
Bar Plot: Distribution of rides over days of the week.
Insight: Consistent ride activity throughout the year, with slight variations across weekdays.

# Conclusions
## Key Findings:
Business-related trips dominate the dataset.
Most trips are short-distance and occur during the evening or night.
Ride purposes vary, with meetings and errands being common.

# Tools & Libraries
Tools Used: Python
Libraries: pandas, seaborn, matplotlib
