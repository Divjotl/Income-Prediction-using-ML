# Project Description: Predicting Income Bracket Using Census Data
This project focuses on building a predictive model to determine whether an individual earns more than $50,000 per year using data from the 1994 U.S. Census. By leveraging supervised learning algorithms, we aim to analyze the factors influencing income and construct a robust classification model. The insights gained from this analysis can help non-profit organizations make better-informed decisions about donation requests and outreach strategies.

## Key Highlights:

- **Objective:** The primary goal is to predict whether an individual's income exceeds $50,000 annually based on demographic and economic features.

## Dataset Overview:
- **Source:** 1994 U.S. Census Bureau database
- **Size:** 32,560 rows with 14 independent features and 1 target variable
- **Target Variable:** Income (binary classification: >$50K or <=$50K)
- **Features:** Includes variables such as age, workclass, education level, marital status, occupation, race, gender, hours worked per week, and more.
  
## Approach:

- Explore and preprocess the dataset to ensure quality and consistency.

- Implement multiple supervised learning algorithms and evaluate their performance.

- Select the best-performing model based on testing procedures and optimize it for improved accuracy.

**Practical Use Case:** Understanding an individual’s income bracket helps non-profits estimate potential donation amounts or decide whether to engage with a potential donor. Publicly available features can serve as reliable indicators of income without needing direct financial details.

## Dataset Features:

Below are the key features used for prediction:

- **Age:** Range from 17 to 90 years.

- **Workclass:** Employment type (e.g., private, government, self-employed).

- **Fnlwgt:** Weight of the feature combination in the dataset.

- **Education:** Highest education level achieved.

- **Education_num:** Number of years of education.

- **Marital_Status:** Marital status of the individual.

- **Occupation:** Type of profession.

- **Relationship:** Family role (e.g., spouse, child, etc.).

- **Race:** Ethnic background.

- **Sex:** Gender (male or female).

- **Capital_gain:** Monetary gains from investments.

- **Capital_loss:** Monetary losses from investments.

- **Hours_per_week:** Weekly work hours.

- **Native_Country:** Country of origin.

## Challenges and Insights:

While the dataset is somewhat dated, it provides valuable insights into the relationships between demographic and economic features and income. These insights can guide the development of modern predictive models in similar domains.

By training and evaluating classification algorithms on this dataset, we aim to uncover the most significant predictors of income and demonstrate the effectiveness of supervised learning in solving real-world problems.
