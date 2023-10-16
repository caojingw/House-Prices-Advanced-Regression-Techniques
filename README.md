# Competition Description - Regression Problem:

Kaggle: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

# Result - Top 20% in the leaderboard
![image](https://user-images.githubusercontent.com/39035531/206618577-ebcd679a-e552-42a4-b96c-54d2bd97bc0d.png)

# Approach

- Data Import and exploration
- Data Processing
  1. Missing Data
  2. Outliers
  3. Data Type Correction
  4. Label encoding
  5. Skewness
- Feature Engineering: New features
- Modelling
  1. Lasso Regression
  2. Ridge Regression
  3. Net Elastic Regression
- Performance Validation
  1. Train/Validation Split
  2. Cross-Validation
 
A detailed explanation can be found in the report attached.

# Summary
After EDA and data pre-processing, we trained 90% of the training data to validate 10% of the remaining dataset. Then, we ran both Lasso and Ridge regularization techniques by running cross-validation and finalized the best model based on their accuracy. In our analysis, the Lasso was proven to be the most effective for our problem with the lowest Mean Square Error.

# Lasso vs. Ridge Regression
![image](https://github.com/caojingw/House-Prices-Advanced-Regression-Techniques/assets/39035531/439f366f-878d-483e-b69e-2b2d024ffa62)

# Secret Sauce
![image](https://github.com/caojingw/House-Prices-Advanced-Regression-Techniques/assets/39035531/16603268-c7d2-48d9-9e33-7d0e1bf97f91)
