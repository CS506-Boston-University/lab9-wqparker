[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WMTTf3io)
# Linear Regression Lab

## Description
This project applies regression methods to historical CO₂ and global temperature anomaly data.  
The goal is to model long-term trends, evaluate regression assumptions, and perform short-term forecasting.
---

## Workflow

1. **Load and preprocess data**
   - Import annual atmospheric CO₂ and global temperature anomaly datasets
   - Restrict dataset to post-1959 for consistent annual coverage

2. **Fit linear regression models**
   - CO₂ vs Year
   - Temperature vs Year

3. **Run regression diagnostics**
   - Residuals vs Year
   - QQ-plots for normality check
   - Statsmodels OLS output (coefficients, significance, R², Durbin-Watson, etc.)

4. **Fit polynomial (quadratic) regression models**
   - Expand features using Year²
   - Compare linear vs quadratic behavior

5. **Forecast**
   - CO₂ levels for the next 10 years
   - Temperature anomalies for the next 20 years

6. **Chain models (CO₂ → Temperature)**
   - Forecast CO₂ using the Year → CO₂ model
   - Use predicted CO₂ values to forecast temperature

---

