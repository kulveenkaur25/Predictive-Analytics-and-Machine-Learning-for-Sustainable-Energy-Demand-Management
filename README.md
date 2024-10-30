# Predictive-Analytics-and-Machine-Learning-for-Sustainable-Energy-Demand-Management
This project focuses on predictive analytics to help the energy company eSC in South Carolina anticipate and manage peak energy demand during hot summer months. By analyzing temperature and energy usage data, we developed a forecasting model and recommendations to mitigate electricity consumption spikes.

--Project Overview

Global warming has led to rising temperatures, causing increased electricity consumption, especially in the summer. This project utilizes data science and machine learning techniques to forecast energy demand during extreme heat and suggests actionable steps for eSC to reduce consumption peaks.

--Objectives

**Predict Energy Demand**: Build a predictive model to forecast hourly energy demand based on historical weather and energy usage data.
**Provide Recommendations**: Analyze consumption patterns and offer suggestions to reduce energy demand through technology and infrastructure changes.

--Technologies and Tools Used

**Languages**: R, Python
**Libraries**: Shiny, ggplot2, caret
**Machine Learning Models**: Linear Regression, Support Vector Machines, Neural Networks

--Data Sources

**House Information**: Static data on houses, including location and construction details.
**Energy Consumption Data**: Monthly energy usage records for July.
**Weather Data**: Hourly weather data for various counties, converted to Eastern Daylight Time (EDT).

--Key Steps

**Data Collection and Preparation**:
Created a pipeline to integrate house, energy, and weather data.
Aggregated consumption and weather data by county and hour.
**Data Analysis**:
Identified a strong linear relationship between temperature increases and energy consumption.
Analyzed consumption patterns by day and week to detect peak demand trends.
**Modeling**:
Developed multiple predictive models, selecting linear regression for its high accuracy (adjusted R² = 0.8909).
Tested additional models, including SVM and neural networks, which had lower predictive performance.
**Prediction and Visualization**:
Predicted hourly energy demand for July under a simulated 5°C temperature rise.
Built an interactive Shiny app to visualize demand trends across counties.

--Recommendations

**Insulation Improvements**: Encourage enhanced insulation standards to reduce energy usage per household.
**Renewable Energy**: Advocate for solar panel installation to offset peak energy demands.

--Conclusion
This project provides eSC with a proactive approach to managing energy demand during hot weather conditions, contributing to sustainable energy management through data-driven insights and technology.
