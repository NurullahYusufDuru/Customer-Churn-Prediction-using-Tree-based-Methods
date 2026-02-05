# Customer-Churn-Prediction-using-Tree-based-Methods

# Customer Churn Prediction

This project focuses on predicting customer churn using machine learning techniques. The goal is to identify customers who are likely to leave the service and provide insights that can support retention strategies.

## Dataset
The dataset contains customer-level information including demographic features, service usage, and contract details.  
Key preprocessing steps include:
- Removal of non-informative identifiers (CustomerID)
- Handling missing values in `TotalCharges`
- Encoding categorical variables
- Addressing class imbalance using **SMOTE**

## Methodology
The workflow follows a standard data science pipeline:
1. Exploratory Data Analysis (EDA) for numerical and categorical features  
2. Data preprocessing and feature encoding  
3. Train–test split  
4. Oversampling with SMOTE to handle class imbalance  
5. Model training and comparison  

## Models Used
- Decision Tree Classifier  
- Random Forest Classifier  
- XGBoost (optional comparison)

Among the tested models, **Random Forest** achieved the highest accuracy with default hyperparameters.

## Evaluation
Model performance is evaluated using:
- Accuracy score  
- Confusion matrix  
- Classification report  

## Technologies
- Python  
- pandas, numpy  
- scikit-learn  
- imbalanced-learn (SMOTE)  
- matplotlib, seaborn  

## Conclusion
The results show that ensemble-based methods, particularly Random Forest, perform well in predicting customer churn on imbalanced datasets. This approach can be extended with hyperparameter tuning and cost-sensitive learning for improved real-world performance.
