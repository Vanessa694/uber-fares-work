# Uber Fares Dataset Analysis Report

**Student Name:** Vanessa Gatete  
**Course:** Introduction to Big Data Analytic INSY 8413  
**Instructor:** Eric Maniraguha  
**Date:** July 25, 2025

---

## 1. Introduction

The purpose of this project is to analyze the Uber Fares Dataset to uncover important patterns and trends related to ride fares, durations, and operational metrics. By examining data such as fare amounts, distances, timestamps, and ride locations, this analysis aims to provide actionable insights into how Uber pricing varies by time, distance, and demand. The insights will be presented through an interactive Power BI dashboard to clearly visualize these patterns and support strategic decision-making.

---

## 2. Methodology

- **Data Collection:** The dataset was downloaded from Kaggle, containing Uber ride fare information with timestamps, locations, distances, and fare amounts.
- **Data Preparation:** The data was loaded into a Pandas DataFrame using Python for cleaning and exploratory analysis.

### Screenshot: Data Loading in Python  
*(Insert screenshot here showing the code or output when loading the dataset into Pandas)*  
![Data Loading](screenshots/code1)

- **Data Cleaning:** Missing values and inconsistencies were identified and handled to ensure accurate analysis.

### Screenshot: Data Cleaning Process  
*(Insert screenshot here showing missing value handling or data cleaning code/output)*  
![Data Cleaning](./screenshots/code2.png)

- **Feature Engineering:** New features like hour, day of week, and peak/off-peak indicators were created to enhance the analysis.

### Screenshot: Feature Engineering Code  
*(Insert screenshot here showing code creating new features like hour, day, peak time, etc.)*  
![Feature Engineering](./screenshots/feature_engineering.png)

- **Visualization:** Cleaned data was imported into Power BI to create dynamic visualizations and dashboards.

### Screenshot: Data Import into Power BI  
*(Insert screenshot showing import of cleaned CSV into Power BI)*  
![Power BI Import](./screenshots/powerbi_import.png)

---

## 3. Data Understanding and Cleaning

- The dataset consists of over 500,000 records, including variables such as fare amount, distance traveled, timestamps, and ride duration.
- Initial data assessment revealed some missing and inconsistent values, which were removed or corrected.
- Outliers in fare amounts were identified using box plots and addressed to avoid skewed analysis.

### Screenshot: Box Plot Showing Outliers  
*(Insert screenshot of box plot visualization identifying outliers in fare amount)*  
![Outliers Box Plot](./screenshots/outliers_boxplot.png)

---

## 4. Exploratory Data Analysis (EDA)

- Descriptive statistics and distribution analysis were performed.

### Screenshot: Descriptive Statistics Output  
*(Insert screenshot of Python output or table showing mean, median, standard deviation, etc.)*  
![Descriptive Statistics](./screenshots/descriptive_statistics.png)

- Visualizations showing fare distribution patterns were created in Power BI.

### Screenshot: Fare Distribution Visualization  
*(Insert screenshot of histogram or box plot visual in Power BI)*  
![Fare Distribution](./screenshots/fare_distribution.png)

- Relationships between fare and distance, and fare and time of day were analyzed.

### Screenshot: Scatter Plot of Fare vs Distance  
*(Insert scatter plot screenshot)*  
![Fare vs Distance](./screenshots/fare_vs_distance.png)

### Screenshot: Time of Day Fare Patterns  
*(Insert line/bar chart showing fares by time of day)*  
![Fare by Time of Day](./screenshots/fare_by_time.png)

---

## 5. Feature Engineering

- Hour, day, month, and peak/off-peak indicators were extracted and encoded.

### Screenshot: Feature Table Preview  
*(Insert screenshot of DataFrame preview with new features added)*  
![Feature Table](./screenshots/feature_table.png)

---

## 6. Power BI Analysis & Dashboard Highlights

- Created interactive visuals analyzing fare trends, ride patterns, and geographic distributions.

### Screenshot: Power BI Dashboard Overview  
*(Insert screenshot showing the full dashboard interface)*  
![Dashboard Overview](./screenshots/dashboard_overview.png)

- Included histograms, time series charts, and maps.

### Screenshot: Geographic Distribution Map  
*(Insert map visualization of ride locations)*  
![Geographic Map](./screenshots/geographic_map.png)

---

## 7. Key Findings

- There is a clear positive correlation between fare amount and distance traveled.
- Peak hours show increased ride volumes and higher fares.
- Weekday rides generally have higher average fares than weekend rides.

---

## 8. Conclusion

The analysis of Uber fares provides valuable insights into fare patterns over time and distance, helping to inform business and operational decisions. Temporal features and demand periods significantly affect fare pricing and ride activity.

---

## 9. Recommendations

- Uber could optimize pricing and driver availability during peak hours to meet demand efficiently.
- Greater fare transparency during surge pricing times may improve customer satisfaction.
- Future studies could include weather data to enhance fare pattern predictions.

---


