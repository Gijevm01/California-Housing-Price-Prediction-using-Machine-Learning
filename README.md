# California Housing Price Prediction using Machine Learning

## Project Overview

This project predicts California housing prices using Machine Learning techniques.

The objective is to estimate the median house value based on location, demographics, income levels, and housing characteristics. The project demonstrates the complete machine learning workflow from data cleaning and exploration to model training, evaluation, and prediction.

---

## Business Problem

Real estate prices are influenced by many factors such as income, location, population density, and housing characteristics.

The goal of this project is to build a predictive model that can estimate house prices and identify the most important factors affecting property values.

---

## Dataset

California Housing Dataset

Number of records: 20,640

Target Variable:

- median\_house\_value

Features:

- longitude
- latitude
- housing\_median\_age
- total\_rooms
- total\_bedrooms
- population
- households
- median\_income
- ocean\_proximity

---

## Project Workflow

### 1\. Data Cleaning

- Identified missing values
- Replaced missing bedrooms with the median value
- Verified data quality

### 2\. Exploratory Data Analysis (EDA)

Performed:

- Distribution analysis
- Correlation analysis
- Boxplots
- Histograms
- Heatmaps

Key finding:

Median income showed the strongest positive relationship with house value.

### 3\. Feature Engineering

Created additional features:

- rooms\_per\_household
- bedrooms\_per\_room
- population\_per\_household

These engineered features improved model performance.

### 4\. Data Preprocessing

- One\-Hot Encoding for ocean\_proximity
- Feature Scaling with StandardScaler
- Train/Test Split (80/20)

### 5\. Machine Learning Models

Models evaluated:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

### 6\. Model Evaluation

Metrics used:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Results

| Model | R² Score |
| --- | --- |
| Linear Regression | 0.625 |
| Decision Tree | 0.629 |
| Random Forest | 0.816 |

Random Forest achieved the highest predictive accuracy.

---

## Feature Importance

The most influential features were:

1. Median Income
2. Ocean Proximity (Inland)
3. Longitude
4. Latitude
5. Housing Median Age

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit\-Learn
- Jupyter Notebook

---

## Key Learnings

- Data cleaning and preprocessing
- Feature engineering techniques
- Linear Regression fundamentals
- Model comparison and evaluation
- Interpretation of business insights from machine learning models

---

## Future Improvements

- Hyperparameter tuning
- Cross Validation
- XGBoost
- Gradient Boosting
- Deploy model with Streamlit

---

## Author

Martin Gijevski

Data Analytics \| Machine Learning \| Python \| Power BI \| SQL

