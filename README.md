# 🏡 House Price Prediction with Linear Regression (Manual Gradient Descent)

This project is a beginner-level implementation of linear regression where I manually coded the core formulas. Like the cost function, gradient calculation, and gradient descent updates to gain a deeper understanding about how these concepts work under the hood.

As I am just starting my machine learning journey, I wanted to practice by implementing these algorithms myself instead of using built-in libraries for training.

---

## 📁 Dataset

The dataset (`house_prices_dataset.csv`) contains:

- `area` — size of the house  
- `price` — price of the house

---

## 🛠️ What's Implemented

- Feature scaling (input scaled by dividing by 1000)  
- Manual cost function (Mean Squared Error)  
- Manual gradient calculation  
- Gradient descent loop for parameter optimization  
- Prediction on test data  
- Evaluation using MSE, RMSE, MAE, and R² score  
- Visualization of results

---

## 📊 Model Summary

- Training on first 70 rows  
- Testing on remaining data  
- Learning rate and iterations chosen experimentally

---
## 📈 Example Output
Test MSE: 5.7947
Test RMSE: 2.4072
Test MAE: 1.9325
R² Score: 0.9995 → Model explains 99.95% of the variance
