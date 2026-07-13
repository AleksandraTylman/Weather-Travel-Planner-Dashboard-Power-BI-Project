# Weather Travel Planner Dashboard - Power BI Project

This project focuses on building an interactive Power BI dashboard that helps users identify destinations with weather conditions matching their travel preferences. Using a global weather dataset, the dashboard enables travellers to compare cities worldwide based on temperature, precipitation, humidity, wind speed and weather conditions.

The project was developed as part of the **Mentoring Development Program** organized by the **Wrocław University of Science and Technology Career Office**. This one-to-one mentoring initiative connects students with experienced industry professionals, allowing participants to work on practical projects, receive individual guidance, and develop both technical and professional skills. Throughout the program, regular mentor meetings supported the project development process and helped apply Business Intelligence best practices in a real-world scenario.


## Dataset Overview

- **Source:** https://www.kaggle.com/datasets/syedaeman2212/weather-dataset
- **Content:** 7 original features and 5,475 unique records, enriched with two additional columns created during data preparation (precipitation category column and month column).
- **Purpose:** Enable users to discover travel destinations across the world with weather conditions that best fit their preferences.


## Data Preparation

Data preprocessing and transformation were performed using **Power Query**:

- Data cleaning and validation.
- Data type standardization.
- Creation of custom precipitation categories and a month column used for dynamic filtering.

## Interactive Dashboard

The report uses DAX measures and calculated columns to create dynamic analyses and an interactive user experience. The dashboard contains several interactive visualizations displaying results for the selected month.

### Dynamic KPI Cards

- Average Temperature
- Average Humidity
- Average Wind Speed
- Selected City

### Visualizations

- **Bar Chart** presenting weather condition distribution.
- **Pie Chart** showing precipitation categories.
- **Combined Line Chart** comparing average temperature and average precipitation over time.
- **Interactive Map** with a temperature-based colour scale using conditional formatting.

### Slicers

Users can customize the analysis using interactive slicers:

- City
- Month *(default selection: Current Month)*
- Temperature range

These filters allow users to quickly narrow down destinations according to their preferred weather conditions.

## Technologies Used

- Microsoft Power BI
- Power Query
- DAX (Measures & Calculated Columns)

## Project Outcome

The dashboard provides a practical decision-support tool for travellers planning holidays or business trips. Instead of browsing weather forecasts city by city, users can interactively explore destinations from around the world and identify locations that meet their preferred weather criteria.

The project demonstrates practical Business Intelligence skills, including data preparation, DAX development, interactive reporting and business-oriented data visualisation using Power BI.
