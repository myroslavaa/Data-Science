# Sales forecasting

"Optimizing Regression Models: Feature Selection and Validation"

This project focuses on the preprocessing, feature selection, and validation of regression models to enhance predictive accuracy. Key steps and methodologies include:

## Preprocessing
- Removal of outliers and null values.
- One-hot encoding for nominal features.
- Scaling of numeric features using **MinMaxScaler** to standardize values between [0,1].

## Feature Selection
- Identified and retained features with high correlation to the target variable.
- Addressed collinearity issues by removing redundant features using statistical tests (e.g., chi-squared).
- Improved model interpretability and reduced overfitting by selecting only meaningful features.

## Algorithm Evaluation
Developed and tuned multiple regression models, including:
- **Linear Regression**: Achieved a 32% accuracy improvement with feature selection.
- **Polynomial Regression**: Best performance with degree 2.
- **Decision Tree Regression**: Optimal performance with a maximum depth of 6.
- **k-Nearest Neighbors (KNN) Regression**: Best results achieved with 12 neighbors.

## Cross-Validation
- Implemented cross-validation to ensure model robustness and avoid overfitting.

## Results
- Models with feature selection and tuning significantly outperformed baseline models.
- **Top-performing models**:
  1. **Linear Regression** (with feature selection).
  2. **KNN Regression** (12 neighbors).
  3. **Polynomial Regression** (degree 2).
  4. **Decision Tree Regression** (max depth 6).

This project highlights the importance of careful preprocessing, feature selection, and algorithm tuning in achieving accurate and reliable predictive modeling.

---

Feel free to reach out if you have any questions or suggestions!
