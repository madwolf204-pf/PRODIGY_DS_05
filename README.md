# PRODIGY_DS_05

# US Traffic Accident Analysis and Data Insights

### Overview

This repository contains an exploratory data analysis (EDA) project focused on the vast US Accidents Dataset from Kaggle, which spans traffic incidents across 49 states from 2016 to 2023.

The primary goal of this analysis, detailed in the Traffic_accident.ipynb notebook, is to uncover patterns, trends, and key contributing factors associated with traffic accidents, providing actionable insights for public safety officials and urban planners.


### Dataset

The project utilizes the US Accidents Dataset. This dataset contains approximately 7.7 million accident records collected via various APIs that provide streaming traffic incident data from sources like US and state departments of transportation, law enforcement, and traffic sensors.

## 📂 Dataset
- **Source**: [US Accidents Dataset on Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)  
- **Description**: This dataset provides a record of traffic accidents across the US, including attributes such as  
  - Accident severity  
  - Location (city, state, coordinates)  
  - Weather and road conditions  
  - Time of occurrence   

### Key Data Attributes Analyzed:

- Time and Location: Accident timestamps, coordinates (Latitude/Longitude), and proximity to various points of interest (e.g., junctions, railroads).

- Environmental Factors: Weather condition, visibility, and temperature at the time of the accident.

- Accident Severity: A numerical scale (1 to 4) indicating the impact of the accident.

- Temporal Patterns: Trends based on time of day, day of the week, and month.


### Analysis Methodology

The analysis is conducted entirely within the Traffic_accident.ipynb Jupyter Notebook.


#### Key Exploratory Steps:

* Data Loading and Cleaning: Initial inspection, handling of missing values, and conversion of data types (especially time and location fields).

* Geospatial Analysis: Visualizing accident density across the United States to identify major hotspots.

* Temporal Analysis: Investigating how accident frequency varies with time of day (e.g., rush hour), day of the week, and year-over-year trends.

* Weather Impact: Analyzing the relationship between severe weather conditions and accident occurrences.

* Severity Distribution: Examining the distribution of accident severity levels and determining common features associated with high-severity incidents.


### Key Findings (Based on Notebook Snippet)

The analysis yielded several important insights, including:

  * Accident Severity: The majority of accidents fall under severity level 2, suggesting that most reported incidents are non-life-threatening.

  * Time of Day: Accidents are most frequent during morning rush hour, likely due to increased commuter traffic.

  * Weather Conditions: Surprisingly, most accidents occurred in fair weather, suggesting that non-weather factors like driver behavior and congestion are primary drivers.
