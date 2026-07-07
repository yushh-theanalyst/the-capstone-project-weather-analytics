# THE CAPSTONE PROJECT  
## Historical Weather Analytics Dashboard using Power BI


---

## Project Overview

This project is a professional Power BI capstone dashboard built to analyze historical weather data across multiple cities and seasons.

The dashboard focuses on identifying weather patterns related to temperature, rainfall, wind speed, atmospheric pressure, sunshine, snow depth, and wind direction. It uses interactive filters and visual storytelling to make weather data easy to explore and understand.

The goal of this project is to demonstrate practical data analytics skills including data preparation, KPI creation, DAX measures, dashboard design, and insight generation using Power BI.

---

##  Objective

The main objective of this project is to create an interactive weather analytics dashboard that helps users understand:

- How rainfall changes across months
- How wind speed varies over time
- Seasonal patterns in sunshine and snow depth
- Average temperature and pressure trends
- Dominant wind direction distribution
- City and season-based weather performance

---

## Dashboard Pages

### Weather Overview Dashboard

This page provides a high-level summary of the overall weather dataset using key metrics and visual insights.

Key elements include:

- Total cities analyzed
- Average temperature
- Maximum temperature
- Minimum temperature
- Overall weather summary
- City and date-based filtering

---

### Weather Conditions Dashboard

This page focuses on detailed weather condition analysis including rainfall, wind, sunshine, snow, and pressure.

Key visuals include:

- Rainfall trend by month
- Wind speed trend by month
- Sunshine analysis by season
- Snow depth analysis by season
- Dominant wind direction distribution
- Interactive filters for date, city, and season

---

##  Key Performance Indicators

The dashboard tracks the following KPIs:

- Average Temperature
- Total Rainfall
- Average Wind Speed
- Average Pressure
- Maximum Temperature
- Minimum Temperature
- Total Cities

---

## Tools & Technologies Used

- Power BI Desktop
- Power Query
- DAX
- Excel / CSV Dataset
- Data Visualization
- Dashboard Design
- GitHub

---

## Data Preparation

Before building the dashboard, the dataset was prepared and structured for analysis.

Data preparation steps included:

- Checking column data types
- Formatting date fields
- Creating month and season-based analysis
- Handling blank values in wind direction
- Creating calculated columns for wind direction grouping
- Building DAX measures for KPIs
- Preparing the data model for interactive reporting

---

##  DAX Measures Used

Some of the key DAX measures created for this dashboard include:

Avg Temperature = AVERAGE('daily_weather'[avg_temp_c])
Total Rainfall = SUM('daily_weather'[precipitation_mm])
Avg Wind Speed = AVERAGE('daily_weather'[avg_wind_speed_kmh])
Avg Pressure = AVERAGE('daily_weather'[avg_sea_level_pres_hpa])
Total Cities = DISTINCTCOUNT('daily_weather'[city_name])
Max Temperature = MAX('daily_weather'[max_temp_c])

## Key Insights

The dashboard helps answer important weather-related questions such as:

Which months recorded the highest rainfall?
How does wind speed change throughout the year?
Which seasons receive more sunshine?
How does snow depth vary by season?
What is the dominant wind direction in the dataset?
How do temperature, rainfall, wind, and pressure behave across selected cities?

## Dashboard Demo

A short screen recording is included to demonstrate:

Dashboard interactivity
Date filtering
City filtering
Season filtering
KPI updates
Chart interactions
Page navigation
