⚡ Energy Consumption and Billing Analysis
🔍 Overview

This project provides a data-driven analysis of electricity consumption and billing patterns for both Domestic (Residential) and Commercial consumers.

The main objective is to identify the key factors that influence monthly energy usage and cost. The project includes a detailed Jupyter Notebook performing statistical and machine learning analysis, along with an interactive Power BI dashboard for visual exploration.

📁 Project Files
1. EB_dataset.csv

Description:
Raw dataset containing historical energy consumption, billing amounts, number of occupants, consumer type, and environmental variables (e.g., Average Temperature, Cooling Degree Days).

2. final analysis eb.ipynb

Description:
A complete Jupyter Notebook that includes:

Data cleaning & preprocessing

Exploratory Data Analysis (EDA)

Feature engineering

Machine learning regression models (Random Forest, Gradient Boosting)

Model evaluation and feature importance visualizations

3. EBDASH.pbix

Description:
Interactive Power BI dashboard that visualizes:

Consumption vs. billing trends

Differences between Domestic and Commercial consumers

Seasonal/environmental impacts

Feature relationships and usage patterns

⭐ Key Findings (Analysis Highlights)
1. Domestic Consumption

Strong Predictors: Domestic energy use showed a high correlation with environmental variables such as temperature and Cooling Degree Days (CDD).

Occupants Matter: Household size significantly influences baseline consumption levels.

Result: Predictive models performed well for this segment.

2. Commercial Consumption

Low Predictability: Commercial usage showed very weak or no correlation with the available variables.

Negative R²: Machine learning models performed poorly, indicating missing influential features.

Implication: Commercial consumption depends on other operational factors (business type, machinery load, working hours), not captured in this dataset.

🛠️ Technical Stack & Requirements

Analysis: Python 3.x
Libraries:

pandas

numpy

matplotlib

scikit-learn

Visualization:

Power BI Desktop (.pbix file)

▶️ How to Reproduce the Analysis
1. Clone the repository
https://github.com/shweta-vish/Energy-Consumption-and-Billing-Analysis
cd energy-consumption-analysis

2. Run the Notebook

Open final analysis eb.ipynb in Jupyter Notebook, JupyterLab, or VS Code to walk through the full analysis.
https://drive.google.com/file/d/1Aa7ZtMJRfkdz-7NIKMvq4H0eX-fTPDkg/view?usp=drive_link

3. View the Dashboard

Open EBDASH.pbix using Power BI Desktop to explore interactive visual insights.
https://drive.google.com/file/d/1zzMavR76WgP8d4ZuYmATWzsHnXxkgiiV/view?usp=drive_link
