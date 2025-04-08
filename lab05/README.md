# ml05_huntsman

### Setup Instructions
```
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
```

## Overview

In this lab, I explored two powerful ensemble learning techniques:
- **Random Forest (100 estimators)**
- **Gradient Boosting (100 estimators)**

The goal was to compare performance and generalization using a multiclass classification task on the **Wine Quality** dataset.

---

## Files

- `ensemble-huntsman.ipynb` – Fully executed Jupyter notebook with all models, evaluations, and reflections.
- `winequality-red.csv` – UCI dataset used for classification.
- `README.md` – This file.

---

## Model Performance Summary

| Model                   | Train Accuracy | Test Accuracy | Accuracy Gap | Train F1 | Test F1 | F1 Gap   |
|-------------------------|----------------|----------------|---------------|----------|---------|----------|
| Random Forest (100)     | 1.0000         | 0.8875         | 0.1125        | 1.0000   | 0.8661  | 0.1339   |
| Gradient Boosting (100) | 0.9601         | 0.8562         | 0.1039        | 0.9584   | 0.8411  | 0.1173   |

 **Random Forest** achieved the highest scores but showed signs of overfitting.  
 **Gradient Boosting** generalized better with slightly lower but more consistent performance.

---

## Key Takeaways
- Both models performed well, but **Gradient Boosting** had a smaller accuracy/F1 gap.
- Overfitting was observed in Random Forest due to perfect training scores.
- Hyperparameters like `max_depth`, `learning_rate`, and `n_estimators` are worth tuning for future improvements.
- Next steps could include:
  - Cross-validation
  - Feature importance analysis
  - Trying other ensemble variants like XGBoost or AdaBoost

---

## Resources
- [Notebook Link](https://github.com/katehuntsman/applied-ml-huntsman/blob/main/lab05/ensemble-huntsman.ipynb)
- [Dataset - UCI Wine Quality](https://archive.ics.uci.edu/ml/datasets/wine+quality)
