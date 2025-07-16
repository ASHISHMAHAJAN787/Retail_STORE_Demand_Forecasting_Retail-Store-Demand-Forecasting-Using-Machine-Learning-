# Retail_STORE_Demand_Forecasting_Retail-Store-Demand-Forecasting-Using-Machine-Learning-


This project demonstrates an end-to-end pipeline for retail sales forecasting using advanced time series analysis and machine learning. The workflow includes data preprocessing, feature engineering, model training and evaluation, and insightful business visualizations.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Data Pipeline](#data-pipeline)
- [Modeling & Results](#modeling--results)
- [Visualizations](#visualizations)
- [Key Insights](#key-insights)
- [How to Run](#how-to-run)
- [Requirements](#requirements)
- [Contributors](#contributors)

---

## Project Overview

- **Goal:** Predict daily sales for multiple stores and products using historical data.
- **Techniques:** Feature engineering, regression models (Linear Regression, Random Forest, XGBoost), hyperparameter tuning, and time series decomposition.
- **Outcome:** Accurate sales forecasts and actionable business insights for inventory and marketing strategies.

---

## Data Pipeline

1. **Data Loading:** Import train and test datasets.
2. **Preprocessing:** Handle missing values, convert date columns, and ensure consistency.
3. **Feature Engineering:** Extract date features and create lag features for temporal patterns.
4. **Exploratory Data Analysis:** Visualize trends, distributions, and correlations.

---

## Modeling & Results

- Trained and compared Linear Regression, Random Forest, and XGBoost models.
- Used GridSearchCV for XGBoost hyperparameter tuning.
- **Best Model:** XGBoost with lowest validation MAE.
- Exported predictions with product names for PowerBI and further analysis.

---

## Visualizations

All result images are available in the `images/` directory.  
**Please ensure you save the following plots as images in the `images/` folder and update the paths if needed.**

### 1. Sales Trends Over Time
![Sales Trends](images/sales_trend.png)

### 2. Distribution of Sales
![Sales Distribution](images/sales_distribution.png)

### 3. Correlation Matrix
![Correlation Matrix](images/correlation_matrix.png)

### 4. Total Sales for Each Store
![Total Sales per Store](images/total_sales_per_store.png)

### 5. Top 10 Sales Dates per Store
![Top 10 Dates per Store](images/top_10_dates_per_store.png)

### 6. Best-Selling Products (Store 1, 2018-03-01)
![Best-Selling Products Pie](images/best_selling_products_pie.png)

### 7. Store 5 Sales Trend
![Store 5 Sales Trend](images/store_5_sales_trend.png)

### 8. Seasonal Decomposition (Store 7)
![Store 7 Seasonal Decomposition](images/store_7_seasonal.png)

---

## Key Insights

- **Seasonality:** Clear monthly cycles and periodic spikes in sales.
- **Top Performers:** Identified best-performing stores and products.
- **Model Performance:** XGBoost outperformed other models after tuning.
- **Business Value:** Results support inventory planning and targeted marketing.

---

## How to Run

1. Clone this repository.
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Place the datasets in the `regression_dataset` folder.
4. Run the Jupyter notebook:
    ```bash
    jupyter notebook "Python Code.ipynb"
    ```
5. View results and visualizations in the notebook or in the `images/` folder.

---

## Requirements

- Python 3.8+
- pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, statsmodels, jupyter

---

## Contributors

- [ASHISH MAHAJAN](https://github.com/ASHISHMAHAJAN787)

---


