Financial Fraud Intelligence & Risk Monitoring Portal
📌 Project Overview
This project addresses the critical challenge of identifying fraudulent credit card transactions within highly imbalanced financial datasets. By leveraging XGBoost for predictive modeling and Tableau Desktop for business intelligence, this end-to-end pipeline transforms raw transaction data into actionable insights for risk investigators.

🛠️ Tech Stack
Language: Python 3.13

Libraries: Pandas, NumPy, Scikit-Learn, XGBoost, Matplotlib, Seaborn

Visualization: Tableau Desktop

Techniques: Robust Scaling, Random Under-sampling (SMOTE-ready), Confusion Matrix Analysis

🚀 Key Features
Advanced Predictive Modeling: Utilized XGBoost (Extreme Gradient Boosting) to handle non-linear patterns in financial data.

Data Preprocessing: Implemented RobustScaler to neutralize the impact of extreme outliers in transaction amounts and time-series data.

Class Imbalance Management: Solved the 0.17% fraud-to-genuine ratio through strategic under-sampling to ensure high model recall.

Interactive Risk Dashboard: Developed a multi-view Tableau portal that allows investigators to filter transactions by "Fraud Probability" scores (>0.80).

📊 Dashboard Insights
The final Tableau dashboard includes three critical components:

Model Accuracy Grid: A 2x2 Confusion Matrix validating the True Positive and False Positive rates.

Probability Distribution: A histogram showing the model's confidence levels for both genuine and fraudulent classes.

High-Risk Investigation List: A real-time "Hit List" providing transaction details for immediate manual review.

📈 Performance Results
Recall: ~95% (Optimized to minimize False Negatives in fraud detection).

Data Volume: Processed and analyzed 284,000+ transactions.

Efficiency: Reduced manual audit volume by 90% by focusing on high-probability clusters.

📂 Project Structure
Plaintext
├── data/
│   └── creditcard.csv             # Raw dataset from Kaggle
├── notebooks/
│   └── fraud_detection_v1.ipynb    # Python cleaning and XGBoost modeling
├── output/
│   └── fraud_detection_results.csv # Processed data with AI predictions
└── dashboard/
    └── Fraud_Intelligence.twbx    # Tableau Packaged Workbook


👤 Author
Naveen Shaji

BCA Graduate | Aspiring Data Scientist

