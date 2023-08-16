# 💳 Credit Card Fraud Detection using Linear Regression 🥷💻

This fraud detection dataset is a popular public dataset from Kaggle that provides users with the ability to execute different ML models and evaluate results. The binary classification taking place is on the variable "CLASS" that contains two features {0 - Valid Transactions} and {1 - Fraud Transactions}. 

The dataset presents a real-world characteristic in that the data is imbalanced. During script execution, I aim to show you how I went about my ETL processes and implemented different data augmentation techniques to balance the data. My goal was to create a model that performed better with balanced data, regarding F1 score and Balanced Accuracy.

The results yeilded that both resampling techniques positively impacted the models performance in regard to F1 score and Balanced Accuracy. While there may be signs of overfitting (especially in the SMOTE LR Model), the goal was to positively impact selected metrics to improve model performance.
