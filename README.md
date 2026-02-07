# ApplianceEnergy-Usage
Appliance Energy Consumption Prediction using Machine Learning
# Appliance Energy Consumption Prediction using Machine Learning

This project focuses on predicting appliance-level energy consumption using
environmental and sensor data from a smart home setting.

## Problem Statement
Build a machine learning model that predicts future energy consumption and
explains the prediction results using real-world data.

## Dataset
- Appliances Energy Prediction Dataset (Kaggle)
- Contains temperature, humidity, and environmental sensor readings

## Methodology
- Data ingestion and inspection
- Minimal preprocessing (dataset-agnostic)
- Feature engineering
- Model training using CatBoost Regressor
- Evaluation using MAE, RMSE, and R² score
- Model explainability using feature importance

## Results
- MAE ≈ 41
- RMSE ≈ 78
- R² ≈ 0.38

The results indicate meaningful predictive capability on real-world energy data.

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- CatBoost
- Google Colab

## How to Run
1. Open the notebook in Google Colab
2. Upload the dataset
3. Run all cells sequentially

