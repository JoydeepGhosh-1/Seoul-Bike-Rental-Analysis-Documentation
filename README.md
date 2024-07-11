# Seoul Bike Rental Analysis

This repository contains the analysis and modeling performed on the Seoul Bike Rental dataset. The goal of this project is to explore the dataset, perform regression analysis to predict bike rental counts, and visualize relevant insights.

## Business Context
Currently, rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## Project Overview

### Data Exploration and Analysis
- Loaded and cleaned the dataset.
- Conducted exploratory data analysis (EDA) to understand the distribution and relationships between variables.
- Visualized key trends and patterns in the data.

### Data Preprocessing
- Handled missing values and outliers.
- Performed feature engineering to create new relevant features.
- Selected important features based on correlation and feature importance analysis.

### Model Building
- Split the data into training and testing sets.
- Trained an XGBoost regression model to predict bike rental counts.
- Tuned hyperparameters using RandomizedSearchCV to improve model performance.

### Evaluation
- Evaluated the model using metrics such as Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).
- Achieved an RMSE of 333.09 and an MAE of 206.53 after hyperparameter tuning.

### Visualizations
- Created various plots to visualize data distributions and trends:
  - Histograms for numeric features.
  - Bar plots for categorical features.
  - Line plots to show hourly, monthly, and weekly rental trends.
  - Scatter plots to analyze relationships between humidity and bike rentals.
  - Bar plots for seasonal and weekly average rentals.
  - Line plot for yearly rental trends.

## Key Insights
1. **Humidity vs. Bike Rentals**: As humidity increases, the number of bikers decreases.
2. **Seasonal Trend of Bike Rentals**: Highest rentals occur during the summer, with significant activity in spring and autumn as well.
3. **Day of the Week vs. Bike Rentals**: Rentals are consistent across all days, with a decrease on Sundays.
4. **Yearly Trends of Bike Rentals**: The number of bike rentals has increased significantly over the years, indicating growing popularity and revenue potential.


