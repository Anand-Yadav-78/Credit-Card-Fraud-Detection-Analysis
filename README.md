Credit Card Fraud Detection/n

Introduction:/n
This project aims to detect fraudulent credit card transactions using machine learning techniques. Fraudulent transactions pose a significant risk to financial institutions and consumers alike, leading to substantial financial losses. The goal of this project is to develop a predictive model that can accurately classify transactions as legitimate or fraudulent, thereby helping to mitigate fraud-related risks./n/n

Features:/n
Data Loading:/n
Successfully loaded the credit card dataset for analysis./n/n

Data Exploration:/n
Displayed the first five rows of the dataset for initial insight./n
Obtained a summary of the dataset, including data types and non-null counts./n
Checked for missing values in the dataset./n
Analyzed the distribution of legitimate and fraudulent transactions./n/n

Data Separation:/n
Separated the dataset into legitimate and fraudulent transactions for focused analysis./n
Printed the shapes of both transaction classes for comparison./n/n

Statistical Analysis:/n
Generated statistical summaries for both legitimate and fraudulent transaction amounts./n/n

Data Visualization:/n
Created histograms to visualize the distribution of transaction amounts for both classes./n
Zoomed in on the histogram to focus on smaller transaction amounts (0 to 1000)./n/n

Data Resampling:/n
Applied RandomUnderSampler to balance the classes in the dataset./n
Displayed the shape of the resampled dataset and the new class distribution./n/n

Model Training:/n
Split the dataset into training (80%) and testing (20%) sets./n
Standardized the features using StandardScaler./n
Implemented a Logistic Regression model for classification./n/n

Model Evaluation:/n
Calculated accuracy on both training and test datasets./n
Generated and displayed a confusion matrix and classification report for the test set./n/n
