# ML-Loan-Approval
Authors: Matteo calviello, Paul Cleary, DJ Liveris, Preksha Sarda

## Project Overview
This project predicts loan approval using various machine learning models for both classification and regression tasks. All code and scripts are complete, documented, and ready to run. Functions are kept small and/or include inline comments for clarity.

## How to Run
1. **Install dependencies** (see below).
2. **Place the data file** `loan_approval_dataset.csv` in the project root directory (`ML-Loan-Approval`).
3. **Open and run the Jupyter notebooks** in order, or run individual scripts as needed. Each notebook is self-contained and includes comments for guidance.

## Dependencies
Install all required packages with:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost catboost
```
**Required packages:**
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- xgboost
- catboost

## Data
- **Source:** The dataset `loan_approval_dataset.csv` should be placed in the project root directory.

## Model Results
### Classification Models
| Model Name           | Accuracy |
|----------------------|----------|
| Baseline             | 0.6008   |
| KNN                  | 0.9315   |
| Logistic regression  | 0.9075   |
| XGBoost              | 0.9836   |
| CatBoost             | 0.9801   |
| SVM                  | 0.9309   |
| GaussianNB           | 0.9368   |
| MLPClassifier        | 0.9684   |
| Gradient Boosting    | 0.983    |
| Random Forest        | 0.962    |
| AdaBoost             | 0.97     |
| QDA                  | 0.82     |

### Regression Models
| Model Name             | R^2    |
|------------------------|--------|
| XGBRegressor           | 0.8518 |
| CatBoostRegressor      | 0.8500 |
| MLPRegressor           | 0.8516 |
| Random Forest Regressor| 0.859  |
| Lasso Regression       | 0.861  |
| Gradient Boosting      | 0.860  |
| KNN regressor          | 0.79   |
| Ridge Regression       | 0.86   |
| Decision Tree Regressor| 0.71   |
| Simple Linear Regressor| 0.86   |
| Elastic Net Regression | 0.82   |

**Note:** XGBoost and Lasso Regression achieved the highest scores for classification and regression, respectively.

---
For any issues, please refer to the comments in each notebook or contact the authors listed above.

