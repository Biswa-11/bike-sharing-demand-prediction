# Bike Sharing Demand Prediction

## Project Overview
This project aims to predict **bike sharing demand** based on various environmental and seasonal features.  
It uses **data preprocessing, feature engineering, and regression modeling** to identify the key factors influencing demand.

## Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, Statsmodels

## Exploratory Data Analysis (EDA)
- Data inspection & cleaning  
- Visualization of demand patterns across time, weather, and seasons  
- Correlation heatmap to understand feature relationships  

## Feature Engineering
- Applied **Recursive Feature Elimination (RFE)** to select the most significant features  
- Reduced dimensionality from 15 features to **7 key predictors**

## Model Used
- **Linear Regression**  
  - Built using both **Scikit-learn** and **Statsmodels**  
  - Compared model coefficients and feature importance  

## Evaluation Metrics
- **R² Score** for model performance  
- Coefficient analysis to interpret feature impact

## Results
- Identified **top 7 features** significantly impacting bike demand  
- Achieved a reasonable R² score, showing that regression can explain a large portion of demand variation  

## Future Improvements
- Experiment with advanced models:
  - Random Forest Regressor
  - Gradient Boosting
  - XGBoost
- Hyperparameter tuning for better performance
- Deploy the model using Flask/Streamlit for real-world usability

## Repository Structure
bike-sharing-demand-prediction/
│── Bike_Sharing_Demand_Prediction.ipynb
│── README.md
│── requirements.txt
│── images/
│── data/


## Dataset
https://drive.google.com/uc?id=1EqLwOEdMk-lK5BDa2LD7hzNcki_liE5s

---
Developed by **Biswajit**  
Aspiring Data Scientist | Skilled in ML & Data Analytics
