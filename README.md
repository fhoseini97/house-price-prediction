
markdown
Copy
Edit
# 🏠 House Price Prediction

This project aims to predict house prices using various machine learning models, focusing on the Kaggle "House Prices: Advanced Regression Techniques" competition. The final model uses **XGBoost** and achieves an RMSE of approximately **25072**.

## 📂 Project Structure

house-price-prediction/
├── notebooks/ # Jupyter notebooks (EDA, preprocessing, training)
├── houseprices.csv # Final submission file
├── README.md # Project overview
├── requirements.txt # Required Python packages
└── .gitignore # Files to ignore in Git

yaml
Copy
Edit

## 🔍 Problem Statement

Given various features of homes (e.g., size, year built, neighborhood), the goal is to predict their final sale price.

---

## 📊 Models Used

- Linear Regression
- Ridge Regression
- Random Forest
- **XGBoost (final model)**

---

## 🧪 Evaluation Metric

Root Mean Squared Error (RMSE) on log-transformed sale prices.

---

## 📁 Dataset

- Source: [Kaggle - House Prices](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- Files:
  - `train.csv`
  - `test.csv`

---

## ⚙️ How to Run

### 1. Clone the repo
```bash
git clone https://github.com/fhoseini97/house-price-prediction.git
cd house-price-prediction
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Jupyter notebook
bash
Copy
Edit
jupyter notebook notebooks/House_Prices.ipynb
✅ Final Model Performance
Model	RMSE (CV)
Linear	~29665
Ridge	~29418
Random Forest	~28978
XGBoost	~25072 ✅

📦 Requirements
See requirements.txt

📬 Submission
The final submission is stored in houseprices.csv, formatted for Kaggle with columns:

Id

SalePrice
