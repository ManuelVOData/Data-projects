#  Linear Regression – Housing Prices Prediction

This project applies a **Linear Regression** model to predict housing prices based on the size of the property in square feet.

## 📊 Dataset

- The dataset includes 1,460 observations and 2 columns: `SquareFeet` (independent variable) and `SalePrice` (target).
- The data has been cleaned and formatted for this regression task.

##  Steps performed

1. Data loading and basic exploration (`.head()`, `.describe()`)
2. Visualization of the relationship between features
3. Train-test split
4. Model training using `LinearRegression()` from Scikit-learn
5. Model evaluation using:
   - Mean Squared Error (MSE)
   - R-squared score (R²)
6. Visualization of regression line
7. 10-Fold Cross-Validation

## 📈 Results

- R-squared score (R²) on the test set: **0.59**
- Mean Cross-Validation Score (R²) with `cv=10`: **0.4997**
- The model shows moderate predictive power, suggesting a linear relationship, but also pointing out the potential benefit of incorporating more features for improved performance.

---

##  Reflections & Next Steps

This project was an opportunity to strengthen my understanding of regression fundamentals and the evaluation of models using both hold-out and cross-validation strategies.
