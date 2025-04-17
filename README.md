# SmartWatch Health Data Analysis

https://docs.google.com/spreadsheets/d/1uDsdgxLwdP8Pe2BQfzC93f5n45ICdo-RXYQkhDK5TVw/edit?usp=sharing

This Link contains Cleaned, Analysed and Visualization of the data

## Project Overview

This project involves cleaning and analyzing smartwatch health data collected from users. The dataset includes metrics like heart rate, blood oxygen levels, step count, sleep duration, activity level, and stress levels. The goal is to preprocess the data, fix inconsistencies, and extract meaningful insights.

## Dataset
The dataset includes:
- User ID: Unique identifier for each user
- Heart Rate (BPM): Recorded heart rate
- Blood Oxygen Level (%): Oxygen level
- Step Count: Number of steps taken
- Sleep Duration (hours): Total sleep duration
- Activity Level: Categorized as active, highly active, Sedentary
- Stress Level: Numeric representation of stress

## Data Cleaning Steps
- Handling missing values by imputation or removal.
- Correcting data type inconsistencies.
- Standardizing categorical labels (e.g., fixing typos in Activity Level).
- Removing or correcting erroneous entries.

## Analysis Performed
### Descriptive Statistics
- Average, median, min, max, and standard deviation of heart rate.
- Count of records by activity level.
  ### Correlation Analysis
  - Heart Rate vs Blood Oxygen Level
  - Heart Rate vs Step Count

### Pivot Table Analysis
- Stress Level, Heart Rate, and Blood Oxygen Level grouped by Activity Level

### Visual Dashboard
- KPIs (Heart Rate, Oxygen Level, Step Count, Sleep Duration)
- Distribution Chart (Heart Rate)
- Scatter Plot (Step Count vs Sleep Duration with trendline)
- Bar Chart (Oxygen Level by Activity)
- Pie Chart (Stress Level by Activity)


## Dasboard Insights
This project includes a data dashboard visualizing key health metrics:

### Key Metrics:
- Average Heart Rate: 75.99 BPM
- Average Blood Oxygen Level: 97.85%
- Average Step Count: 6,981.87 steps
- Average Sleep Duration: 6.5 hours

## Key Insights
- Sedentary users had slightly higher average stress levels than active ones.
- Step count and sleep duration showed a weak positive correlation, meaning people who walked more tended to sleep slightly longer.
- Heart rate remained fairly consistent across activity levels — which was surprising and could indicate the need for time-based data to see peaks.
- Blood oxygen levels were stable and didn't differ much by activity type, likely because it fluctuates less in daily activity.
  
## Tools & Technologies
- Google Sheets 
