# Summary:

The analysis focuses on credit card fraud detection using a dataset generated from a deep learning model trained on Credit Card Fraud Detection. It involves data exploration, model training, and result submission for the competition. The primary objective is to predict the 'Class' variable, indicating whether a transaction is fraudulent or not. The analysis includes logistic regression and random forest models, with an emphasis on handling imbalanced classes.

Dataset:
- train.csv: The training dataset with 'Class' as the target variable.
- test.csv: The test dataset where participants predict 'Class.'
- sample_submission.csv: A sample submission file providing the correct format for result submissions.

**Key Models:**

- Logistic Regression:
   - Utilizes features 'Time,' 'V1,' 'V5,' 'V10.'
   - Trains on imbalanced class data.
   - Achieves accuracy on the test set.
   
- Random Forest:
   - Employs a set of features including 'Time' and various 'V' features.
   - Addresses class imbalance using the 'balanced' class weight.
   - Achieves accuracy on the test set.
   
- Kaggle Submission:
   - File Name: testing_submission(credit card).csv
   - Columns: 'id' and 'Class'

# Objective:
The primary objective is to build predictive models for credit card fraud detection. Key goals include exploring the dataset, handling missing values, identifying class imbalances, training models (logistic regression and random forest), and creating a submission for the competition. The analysis aims to achieve high accuracy in identifying fraudulent transactions.

# Reflection:
The analysis begins with loading the datasets, exploring their shapes, and checking for missing values. Features such as 'Time,' 'Amount,' and various 'V' features are utilized for training the models. Two models, logistic regression and random forest, are trained and evaluated. Special attention is given to handling imbalanced classes, crucial in fraud detection scenarios. The results are then submitted in the required format for the competition.

# Link:
https://www.kaggle.com/competitions/playground-series-s3e4/data
