# Exploratory Data Analysis (EDA) for Bird Observation Data

## Overview
This repository contains an Exploratory Data Analysis (EDA) of bird observation data. The analysis focuses on data cleaning, preprocessing, and visualizations to uncover patterns and relationships between species observations and environmental factors.

## 1. Data Cleaning and Preprocessing
- Handle missing data and standardize observational metrics.
- Filter relevant columns for analysis (e.g., species, environmental factors, temporal data).
- Consolidate data from forest and grassland units into comparable formats.

## 2. Exploratory Data Analysis (EDA)
### **Temporal Analysis**
- **Seasonal Trends**: Analyze the `Date` and `Year` columns to detect patterns in bird sightings across different seasons or years.
- **Observation Time**: Study `Start_Time` and `End_Time` to determine if specific time windows correlate with higher bird activity.

### **Spatial Analysis**
- **Location Insights**: Group data by `Location_Type` (e.g., Grassland) to identify biodiversity hotspots.
- **Plot-Level Analysis**: Compare observations across different `Plot_Name` values to see which plots attract more species or specific kinds of birds.

## 3. Species Analysis
- **Diversity Metrics**: Count unique species (`Scientific_Name`) observed and their distribution across `Location_Type`.
- **Activity Patterns**: Check the `Interval_Length` and `ID_Method` columns to identify the most common activity types (e.g., Singing).
- **Sex Ratio**: Analyze the `Sex` column to understand the male-to-female ratio for different species.

## 4. Environmental Conditions
- **Weather Correlation**: Explore how `Temperature`, `Humidity`, `Sky`, and `Wind` impact observations, such as the number of birds or their distances.
- **Disturbance Effect**: Assess the impact of `Disturbance` (e.g., slight effect) on bird sightings.

## 5. Distance and Behavior
- **Distance Analysis**: Evaluate the `Distance` column to identify species typically observed closer or farther from the observer.
- **Flyover Frequency**: Examine the `Flyover_Observed` column to detect trends in bird behavior during observation.

## 6. Observer Trends
- **Observer Bias**: Analyze data by `Observer` to check if specific individuals report more observations or certain species.
- **Visit Patterns**: Evaluate the `Visit` column to see how repeated visits affect species count or diversity.

## 7. Conservation Insights
- **Watchlist Trends**: Use the `PIF_Watchlist_Status` and `Regional_Stewardship_Status` to identify trends in species that are at risk or require conservation focus.
- **AOU Code Patterns**: Study the distribution of species based on their `AOU_Code` to correlate with regional or national conservation priorities.

## Visualizations
The analysis includes various visualizations to support insights:
- **Histograms & Boxplots**: Distribution of numerical variables.
- **Line & Bar Charts**: Temporal trends in bird sightings.
- **Scatter Plots**: Relationship between environmental conditions and bird activity.
- **Heatmaps**: Correlation between multiple variables.



