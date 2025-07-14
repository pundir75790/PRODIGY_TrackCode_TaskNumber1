# PRODIGY_TrackCode_TaskNumber1
Linear Regression model to predict house prices using square footage, bathrooms, and bedrooms
# 🏠 House Price Prediction using Linear Regression

This machine learning project uses **Linear Regression** to predict house sale prices based on key features like:

- **GrLivArea** (above-ground living area in sq ft)
- **BedroomAbvGr** (number of bedrooms above ground)
- **TotalBathrooms** (a custom feature combining full and half baths)

The model was trained on the **Ames Housing Dataset** (from Kaggle) and achieves an **R² score of ~0.63**, meaning it explains around **63% of the variance in house prices** using just a few features.

---

## ✅ Features
- 📊 Data cleaning & feature engineering (`TotalBathrooms`)
- 📈 Trained a `LinearRegression` model from scikit-learn
- 📉 Evaluated with `Mean Squared Error` and `R² Score`
- 📍 Visualized actual vs predicted house prices
