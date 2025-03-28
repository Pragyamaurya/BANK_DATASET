# Portugal Bank Marketing Dataset (Supervised Learning)

Overview

This dataset originates from the Portugal Bank Marketing campaign and is used to predict whether a client will subscribe to a term deposit. It consists of various attributes related to the bank's clients, their contact history, previous campaign details, and socio-economic factors.

Dataset Information

The dataset contains the following attributes:

Bank Client Data:

age (numeric) – Age of the client.

job (categorical) – Type of job.

marital (categorical) – Marital status.

education (categorical) – Level of education.

default (categorical) – Credit in default (yes/no/unknown).

housing (categorical) – Housing loan status.

loan (categorical) – Personal loan status.

Contact Details:

contact (categorical) – Type of communication.

month (categorical) – Last contact month.

dayofweek (categorical) – Last contact day.

duration (numeric) – Duration of the last contact.

Campaign Details:

campaign (numeric) – Number of contacts performed during this campaign.

pdays (numeric) – Days since the client was last contacted.

previous (numeric) – Number of contacts before this campaign.

poutcome (categorical) – Outcome of the previous campaign.

Socio-Economic Indicators:

emp.var.rate (numeric) – Employment variation rate.

cons.price.idx (numeric) – Consumer price index.

cons.conf.idx (numeric) – Consumer confidence index.

euribor3m (numeric) – Euribor 3-month rate.

nr.employed (numeric) – Number of employees.

Target Variable:

y (binary) – Subscription to a term deposit (yes/no).

Tasks to be Performed

1. Exploratory Data Analysis (EDA)

Perform statistical summaries and visualizations.

Analyze categorical variables for insights.

2. Data Preprocessing

Handle missing values.

Perform label encoding for categorical variables.

Select important features using Random Forest.

Address class imbalance using SMOTE.

Standardize numerical features.

3. Model Building

Train and evaluate the following models:

Logistic Regression

Decision Tree

Random Forest

4. Model Evaluation

Compare models using key performance metrics (accuracy, precision, recall, F1-score, etc.).

Perform hyperparameter tuning for optimal performance.

Identify the best-performing model.

Usage Instructions

Load the dataset into a Python environment using Pandas.

Perform EDA and preprocess the data.

Train and evaluate supervised learning models.

Use the model with the best performance for predictions.

This dataset provides valuable insights into marketing campaign effectiveness and can be used for predictive modeling to improve customer targeting strategies.

