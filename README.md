Credit Card Fraud Detection

Introduction:
This project aims to detect fraudulent credit card transactions using machine learning techniques. Fraudulent transactions pose a significant risk to financial institutions and consumers alike, leading to substantial financial losses. The goal of this project is to develop a predictive model that can accurately classify transactions as legitimate or fraudulent, thereby helping to mitigate fraud-related risks.

<b>Features</b>:
Data Loading:
Successfully loaded the credit card dataset for analysis.

Data Exploration:
Displayed the first five rows of the dataset for initial insight.
Obtained a summary of the dataset, including data types and non-null counts.
Checked for missing values in the dataset.
Analyzed the distribution of legitimate and fraudulent transactions.

Data Separation:
Separated the dataset into legitimate and fraudulent transactions for focused analysis.
Printed the shapes of both transaction classes for comparison.

Statistical Analysis:
Generated statistical summaries for both legitimate and fraudulent transaction amounts.

Data Visualization:
Created histograms to visualize the distribution of transaction amounts for both classes.
Zoomed in on the histogram to focus on smaller transaction amounts (0 to 1000).

Data Resampling:
Applied RandomUnderSampler to balance the classes in the dataset.
Displayed the shape of the resampled dataset and the new class distribution.

Model Training:
Split the dataset into training (80%) and testing (20%) sets.
Standardized the features using StandardScaler.
Implemented a Logistic Regression model for classification.

Model Evaluation:
Calculated accuracy on both training and test datasets.
Generated and displayed a confusion matrix and classification report for the test set.
