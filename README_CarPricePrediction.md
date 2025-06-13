
# 🚗 Car Price Prediction - Regression Analysis

## 📝 Project Objective

This project aims to predict car prices using various regression techniques. A Chinese automobile company is exploring the U.S. market and wants to understand the key factors affecting car prices to plan local manufacturing strategies.

---

## 📊 Dataset

- Source: Provided by an automobile consulting firm
- Features include car specifications, brand, engine type, etc.
- Target: `price`

---

## 🧹 Data Preprocessing

- Loaded and cleaned the dataset
- Handled missing values
- Converted categorical variables using one-hot encoding
- Performed feature scaling (StandardScaler)

---

## 🤖 Models Used

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Support Vector Regressor (SVR)

---

## 🧪 Model Evaluation

Evaluated all models using:

- R-squared (R²)
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

📌 Best Model: **Random Forest Regressor** (based on highest R² and lowest error)

---

## 🔍 Feature Importance

Used model-based feature importance to identify top factors influencing car prices.

---

## 🔧 Hyperparameter Tuning

Performed tuning using GridSearchCV for best model (Random Forest), resulting in improved performance.

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy, Seaborn, Matplotlib
- scikit-learn
- Jupyter Notebook

---

## 📁 How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/car-price-prediction.git

# Open the notebook
car_price_prediction.ipynb
```

---

## 🙋‍♂️ Author

**Abdullah CT**  
PGDM Student | Data Science Enthusiast  
[LinkedIn](https://linkedin.com/in/your-link) | [GitHub](https://github.com/abdullahct)
