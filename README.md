# Customer-Churn-Analysis
 📊 Telco Customer Churn Prediction
An End-to-End Machine Learning Project to Identify At-Risk Customers

## 🚀 Project Overview
This project uses a Random Forest Classifier to predict customer churn for a telecommunications company. By identifying customers likely to cancel their service, the business can proactively offer retention incentives, potentially saving thousands in lost revenue.

## 📈 Key Insights
* Contract Type: Customers on Month-to-Month contracts are 4x more likely to churn than those on long-term contracts.
* Tenure: New customers (0-6 months) represent the highest risk group.
* Top Predictor: `TotalCharges` and `MonthlyCharges` were the most significant indicators of churn.

## 🛠️ Tech Stack
* Language: Python 3.10+
* Libraries: Pandas, Scikit-Learn, Seaborn, Matplotlib
* Model: Random Forest (80%+ Accuracy)

## 🏁 How to Run
1. Clone the repo: `git clone https://github.com/YOUR_USERNAME/customer-churn-prediction.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook notebooks/Churn_Analysis_Main.ipynb`
