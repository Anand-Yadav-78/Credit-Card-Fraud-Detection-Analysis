<H1><b>Credit Card Fraud Detection</b></H1>

<H2><b>Introduction:</b></H2>
This project aims to detect fraudulent credit card transactions using machine learning techniques. Fraudulent transactions pose a significant risk to financial institutions and consumers alike, leading to substantial financial losses. The goal of this project is to develop a predictive model that can accurately classify transactions as legitimate or fraudulent, thereby helping to mitigate fraud-related risks.

<H2><b>Features:</b></H2>

<H3><b>Data Loading:</b></H3>

- Successfully loaded the credit card dataset for analysis.

<H3><b>Data Exploration:</b></H3>

- Displayed the first five rows of the dataset for initial insight.
- Obtained a summary of the dataset, including data types and non-null counts.
- Checked for missing values in the dataset.
- Analyzed the distribution of legitimate and fraudulent transactions.

<H3><b>Data Separation:</b></H3>

- Separated the dataset into legitimate and fraudulent transactions for focused analysis.
- Printed the shapes of both transaction classes for comparison.

<H3><b>Statistical Analysis:</b></H3>

- Generated statistical summaries for both legitimate and fraudulent transaction amounts.

<H3><b>Data Visualization:</b></H3>

- Created histograms to visualize the distribution of transaction amounts for both classes.
- Zoomed in on the histogram to focus on smaller transaction amounts (0 to 1000).

<H3><b>Data Resampling:</b></H3>

- Applied RandomUnderSampler to balance the classes in the dataset.
- Displayed the shape of the resampled dataset and the new class distribution.

<H3><b>Model Training:</b></H3>

- Split the dataset into training (80%) and testing (20%) sets.
- Standardized the features using StandardScaler.
- Implemented a Logistic Regression model for classification.

<H3><b>Model Evaluation:</b></H3>

- Calculated accuracy on both training and test datasets.
- Generated and displayed a confusion matrix and classification report for the test set.
