# Telecom Customer Churn Prediction

🎯 Project Overview
This project aims to predict which customers are going to leave telecom services. By identifying at-risk customers early, a business can take proactive steps to retain them, such as offering them a discount or any offer. 

🛠️ Tech Stack & Concepts
- **Python**: Core programming language.
- **Pandas/NumPy**: Data cleaning and manipulation.
- **SMOTE**: Handled data imbalance (from 27% churn up to 50% for training).
- **Random Forest (Ensemble)**: Built a committee of 100 decision trees for robust prediction.
- **Scikit-Learn**: For model training and evaluation.

📊 Results
- **Overall Accuracy**: 78%
- **Recall for Churners**: 54% (Catching more than half of leaving customers).
- **Key Driver**: **Tenure** was identified as the most significant factor in predicting loyalty.

🚀 How to Run
1. Clone this repo.
2. Install requirements using `pip install pandas scikit-learn imbalanced-learn`.
3. Run the script/notebook.
