# Predicting Cryptocurrency Market

Team 7 Details:
1. Sallangi Rahul Narayan, 22/11/EC/052 (Team Leader)
2. Vikas Puniya, 22/11/EC/053
3. Prakhar Srivastav, 22/11/EC/054
4. Saksham Umate, 22/11/EC/055
5. Chavda Bhavy, 22/11/EC/057
6. Ketan Dipak Khandekar, 22/11/EC/058
7. Adarsh Kumar, 22/11/EE/002
8. Devansh Sangule, 22/11/EE/003

## Overview

This repository contains a comprehensive analysis and forecasting pipeline for cryptocurrency time series data. The project leverages data from the G-Research Crypto Forecasting competition dataset, exploring trends, seasonal decomposition, and ARIMA-based modeling for predictive analysis. 

Key features include:  
- Cryptocurrency-specific preprocessing and missing data imputation.  
- Visualization of cryptocurrency performance and correlations.  
- Seasonal decomposition and advanced forecasting with ARIMA models.  
- Evaluation metrics like MAE, MSE, RMSE, and R² for model performance assessment.  

---

## Dataset

The project uses two files:  

1. **`train.csv`**: Contains historical data for multiple cryptocurrencies, including attributes like Open, High, Low, Close, Volume, and Target (15-minute return residue).  
2. **`asset_details.csv`**: Metadata about the cryptocurrencies, including `Asset_ID`, `Weight`, and `Asset_Name`.

---

## How to Run

This project is designed to run on Kaggle. Follow these steps to get started:

1. **Go to Kaggle**:  
   Visit [Kaggle](https://www.kaggle.com) and log in or sign up for an account.

2. **Create a New Notebook**:  
   - Navigate to your Kaggle workspace.  
   - Create a new notebook and ensure the environment has internet enabled.

3. **Upload the Repository Files**:  
   - Upload the script or clone this repository. You can clone it directly using Kaggle's terminal or upload the files manually.

4. **Add the Dataset**:  
   - Link the G-Research Crypto Forecasting dataset to your notebook by adding it as a dataset in the notebook's settings.

5. **Run the Code**:  
   - Execute the notebook cells in order. Adjust any parameters or paths as necessary for your analysis.

---

## Key Functions

### Preprocessing and Visualization
- **`c_time_sub(asset_id, data)`**: Handles missing time intervals and imputes missing values for each cryptocurrency.  
- **Visualization**: Includes tools like correlation heatmaps, performance plots, and seasonal decomposition.

### Forecasting
- **Box-Cox Transformation**: Stabilizes variance in data for better forecasting accuracy.  
- **ARIMA Models**: Used for predicting the future closing prices of cryptocurrencies with parameter optimization for best performance.

### Metrics
- **Model Evaluation**: Metrics like MAE, MSE, RMSE, and R² are used to evaluate forecast quality.

---

## Sample Outputs

- **Cryptocurrency Correlation Heatmap**: Highlights relationships between various cryptocurrencies.
- **Seasonal Decomposition**: Breaks down trends, seasonality, and residuals in time series data.
- **Forecasting Visualizations**: Predicts monthly closing prices with actual vs. forecasted data plots.

---
