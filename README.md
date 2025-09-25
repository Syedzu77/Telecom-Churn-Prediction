# Customer Churn Prediction 📊
Machine learning project to predict **telecom customer churn** using the [Kaggle 2020 dataset](https://www.kaggle.com/c/customer-churn-prediction-2020/overview).

----

# Project Overview
Context: Based on the Kaggle 2020 Customer Churn Competition
Problem: Customer churn leads to significant revenue losses in telecom.
Goal: Build predictive models to identify churners and analyze key features influencing churn.
Business Impact: Helps telecom companies design targeted retention strategies.

----

# Results
- **Best Model:** XGBClassifier  
  - Accuracy: **95%**  
  - Recall: **75%**  
- **Key Features Driving Churn:**  
  - `total_day_charge`  
  - `customer_service_calls`  
  - `total_eve_charge`  
  - `total_night_charge`  
  - `international_plan`

👉 Customers with *high charges* and *frequent service calls* are at higher risk of leaving.  

# Repository Structure
├── ChurnPrediction.ipynb # Full workflow: EDA, features, models
├── train.csv # Training dataset
├── test.csv # Test dataset
├── Three_page_report.pdf # Summary of methodology & insights
├── README.md # Documentation

---

## ⚡ Getting Started
Clone repo & install dependencies:
```bash
git clone https://github.com/S-G-001/customer_churn_prediction.git
cd customer_churn_prediction
pip install -r requirements.txt
jupyter notebook ChurnPrediction.ipynb


## 📂 Repository Structure
