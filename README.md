# House Price Prediction

A regression project that predicts median housing prices based on location, demographics, and property features.

## Dataset
California Housing Dataset (sklearn built-in / Kaggle)

## Tech Stack
- Python, pandas, NumPy
- scikit-learn (Linear Regression, cross-validation)
- XGBoost
- Matplotlib, Seaborn

## ⚙️ How It Works
1. Load and explore the dataset (EDA)
2. Visualize feature correlations with heatmap
3. Apply log transformation on skewed features
4. Train Linear Regression and XGBoost models
5. Evaluate with R² score, MAE, RMSE
6. Cross-validate for reliability

## 📊 Results
- XGBoost R² Score: ~0.83
- Key predictors: median income, location (lat/long), house age

## 🚀 Run It
Open `house_price_prediction.ipynb` in Google Colab and run all cells.
