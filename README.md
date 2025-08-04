# Fraud Detection ML Project

A complete machine learning pipeline for **detecting fraudulent financial transactions** using Python. This project covers data preprocessing, missing value and outlier handling, multicollinearity checks, model selection (Random Forest & Logistic Regression), model evaluation, feature importance analysis, and infrastructure-level fraud prevention recommendations.

## 🚩 Features

- **Data Cleaning:** Handles missing values, outliers, and multicollinearity.
- **Feature Engineering:** Encodes categorical variables and selects significant predictors.
- **Class Imbalance Handling:** Employs SMOTE oversampling for rare fraud cases.
- **Modeling:** Trains Random Forest and Logistic Regression models for binary classification.
- **Performance Evaluation:** Provides classification reports, confusion matrices, ROC curves, and AUC scores.
- **Feature Importance:** Highlights key drivers of fraud detection.
- **Best Practices:** Suggests actionable, infrastructure-level measures for fraud prevention.
- **Effectiveness Evaluation:** Details strategies for assessing real-world prevention impact.

## 📁 Project Structure

Fraud_Detection_Task_Sahil.ipynb # Jupyter notebook with full ML workflow
Fraud.csv # Input transaction dataset (not included)
README.md # This documentation file



## 🛠️ How to Run

1. **Clone the repository:**  
git clone https://github.com/yourusername/fraud-detection-ml-project.git
cd fraud-detection-ml-project



2. **Install required libraries:**  
Ensure Python 3 is installed. Install dependencies with:
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn statsmodels



3. **Open and run the notebook:**  
Launch `Fraud_Detection_Task_Sahil.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab and execute each cell sequentially.

## 📊 Key Results

- **Top Predictive Factors:**  
- Original and new balances on sender and receiver accounts  
- Transaction amount  
- Transaction type  
- **Model Performance:**  
- High recall and ROC-AUC for fraud class after class balancing.
- **Business Insights:**  
- Model feature importances and predictions match real-world fraud behavior.

## 🛡️ Fraud Prevention Recommendations

- Real-time transaction monitoring
- Multi-factor authentication (MFA)
- Data encryption in transit and at rest
- Activity/event logging & anomaly alerting
- ML-based transaction risk scoring
- Daily/per-transaction limits; stricter for new users or large transfers
- Device and location tracking for new/suspicious logins
- Regular tuning and updating of fraud models
- Behavioral profiling for users and entities
- Ongoing infrastructure and security assessments

## 📈 Effectiveness Evaluation

- Monitor KPIs: fraud detection rate, recall, precision, false positives
- Review user reports and feedback on blocked accounts or errors
- Compare incident rates and model metrics before and after process updates
- Use A/B testing for evaluating new fraud rules or system changes

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!  
Please open an issue or submit a pull request.

## 📝 License

For educational use only.  
Please verify individual library and data licenses for production or commercial deployments.
