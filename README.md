# ClassificationAssignment01_KNNModel_DetectingCreditcardFraudulentTransactions

# Case Study:

Let's assume you are a data scientist, and you have been tasked with detecting fraudulent transactions. The objective is to build a model that can accurately classify transactions in a given dataset as either fraudulent or non-fraudulent.

About the dataset:

The creditcard.csv dataset is utilized here which consists of various anonymized features, along with Time, Amount, and Class, where Class indicates whether the transaction is fraudulent (1) or not (0).

This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependent cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Download dataset from the below link:

https://drive.google.com/drive/folders/1oZt50W9d5eYYNZ20ca0SIlU49UUN60qx?usp=sharing

Tasks:

Q1) Perform data loading, preprocessing by dropping any rows with 'NaN' values in the 'Class' column. [1M]

Q2) Split the dataset into features (X) and the target variable (y), and further divide into training and test sets. [Consider test_size=0.2]  [1M]

Q3) Perform data scaling and modelling. Also, fine tune the value of k. [3M]

The K-Nearest Neighbors model has to be initialized, trained on the training data, and subsequently use it to make predictions on the test data. Initialize the model with k=5.

Q4) Evaluate the model performance using a classification report and accuracy score [2M]

Q5) Plot a confusion matrix as a heatmap, offering a visual representation of the model's performance, illustrating True Positives, True Negatives, False Positives, and False Negatives. [1M]

Q6) Write some conclusion on how K-Nearest Neighbors implementation serves as an efficient solution for credit card fraud detection. [1M]


