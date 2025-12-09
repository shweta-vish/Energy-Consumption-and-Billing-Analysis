# Energy Consumption and Billing Analysis
# Overview

This project delivers a comprehensive, data-driven analysis of electricity consumption and billing trends, comparing Domestic (Residential) and Commercial consumers.

The objective is to identify the major factors influencing monthly electricity usage and cost. The analysis is performed using a detailed Jupyter Notebook with statistical and machine learning models, along with an interactive Power BI dashboard for visual insights.

# Project Files
1. EB_dataset.csv

Description: Raw Dataset
Contains historical energy consumption values, billing amounts, number of occupants, consumer type, and environmental indicators (e.g., Average Temperature, Cooling Degree Days).

2. final analysis eb.ipynb

Description: Data Analysis Notebook
A complete Jupyter Notebook performing:

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Feature engineering

Machine Learning regression models (Random Forest, Gradient Boosting)

Model evaluation and feature-importance visualization

3. EBDASH.pbix

Description: Power BI Dashboard
Interactive dashboard showcasing:

Consumption vs. billing trends

Differences between Domestic and Commercial consumers

Seasonal and environmental impacts

Feature relationships and usage patterns

# Key Findings
Domestic Consumers

Strong Predictors: Domestic energy usage showed high correlation with environmental factors such as temperature and Cooling Degree Days (CDD).

Occupants Influence: Household size significantly drives baseline energy usage.

Result: Models performed accurately for Domestic consumption.

Commercial Consumers

Low Predictability: Very weak or no correlation with available variables.

Negative R²: Regression models failed to capture patterns.

Reason: Commercial usage depends on external operational factors (business type, machinery load, hours), not included in the dataset.

# Technical Stack
Analysis (Python 3.x)

pandas

numpy

matplotlib

scikit-learn

Visualization

Power BI Desktop (.pbix)

# How to Reproduce
1. Clone the Repository
https://github.com/shweta-vish/Energy-Consumption-and-Billing-Analysis

2. Run the Notebook

Open final analysis eb.ipynb using Jupyter Notebook, JupyterLab, or VS Code.
Notebook Link:
https://drive.google.com/file/d/1Aa7ZtMJRfkdz-7NIKMvq4H0eX-fTPDkg/view?usp=drive_link

3. View the Dashboard

Open EBDASH.pbix in Power BI Desktop.
Dashboard Link:
https://drive.google.com/file/d/1zzMavR76WgP8d4ZuYmATWzsHnXxkgiiV/view?usp=drive_link
