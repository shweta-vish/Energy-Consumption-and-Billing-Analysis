# Energy-Consumption-and-Billing-Analysis
Energy Consumption and Billing Analysis
Overview
This project provides a data-driven analysis of energy consumption and billing patterns, differentiating between Domestic (Residential) and Commercial consumers.

The core objective is to uncover key factors and trends that drive electricity usage and cost for each consumer type. This work culminates in a detailed Jupyter Notebook exploring statistical and machine learning models, and an interactive Power BI dashboard for visual reporting.

Project Files
File Name: EB_dataset.csv Description: Raw Dataset: Contains historical energy consumption records, billing amounts, number of occupants, and corresponding environmental data (e.g., Average Temperature, Cooling Degree Days (CDD)).

File Name: final analysis eb.ipynb Decscription: Data Analysis Notebook: A detailed Jupyter Notebook that performs data cleaning, exploratory data analysis (EDA), feature engineering, and implements Machine Learning regression models (Random Forest, Gradient Boosting). It concludes with a visualization of model performance and feature importance.

File Name: EBDASH (4).pbix Dscription: Interactive Dashboard: The final visualization file created in Power BI. It provides an interactive interface for exploring consumption and billing trends, comparing consumer types, and viewing the seasonal/environmental impacts on usage. |

Key Findings (Analysis Highlights)
The machine learning analysis within the Jupyter Notebook revealed distinct differences in consumption drivers between the two segments:

1. Domestic Consumption
Strong Predictors: Domestic energy consumption is highly predictable and significantly correlated with quantifiable factors. The analysis successfully modeled this behavior, identifying a strong positive correlation between consumption and environmental variables (like Average Temperature and CDD).
Key Feature: The number of occupants is a primary feature driving the baseline energy usage.
2. Commercial Consumption
Low Predictability: Unlike domestic usage, commercial consumption showed very low correlation with the available variables, resulting in a poor predictive model (e.g., a negative R² score).
Implication: This suggests that commercial energy consumption is driven by unmeasured factors, such as business type, operational schedules, or equipment load, which are not present in the current dataset.
Technical Stack & Requirements
The project utilizes common data science and visualization tools.

