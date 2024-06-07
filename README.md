PCA and Logistic Regression on Breast Cancer Dataset
Overview
This project demonstrates the use of Principal Component Analysis (PCA) to identify essential variables and reduce dimensionality, followed by Logistic Regression for prediction using the breast cancer dataset from sklearn.datasets.

Contents
pca_logistic_regression.py: Python script implementing PCA and Logistic Regression.
README.md: This readme file.
Requirements
Python 3.x
Required libraries:
pandas
scikit-learn
matplotlib
seaborn

You can install the required libraries using the following command:
pip install pandas scikit-learn matplotlib seaborn

Steps to Run the Code
Clone the Repository:
git clone https://github.com/your-username/repository-name.git
cd repository-name

Run the Script:
python pca_logistic_regression.py

Script Details
Data Loading and Preparation
The breast cancer dataset is loaded using load_breast_cancer from sklearn.datasets.
The dataset is converted into a DataFrame for easier manipulation.
The features are standardized to ensure equal contribution to the PCA.
Principal Component Analysis (PCA)
PCA is applied to reduce the dataset to 2 principal components.
The transformed data is stored in a new DataFrame for further analysis.
Logistic Regression
The dataset is split into training and testing sets.
Logistic Regression is trained on the PCA-transformed data.
Predictions are made on the test set.
Evaluation
The model's accuracy is calculated.
A confusion matrix is generated to visualize the performance.
An ROC curve is plotted to assess the model's performance.

Example Output
Accuracy: 0.95
Confusion Matrix
ROC Curve

Files
pca_logistic_regression.py: Main script for performing PCA and Logistic Regression.
README.md: Documentation for the project.
