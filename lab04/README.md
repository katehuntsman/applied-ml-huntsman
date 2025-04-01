# ml04_huntsman

# Titanic Fare Prediction

## Project Overview
This project focuses on predicting passenger fare on the Titanic dataset using various regression models. The goal is to understand the relationship between passenger attributes and fare while evaluating model performance with different techniques.

## Objectives
- Analyze the features influencing Titanic fare.
- Build and evaluate multiple regression models to predict fare.
- Compare model performance based on metrics like R², RMSE, and MAE.
- Experiment with regularization techniques (Ridge, Lasso, ElasticNet) and polynomial regression.

## Dataset
The dataset used is the Titanic dataset, which includes features like:
- **Age**: Age of the passenger.
- **Family Size**: The number of family members aboard the Titanic.
- **Pclass**: Passenger class (1, 2, or 3).
- **SibSp**: Number of siblings/spouses aboard.
- **Embarked**: Port of embarkation.
- **Sex**: Gender of the passenger.
- **Fare**: The ticket price paid by the passenger.

## Results Table
![Model Results](./lab04/results_table.png)

## Project Overview
## Section 1. Import and Inspect the Data

## Section 2. Data Exploration and Preparation

## Section 3. Feature Selection and Justification

## Section 4. Train a Regression Model (Linear Regression)
4.1 Split the Data
4.2 Train and Evaluate Linear Regression Models (all 4 cases)
4.3 Report Performance

## Section 5. Compare Alternative Models
5.1 Ridge Regression (L2 penalty)
5.2 Elastic Net (L1 + L2 combined)
5.3 Polynomial Regression
5.4 Visualize Polynomial Cubic Fit (for 1 input feature)
5.4 Reflections (in a Markdown cell):
5.4 Compare All Models

## Section 6. Final Thoughts & Insights
6.1 Summarize Findings
What features were most useful?
What regression model performed best?
How did model complexity or regularization affect results?

6.2 Discuss Challenges
Was fare hard to predict? Why?
Did skew or outliers impact the models?

6.3 Optional Next Steps
Try different features besides the ones used (e.g., pclass, sex if you didn't use them this time)
Try predicting age instead of fare
Explore log transformation of fare to reduce skew