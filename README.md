# SmartWatch Health Data Analysis

https://docs.google.com/spreadsheets/d/1uDsdgxLwdP8Pe2BQfzC93f5n45ICdo-RXYQkhDK5TVw/edit?usp=sharing

### Project Overview

This project involves cleaning and analyzing smartwatch health data collected from users. The dataset includes metrics like heart rate, blood oxygen levels, step count, sleep duration, activity level, and stress levels. The goal is to preprocess the data, fix inconsistencies, and extract meaningful insights.

### Dataset
The dataset includes:
- User ID: Unique identifier for each user
- Heart Rate (BPM): Recorded heart rate
- Blood Oxygen Level (%): Oxygen level
- Step Count: Number of steps taken
- Sleep Duration (hours): Total sleep duration
- Activity Level: Categorized as active, highly active, Sedentary
- Stress Level: Numeric representation of stress

### Data Cleaning Steps
- Handling missing values by imputation or removal.
- Correcting data type inconsistencies.
- Standardizing categorical labels (e.g., fixing typos in Activity Level).
- Removing or correcting erroneous entries.

### Pivot Table Analysis
Pivot tables were utilized to summarize and extract insights from the dataset efficiently:
- Average Metrics by Activity Level:
Computed mean heart rate, Stress levels and blood oxygen level for different activity levels.

### Dasboard Insights
This project includes a data dashboard visualizing key health metrics:

#### Key Metrics:
- Average Heart Rate: 75.99 BPM
- Average Blood Oxygen Level: 97.85%
- Average Step Count: 6,981.87 steps
- Average Sleep Duration: 6.5 hours

#### Visualizations:
- Distribution of Heart Rate: Histogram to detect abnormal values.
- Step Count vs Sleep Duration: Scatter plot with a trend line.
- Blood Oxygen Level vs Activity Level: Bar chart comparison.
- Stress Levels by Activity Level: Pie chart for distribution.

#### Interactive Features:
- Activity Level Filter: Allows users to analyze trends across different activity levels.
- Trend Analysis: Linear regression applied to sleep duration vs. step count.

### Tools & Technologies
- Google Sheets 
