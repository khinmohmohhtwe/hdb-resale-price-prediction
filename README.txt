# 🏠 HDB Resale Price Prediction in Singapore

This project uses a machine learning model to predict HDB resale flat prices in Singapore using open data from data.gov.sg. The goal is to help understand the factors affecting flat prices and create a predictive model using Random Forest.

---

## 📌 Project Objectives

- Predict resale prices of HDB flats based on features like location, flat type, and age.
- Use feature engineering and one-hot encoding for better accuracy.
- Evaluate the model using RMSE (Root Mean Squared Error).
- Visualize feature importance to understand key price factors.

---

## 📊 Dataset

- **Source**: [HDB Resale Flat Prices (2017 Onwards)](https://data.gov.sg/dataset/resale-flat-prices)
- **Size**: ~100,000 rows
- **Features Used**:
  - `town`, `flat_type`, `floor_area_sqm`, `flat_model`
  - `lease_commence_date`, `remaining_lease`
  - Engineered: `flat_age`, `remaining_lease_years`

---

## 🧪 Model Used

- **RandomForestRegressor** from scikit-learn
- RMSE metric to evaluate model performance

---

## 🔧 Tech Stack

- Python 3.x
- Jupyter Notebook
- pandas, matplotlib, seaborn, scikit-learn

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/hdb-resale-price-prediction.git
   cd hdb-resale-price-prediction
