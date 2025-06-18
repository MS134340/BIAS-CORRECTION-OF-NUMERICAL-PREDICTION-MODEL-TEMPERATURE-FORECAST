# BIAS-CORRECTION-OF-NUMERICAL-PREDICTION-MODEL-TEMPERATURE-FORECAST

This project addresses the issue of **bias in numerical weather prediction (NWP) models**, particularly in **temperature forecasts**. By leveraging historical weather data and machine learning regression techniques, the project aims to improve the accuracy of forecasts and reduce systematic errors in numerical models.

---

## 📌 Objective

To detect and correct bias in temperature forecasts using machine learning models trained on real-world historical environmental data.

---

## 🔍 Approach

1. **Data Collection**:
   - Real-world temperature forecasts vs. actual observed temperatures
   - Additional features: water density, pressure, humidity, etc.

2. **Data Preprocessing**:
   - Missing value handling (e.g., missing water density)
   - Feature selection and normalization

3. **Modeling**:
   - Applied multiple regression models
   - Chose **Random Forest** as the final model for its superior performance

4. **Evaluation**:
   - Bias quantified and visualized using error metrics
   - Forecasting accuracy improved post-correction

---

## 🧠 Techniques Used

- Linear Regression
- Random Forest Regression
- Feature Engineering
- Error Visualization (e.g., residual plots)

---

## 📊 Results Summary

- **Random Forest** showed the highest predictive accuracy
- Systematic biases in NWP were reduced
- Visual analysis confirmed reduced forecasting error

---

## ⚙️ Technologies
- Python (Jupyter Notebook)
- Libraries: pandas, sklearn, matplotlib, seaborn
- Models: Random Forest, Linear Regression
