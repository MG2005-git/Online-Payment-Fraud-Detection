# Online-Payment-Fraud-Detection
This project presents a comprehensive framework for detecting online payment fraud using machine learning. With effective preprocessing, EDA, model training and evaluation, the Random Forest model demonstrated promising performance.

Online payments have become the most widely used method for financial transactions worldwide. However, this surge in digital payments has also led to a significant increase in payment fraud. The primary objective of this study is to distinguish between fraudulent and legitimate online transactions. For this purpose, we utilize a dataset sourced from Kaggle, containing historical records of both fraudulent and non-fraudulent transactions. By analyzing these patterns, we aim to develop effective techniques for detecting and preventing online payment fraud.


The dataset consists of 10 variables:
* **step**: represents a unit of time where 1 step equals 1 hour
* **type**: type of online transaction
* **amount**: the amount of the transaction
* **nameOrig**: customer starting the transaction
* **oldbalanceOrg**: balance before the transaction
* **newbalanceOrig**: balance after the transaction
* **nameDest**: recipient of the transaction
* **oldbalanceDest**: initial balance of recipient before the transaction
* **newbalanceDest**: the new balance of recipient after the transaction
* **isFraud**: fraud transaction

## Conclusion
* Random Forest obtains the highest score of all using K-fold cross-validation.
* The best performing model is **Random Forest** for identifying fraudulent and non-fraudulent payments, as the AUC is 0.999, which is close to 1. This means it has a good separability measure, and the model has an 99.9% chance of being able to distinguish between positive and negative classes.
