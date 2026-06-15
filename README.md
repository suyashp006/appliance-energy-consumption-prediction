# Appliance Energy Consumption Prediction

## Project Overview

This project predicts household appliance energy consumption using machine learning techniques. The objective is to identify the environmental and indoor factors that influence energy usage and build predictive models that can help optimize energy efficiency.

---

## Business Problem

Energy consumption is a major concern for households and utility providers. Accurately predicting appliance energy usage helps:

- Reduce electricity costs
- Improve energy efficiency
- Support smart home automation
- Assist energy management systems

---

## Dataset

Dataset: Appliance Energy Prediction Dataset

The dataset contains:

- Indoor temperature measurements
- Indoor humidity measurements
- Outdoor weather conditions
- Appliance energy consumption
- Date and time information

Target Variable:

- Appliances (Energy Consumption)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn

---

## Project Workflow

### 1. Data Loading

- Imported appliance energy dataset
- Performed initial inspection

### 2. Data Preprocessing

- Converted date column into datetime format
- Extracted:
  - Hour
  - Day
  - Month
- Removed original date column

### 3. Exploratory Data Analysis (EDA)

Performed:

- Distribution Analysis
- Correlation Heatmap
- Temperature vs Energy Consumption Analysis
- Feature Relationship Exploration

### 4. Feature Engineering

Created time-based features:

- Hour
- Day
- Month

### 5. Model Building

Implemented multiple regression models:

#### Linear Regression

Baseline model for performance comparison.

#### Random Forest Regressor

Tree-based ensemble model for improved prediction accuracy.

#### Support Vector Regressor (SVR)

Advanced regression model using kernel methods.

### 6. Hyperparameter Tuning

Used GridSearchCV to optimize Random Forest parameters.

### 7. Model Evaluation

Evaluation Metrics:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

### 8. Model Interpretation

- Feature Importance Analysis
- Residual Analysis
- Actual vs Predicted Visualization

---

## Key Findings

- Random Forest outperformed Linear Regression and SVR.
- Hyperparameter tuning improved model performance.
- Temperature and humidity variables significantly influence energy consumption.
- Time-based features contributed to prediction accuracy.

---

## Visualizations

The project includes:

- Energy Consumption Distribution
- Correlation Heatmap
- Outdoor Temperature vs Energy Usage
- Feature Importance Plot
- Actual vs Predicted Plot
- Residual Distribution

---

## Folder Structure

```text
appliance-energy-consumption-prediction/
│
├── notebook/
│   └── Predicting Appliance Energy Consumption In Household.ipynb
│
├── data/
│   └── energydata_complete.csv
│
├── images/
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   ├── actual_vs_predicted.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Future Improvements

- XGBoost Regression
- LightGBM
- Time-Series Forecasting Models
- Feature Selection Techniques
- Deployment using Streamlit

---

## Author

Suyash Patil

Aspiring Data Analyst | Data Scientist | Data Engineer
