# Financial_Fraud_Detection_using_Machine_Learning_Techniques
In this project, we applied multiple supervised machine learning techniques to the problem of fraud detection using a publicly available simulated payment transactions data. Our aim was to demonstrate how supervised ML techniques can be used to classify data with high class imbalance with high accuracy.

We started by exploring the data using various visualization techniques to gain insights into the patterns of fraudulent and non-fraudulent transactions. We found that fraudulent transactions were more uniformly spread out across time steps, while non-fraudulent transactions were more concentrated in specific time steps. Additionally, we found that the distribution of transaction amounts did not show any conclusive difference between fraudulent and non-fraudulent transactions.

Next, we used multiple supervised learning algorithms like logistic regression, random forest, and XGBoost to classify the fraudulent and non-fraudulent transactions. We used evaluation metrics like accuracy, precision, recall, and F1-score to evaluate the performance of each algorithm. We also used techniques like hyperparameter tuning, cross-validation, and SMOTE to improve the performance of our models.

Our results showed that tree-based algorithms like Random Forest performed better than logistic regression & XGBoost in detecting fraudulent transactions respectively. We also found that SMOTE improved the performance of the models, especially for the logistic regression algorithm.

Overall, our study demonstrated that machine learning techniques can be used effectively to detect fraudulent transactions in large amounts of payment data with high accuracy.
