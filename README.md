# Walmart Sales Prediction Project

## Project Overview
This project aims to predict weekly sales for various Walmart stores using historical sales data. The model accounts for various factors including promotional holidays, economic conditions, and store-specific characteristics, to accurately forecast sales figures.

## Dataset
The dataset includes over 6,400 entries with the following attributes:
- **Store**: The store number.
- **Date**: The week of the sales.
- **Weekly_Sales**: The total sales for the given week.
- **Holiday_Flag**: Whether the week is a special holiday week.
- **Temperature**: The average temperature in the region.
- **Fuel_Price**: Cost of fuel in the region.
- **CPI**: Consumer Price Index.
- **Unemployment**: Unemployment rate.

## Models Used
- **Linear Regression**: Baseline model to predict sales.
- **Polynomial Regression**: Advanced model to capture non-linear trends.
- **Random Forest Regression**: Ensemble method for robust predictions.
- **Decision Tree Regression**: A simple model to interpret complex relationships.

## Key Findings
- The Polynomial Regression model achieved the highest R-squared value of 95.74%, indicating a strong ability to predict future sales.
- Random Forest and Decision Tree models also showed high accuracy, making them suitable for understanding feature importances and decision rules.

## Technologies Used
- **Python**: Main programming language used for the project.
- **Pandas**: Data manipulation and analysis.
- **Scikit-learn**: Machine learning library used for implementing regression models.
- **Matplotlib**: Library used for creating visualizations.
