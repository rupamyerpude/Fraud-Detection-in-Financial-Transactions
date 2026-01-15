# Fraud-Detection-in-Financial-Transactions


A machine learning–based fraud detection project developed to identify fraudulent financial transactions using historical transaction data. The project focuses on data understanding, handling class imbalance, and evaluating model performance using appropriate metrics.

---

## Objective
To build a baseline model that can identify fraudulent transactions and provide insights that help reduce financial risk.

---

## Dataset Overview
- Large-scale financial transaction dataset (~6 million records)
- Binary target variable: `isFraud`
- Highly imbalanced data (fraud cases are rare)

---

## Approach
- Data understanding and exploratory analysis
- Identification of severe class imbalance
- Feature preparation and categorical encoding
- Baseline model development using Logistic Regression
- Model evaluation using confusion matrix, precision, recall, and F1-score

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## Key Learnings
- Importance of recall over accuracy in fraud detection
- Handling imbalanced datasets
- Interpreting model results from a business perspective
- Translating data insights into fraud prevention strategies

---

## Results
The baseline model achieved reasonable precision with moderate recall, highlighting the need for further improvement using advanced techniques and imbalance-handling methods.

---

## Future Improvements
- Improve recall using resampling techniques (SMOTE)
- Try tree-based models
- Feature engineering for behavioral patterns
- Real-time fraud detection implementation

---

## Author
Developed as a self-learning and academic data science project by a B.Tech Artificial Intelligence student.

---

## License
For educational purposes only.
