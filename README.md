# Air Quality Index (AQI) Prediction using Machine Learning and Deep Learning
This project focuses on predicting Air Quality Index (AQI) using various machine learning and deep learning models, leveraging pollution-related features from multiple datasets. The objective is to evaluate and compare the performance of CNN, XGBoost, and MLP models for AQI regression.

#### Models Implemented
1.  CNN (1D Convolutional Neural Network)
- Input reshaped to 3D for Conv1D layers
-  Mean Absolute Error (MAE): 45.38
-  Root Mean Squared Error (RMSE): 82.59
-  R² Score: 0.68
2.  XGBoost Regressor
-  GPU-accelerated tree-based model
-  Mean Absolute Error (MAE): 43.82
-  Root Mean Squared Error (RMSE): 75.53
-  R² Score: 0.73
 3.  MLP (Multi-Layer Perceptron)
-  Standard dense layers for regression
-  Mean Absolute Error (MAE): 46.87
-  Root Mean Squared Error (RMSE): 81.82
-  R² Score: 0.69

####  Dataset
- Combined from four official files  
  (Each dataset includes pollutants like PM2.5, PM10, NO, NO₂, CO, O₃, SO₂, Benzene, Toluene, and Xylene, used as features for AQI prediction):

    - `city_day.csv`  
    - `city_hour.csv`  
    - `station_day.csv`  
    - `station_hour.csv`



