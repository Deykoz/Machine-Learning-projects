# Multiple Regression Models

This project focuses on predicting the **Apnea-Hypopnea Index (IAH)** using key features such as **Age**, **BMI**, and **Cervical**. The goal is to compare the performance of different regression models, including both linear and non-linear approaches, to find the model that provides the best predictions for IAH.

## Models Used

- **Linear Regression**: A simple approach to model the relationship between input variables and the target.
- **Ridge Regression**: A linear model that adds regularization to prevent overfitting.
- **Lasso Regression**: A regression model that performs feature selection while preventing overfitting.
- **Elastic Net Regression**: A combination of Lasso and Ridge regression, balancing both regularization techniques.
- **Polynomial Regression**: A non-linear model that extends linear regression by introducing higher-degree polynomial terms.
- **Random Forest Regression**: An ensemble learning method that uses multiple decision trees to improve performance.

## Objective

The primary objective is to predict **IAH** using these regression models and evaluate their performance based on several metrics, such as:
- **R²**: Measures the proportion of variance explained by the model.
- **MSE**: Mean Squared Error, which measures prediction accuracy.
- **RMSE**: Root Mean Squared Error, a normalized version of MSE.
- **MAE**: Mean Absolute Error, representing the average magnitude of errors in the predictions.

## Results

- **Polynomial Regression** emerged as the best performer, with an **R²** of **0.2707**, offering the best balance between model complexity and predictive accuracy. It also produced the lowest **MSE**, **RMSE**, and **MAE**, indicating better prediction accuracy.
- **Random Forest Regression**, although a more complex model, performed poorly with an **R²** of **0.1791**. This suggests that it might suffer from overfitting or underfitting, which could be due to improper hyperparameter tuning.
- The **Linear Regression**, **Ridge Regression**, **Lasso Regression**, and **Elastic Net Regression** models showed similar results, with **R²** values around **0.25**, indicating that they didn't capture the underlying patterns in the data effectively.

### Model Performance Summary:

| Model                    | R²       | MSE    | RMSE   | MAE    |
|--------------------------|----------|--------|--------|--------|
| Polynomial Regression     | 0.2707   | Lowest | Lowest | Lowest |
| Random Forest Regression  | 0.1791   | High   | High   | High   |
| Linear Regression         | 0.25     | Medium | Medium | Medium |
| Ridge Regression          | 0.25     | Medium | Medium | Medium |
| Lasso Regression          | 0.25     | Medium | Medium | Medium |
| Elastic Net Regression    | 0.25     | Medium | Medium | Medium |

## Conclusion

- **Polynomial Regression** provided the best performance in terms of predictive accuracy and error minimization. 
- **Random Forest** struggled with generalization, likely due to overfitting or improper tuning of hyperparameters.
- **Linear**, **Ridge**, **Lasso**, and **Elastic Net** regressions showed comparable performance, indicating that simpler models might not capture the complexity of the data.

## Next Steps

- Explore **alternative ensemble methods** or **boosting techniques** to improve model performance.
- Investigate further **hyperparameter tuning** for **Random Forest** to improve its performance and reduce overfitting.
- Explore **feature engineering** and potentially incorporate more features to improve model predictions.

## Notebook

You can find the notebook for this project here: [Multiple_Regression_Models.ipynb](Multiple_Regression_Models.ipynb)

