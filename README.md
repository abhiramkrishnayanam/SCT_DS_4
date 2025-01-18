# SCT_DS_4
# README: Traffic Accident Dataset Analysis

## Overview
This project involves the exploratory data analysis (EDA) and visualization of a traffic accident dataset to uncover trends and contributing factors related to accidents. The dataset contains various features such as time, day of the week, driver characteristics, vehicle details, accident dynamics, and casualty details.

The primary objectives of this analysis are:
- To identify patterns related to road conditions, weather, and time of day.
- To visualize accident hotspots and contributing factors.
- To analyze trends in accident severity, causes, and demographics.

## Dataset Description
The dataset includes the following key columns:
- `Time`: The time of the accident.
- `Day_of_week`: The day the accident occurred.
- `Age_band_of_driver`: Age group of the driver involved.
- `Sex_of_driver`: Gender of the driver.
- `Driving_experience`: Experience level of the driver.
- `Type_of_vehicle`: Type of vehicle involved in the accident.
- `Area_accident_occured`: Area type (e.g., urban, residential).
- `Cause_of_accident`: The primary cause of the accident.
- `Accident_severity`: Severity level (slight, serious, fatal).
- `Number_of_vehicles_involved`, `Number_of_casualties`: Numerical details of the accident.

## Steps Performed

### 1. Data Cleaning
- Removed duplicate rows and handled missing values.
- Standardized categorical data entries for consistency.
- Extracted useful features (e.g., `Hour` from `Time`).

### 2. Exploratory Data Analysis (EDA)
#### Patterns Analysis:
- **Time and Day**:
  - Analyzed accidents by hour and day of the week to identify peak times and high-risk days.
- **Driver Characteristics**:
  - Investigated accident trends by driver age, gender, and driving experience.
- **Vehicle and Road Factors**:
  - Assessed accident frequency by vehicle type and area type.
- **Accident Causes and Severity**:
  - Studied common causes and their impact on accident severity.

### 3. Data Visualizations
#### Visualizations Generated:
- **Accidents by Hour**:
  - Bar plot showing peak accident times during the day.
- **Accidents by Driving Experience**:
  - Analysis of accidents based on the driver’s experience level.
- **Vehicle Type and Area**:
  - Accident trends categorized by vehicle type and area of occurrence.
- **Reason**:
  -  No distancing is the main reason of accidents.


### 4. Key Insights
- Accidents are more frequent during specific times of the day, typically rush hours.
- Younger(18-30) drivers are more prone to accidents.
- Common causes include speeding, improper turns, and pedestrian errors.
- Certain vehicle types (e.g., motorcycles, automobiles) are more involved in accidents.
- No distancing is the main reason of accidents.
## Tools and Libraries Used
- **Python**: For data cleaning, analysis, and visualization.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: For generating visualizations.

## Future Work
- Integrating geospatial analysis using latitude and longitude (if available) to create detailed heatmaps.
- Building predictive models to forecast accident risks based on historical patterns.
- Adding machine learning techniques to classify accident severity.

## Conclusion
This project demonstrates how EDA and visualizations can provide valuable insights into traffic accident trends.

