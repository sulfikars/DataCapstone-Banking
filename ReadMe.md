# Banking

## Problem Statement

Financial institutions face significant losses due to vehicle loan defaults, leading to stricter underwriting standards and increased loan rejection rates. To address this issue, there is a need for a more effective credit risk scoring model. This project involves studying the determinants of vehicle loan default using a dataset with 41 attributes to identify factors influencing default rates and create a predictive model for potential defaulters.

## Approach

### 1. Data Preliminary Analysis

- **Data Inspection**: Conduct an initial review of the dataset to assess its structure, identify missing values, and detect duplicates.
- **Variable Naming**: Adjust variable names to align with Python’s naming conventions.
- **Missing Values**: Explore the presence of missing values and develop strategies to handle them.

### 2. Performing Exploratory Data Analysis (EDA)

- **Statistical Description**: Provide a summary of quantitative data variables.
- **Target Variable Distribution**: Analyze the overall distribution of the target variable and its distribution across various categories such as branch, city, state, supplier, and manufacturer.
- **Employment Types**: Identify different employment types and propose strategies to address missing values, if any. Use pie charts to visualize how employment types relate to defaulters and non-defaulters.
- **Age Distribution**: Investigate the relationship between age and default status. Examine age distribution in relation to defaulters and non-defaulters.
- **ID Types**: Determine the most commonly presented ID types by customers.
- **Factors Affecting Ratings**: Explain factors influencing ratings such as number of cuisines, cost, delivery options, etc.

### 3. EDA and Modeling

- **Credit Bureau Score**: Examine the distribution of credit bureau scores for defaulters versus non-defaulters in detail.
- **Account Details**: Analyze primary and secondary account information to determine its relationship with loan default probability.
- **Sanctioned vs. Disbursed Amount**: Study differences between the sanctioned and disbursed amounts of primary and secondary loans, using appropriate statistics and visualizations.
- **Inquiries and Risk**: Investigate whether a higher number of inquiries correlates with higher risk of default.
- **Credit History**: Assess the significance of credit history factors such as new loans, recent defaults, and time since the first loan in predicting default probabilities.
- **Logistic Regression**: Build a logistic regression model to predict loan defaults. Validate the model’s performance using a confusion matrix on the test data.

---

This project aims to deliver actionable insights into vehicle loan defaults and develop a robust model for predicting potential defaulters to assist financial institutions in mitigating risks.
