# Project Title
- Wild Blueberry Yield Prediction using Machine Learning
  ![dataset-card](https://github.com/user-attachments/assets/d2f212d0-5870-4a91-a5ba-14165618f1dc)
# Objective
- The objective of this project is to predict blueberry crop yield based on agricultural and environmental factors (such as fruit set, fruit mass, seeds, and other related features). The goal is to help in improving farming decisions and pollination strategies.
# Why We Use This Project
- Agricultural optimization: Predicting yield allows farmers to make informed decisions about pollination, resource allocation, and harvesting.
- Environmental impact: Helps understand how pollination influences crop yield.
- Data-driven decisions: Uses statistical and ML models to derive insights from complex biological and environmental interactions.
# Step-by-Step Approach
- Data Import & Cleaning
- Load dataset (WildBlueberryPollinationSimulationData.csv).
- Handle missing values and ensure correct datatypes.
# Exploratory Data Analysis (EDA)
- Shape of dataset.
- Distribution of yield and key features.
- Correlation heatmap between yield and predictors.
- Outlier detection using boxplots & z-scores.
# Feature Selection
- Used SelectKBest with:
- f_regression() (linear correlation).
- mutual_info_regression() (information gain).
# Retained most important predictors: fruitset, fruitmass, seeds.
- Feature Engineering
- Standardization using StandardScaler.
- Split dataset into train (80%) and test (20%).
# Model Training
- Models trained:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
# Techniques applied:
- Cross-validation with RepeatedKFold.
- GridSearchCV for hyperparameter tuning.
# Model Testing
- Evaluation metrics:
- R² Score (goodness of fit).
- Mean Absolute Error (MAE).
- Root Mean Squared Error (RMSE).
# Output
<img width="1387" height="340" alt="Screenshot 2025-08-21 134706" src="https://github.com/user-attachments/assets/9e3cd54e-e355-4e80-8295-46f15ef9e2d6" />

