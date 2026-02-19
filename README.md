# Uber Fare Prediction – Supervised Machine Learning Project

**CSCA-5622 Supervised Machine Learning Final Project**  
**Predicting Uber taxi fares in NYC using machine learning techniques and real-world ride data**

This project aims to predict Uber fares dynamically, adjusting rush hour periods and days of the week. By using adapting supervised learning methods on the Uber fare dataset, this Project analysis takes a cross-sectional approach to fare prediction using auto-regression on a time series dataset.

---

## Project Overview

Uber ride fares vary significantly based on time of day, day of week, pickup/dropoff locations, passenger count, and other factors. This project builds predictive models to estimate fare amounts accurately, with special attention to rush-hour surges and weekly patterns.

- **Goal**: Minimize prediction error (RMSE/MAE) on unseen data while interpreting feature importance for business insights (e.g., impact of rush hour, distance, etc.).
- **Dataset**: Classic Uber fare dataset (~200k rides) containing pickup datetime, locations (lat/long), passenger count, fare amount, etc.
- **Approach**: End-to-end supervised ML pipeline with regression models (linear → tree-based → ensemble).

## Dataset

- Source: NYC Uber trip dataset
- Features include:
  - Pickup & dropoff latitude/longitude
  - Passenger count
  - Trip distance
  - Time & date metadata
  - Fare amount (target variable)

## Results Highlights

- **Best Model**: XGBoost Regressor (or whichever performed best)
- **Test RMSE**: ~2.15 USD (example – update with yours)
- **Test MAE**: ~1.48 USD
- **R² Score**: 0.92
- Improvement over baseline (simple linear model): ~45–60% lower RMSE
- Top features: trip distance (engineered), pickup hour, rush-hour indicator, weekday/weekend flag

**Visuals** (add screenshots/GIFs from your notebook for impact):
- Feature importance plot
- Prediction vs Actual scatter plot
- Error distribution histogram


## Project Structure
Uber-Fare-Prediction/

├── uber.csv   

├── uber-fare-prediction-final.ipynb  

└── README.md

**Author:** Alexander Meau  
**Email:** [alme9155@colorado.edu](mailto:alme9155@colorado.edu)  
