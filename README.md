# Laptop Price Prediction using Regression Analysis

This project focuses on predicting laptop prices based on various technical specifications using machine learning regression techniques. It includes comprehensive Exploratory Data Analysis (EDA), feature engineering, and the implementation of multiple regression models to achieve accurate price estimation.

## Project Overview

The goal of this project is to build a robust predictive model that can estimate the market price of a laptop given its hardware and software features. This is particularly useful for both consumers looking for fair deals and retailers aiming to price their products competitively.

## Key Features

- **Exploratory Data Analysis (EDA):** In-depth analysis of the dataset to uncover trends, correlations, and insights.
- **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature scaling.
- **Feature Engineering:** Creating new features like Pixels Per Inch (PPI) and extracting information from CPU/GPU specifications.
- **Machine Learning Models:**
  - Simple Linear Regression (Statistical and Gradient Descent approaches)
  - Multiple Linear Regression
  - Advanced Regression techniques (e.g., Ridge, Lasso)
- **Interactive Visualizations:** Using Plotly and Seaborn for dynamic and informative plots.

## Dataset

The dataset (`laptop2.csv`) contains information on 1,303 laptops, including:
- **Company:** Manufacturer (e.g., Apple, HP, Dell)
- **TypeName:** Type of laptop (e.g., Notebook, Ultrabook, Gaming)
- **Ram:** Memory size in GB
- **Weight:** Laptop weight
- **Touchscreen:** Whether the laptop has a touchscreen
- **CpuCompany:** Processor manufacturer
- **ClockSpeed:** CPU clock speed
- **Storage:** SSD, HDD, Flash Storage, and Hybrid capacities
- **GPU:** Graphics card manufacturer
- **Ppi:** Pixels Per Inch (calculated from resolution and screen size)
- **Price:** Target variable (Price in local currency)

## Results

The models were evaluated using R-squared and Mean Squared Error (MSE) metrics. The project demonstrates how different features impact the price and which models perform best for this specific regression task.

## License

This project is open-source and available under the [MIT License](LICENSE).
