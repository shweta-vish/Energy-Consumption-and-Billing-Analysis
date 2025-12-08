##Energy Consumption and Billing Analysis

Overview
This project provides a data-driven analysis of energy consumption and billing patterns, differentiating between Domestic (Residential) and Commercial consumers. The core objective is to uncover key factors and trends that influence electricity usage and cost for each consumer type. The project includes a detailed Jupyter Notebook covering statistical and machine learning models, along with an interactive Power BI dashboard for visual reporting.

Project Files

File Name: EB_dataset.csv
Raw Dataset: Contains historical energy consumption records, billing amounts, number of occupants, and environmental data such as Average Temperature and Cooling Degree Days (CDD).

File Name: final analysis eb.ipynb
Data Analysis Notebook: A complete Jupyter Notebook performing data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning regression modeling (Random Forest, Gradient Boosting). Includes visualizations of model performance and feature importance.

File Name: EBDASH (4).pbix
Interactive Dashboard: A Power BI dashboard that allows users to explore consumption and billing trends, compare consumer types, and examine seasonal/environmental impacts on energy usage.

Key Findings (Analysis Highlights)
1. Domestic Consumption

Strong Predictors: Domestic energy consumption shows strong correlation with measurable factors.

Environmental Influence: Higher Average Temperature and CDD values increase energy usage.

Key Feature: Number of occupants strongly drives baseline consumption.

2. Commercial Consumption

Low Predictability: Commercial usage exhibits weak correlation with the available dataset variables.

Negative R²: ML models perform poorly due to missing influential features.

Implication: Commercial consumption depends on external factors like business type, operating hours, and equipment load, which are not included in the dataset.

Technical Stack & Requirements

Analysis: Python 3.x
Libraries: pandas, numpy, matplotlib, scikit-learn
Visualization: Power BI Desktop (.pbix file)
