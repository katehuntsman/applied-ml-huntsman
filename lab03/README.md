# ml03_huntsman

## Classification Models
Decision Tree Classifier (DT)

A Decision Tree splits data into smaller groups based on decision rules (like "is height greater than 150 cm?"). It’s like a flowchart, where each decision point leads to another question until a final classification is reached.

Strengths: Easy to interpret and fast to train.
Weaknesses: Can overfit if the tree becomes too complex.
Support Vector Machine (SVM)

A Support Vector Machine tries to find the "best boundary" (a hyperplane) that separates data into classes. It works well with complex data and small datasets.

Strengths: Effective when there is a clear margin of separation between classes.
Weaknesses: Computationally expensive for large datasets.
Neural Network (NN)

A Neural Network is inspired by how human brains process information. It consists of layers of interconnected "neurons" that process input data and adjust based on feedback

Strengths: Can handle complex patterns and non-linear relationships.
Weaknesses: Needs more data and tuning to avoid overfitting.

## Project Overview

## Section 1. Import and Inspect the Data
- 1.1 Load the dataset and display the first 10 rows.
- 1.2 Check for missing values and display summary statistics.

## Section 2. Data Exploration and Preparation
- 2.1 Handle Missing Values and Clean Data
- 2.2 Feature Engineering

## Section 3. Feature Selection and Justification
- 3.1 Choose features and target
- 3.2 Define X (features) and y (target)

## Section 4. Train a Classification Model (Decision Tree)
- 4.1 Split the Data
- 4.2 Create and Train Model (Decision Tree)
- 4.3 Predict and Evaluate Model Performance
- 4.4 Report Confusion Matrix (as a heatmap)
- 4.5 Report Decision Tree Plot

## Section 5. Compare Alternative Models (SVC, NN)
- 5.1 Train and Evaluate Model (SVC)
- 5.2 Train and Evaluate Model (NN MLP)

## Section 6. Final Thoughts & Insights
- 6.1 Summarize Findings
    - What indicators are strong predictors of gender?
    - Decision Tree performed well but overfit slightly on training data.
    - Neural Network showed moderate improvement but introduced complexity.
- 6.2 Discuss Challenges Faced
    - Small sample size could limit generalizability.
    - Missing values (if any) could bias the model.
- 6.3 Next Steps
    - Test more features (e.g., BMI class).
    - Try hyperparameter tuning for better results.

## Markdown code for classification
| Model Type | Case | Features Used | Accuracy | Precision | Recall | F1-Score | Notes |
|------------|------|---------------|----------|-----------|--------|-----------|-------|
| **Decision Tree** | Case 1 | alone | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                   | Case 2 | age | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                   | Case 3 | age + family_size | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (RBF Kernel)** | Case 1 | alone | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                    | Case 2 | age | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                    | Case 3 | age + family_size | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (Linear Kernel)** | Case 1 | alone | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                    | Case 2 | age | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                    | Case 3 | age + family_size | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (Poly Kernel)** | Case 1 | alone | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                    | Case 2 | age | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                    | Case 3 | age + family_size | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (Sigmoid Kernel)** | Case 1 | alone | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                    | Case 2 | age | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                    | Case 3 | age + family_size | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **Neural Network (MLP)** | Case 1 | alone | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                    | Case 2 | age | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |
|                    | Case 3 | age + family_size | xx.xx% | xx.xx% | xx.xx% | xx.xx% | - |