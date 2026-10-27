# House Price Prediction Using Regression

## 1. Project Overview

This project focuses on predicting house prices using Machine Learning regression algorithms. The project uses property features such as house area, number of bedrooms, bathrooms, location score, and property age to estimate house prices.

Different regression models are implemented and evaluated to compare their performance and understand how they predict house prices.

## 2. Project Objectives

- To understand supervised learning and regression algorithms.
- To explore and preprocess the house-price dataset.
- To implement Simple Linear Regression.
- To implement Multiple Linear Regression.
- To implement Polynomial Regression.
- To understand Batch, Stochastic, and Mini-Batch Gradient Descent.
- To evaluate models using different performance metrics.
- To analyze overfitting, underfitting, and the bias–variance trade-off.
- To identify the best-performing model based on test results.

## 3. Dataset Description

The project uses an Excel dataset named `house price.xlsx`.

The target variable is:

- `house_price_inr` — the price of the house in Indian Rupees.

The identifier column is:

- `house_id` — a unique identifier that is excluded from model training.

Other available numerical columns are used as independent variables to predict house prices.

## 4. Technologies and Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 5. Machine Learning Algorithms

### Simple Linear Regression

Simple Linear Regression predicts house prices using one independent variable, such as house area.

### Multiple Linear Regression

Multiple Linear Regression uses multiple property features to predict house prices.

### Polynomial Regression

Polynomial Regression transforms input features into polynomial features to capture nonlinear relationships.

### Batch Gradient Descent

Batch Gradient Descent updates model parameters using the entire training dataset in each iteration.

### Stochastic Gradient Descent (SGD)

Stochastic Gradient Descent updates model parameters using individual training examples.

### Mini-Batch Gradient Descent

Mini-Batch Gradient Descent updates model parameters using small batches of training examples.

## 6. Data Preprocessing

The following preprocessing steps are performed:

- Load the dataset from an Excel file.
- Inspect the dataset using `head()`, `info()`, and `describe()`.
- Check for missing values.
- Check and remove duplicate rows.
- Separate independent variables and the target variable.
- Exclude the house identifier from the input features.
- Split the dataset into training and testing sets.

## 7. Model Evaluation Metrics

The models are evaluated using the following metrics:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted prices.
- **MSE (Mean Squared Error):** Measures the average squared prediction error.
- **RMSE (Root Mean Squared Error):** Measures prediction error in the same units as house prices.
- **R² Score:** Measures how well the model explains variation in house prices.
- **Adjusted R²:** Adjusts R² according to the number of predictors and the sample size.
- **Training Time:** Measures the time taken to train a model or optimization method.

Lower MAE and RMSE values generally indicate better prediction accuracy, while a higher test-set R² generally indicates better predictive performance.

## 8. Data Visualization and Analysis

The project includes visualizations such as:

- Correlation heatmap.
- House area versus house price scatterplot.
- Actual versus predicted house prices.
- Residual plot.
- Gradient Descent convergence plot.
- Training versus testing performance comparison.

These visualizations help analyze relationships between features, prediction errors, model convergence, and possible overfitting or underfitting.

## 9. How to Run the Project

1. Install Python and Jupyter Notebook.
2. Install the required libraries.
3. Place the Excel dataset in the appropriate folder.
4. Open the project notebook in Jupyter Notebook.
5. Update the dataset path in the code if necessary.
6. Run the notebook cells in order.
7. Review the model evaluation metrics and visualizations.
8. Compare the results of all models.

Install the required libraries using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn openpyxl jupyter
```

## 10. Results

The performance of each model is compared using MAE, RMSE, R² Score, and training time.

The final best-performing model should be selected based on actual test-set results. The model with the best training performance is not necessarily the best model for predicting unseen house prices.

## 11. Conclusion

This project demonstrates the use of supervised Machine Learning regression algorithms for house-price prediction. Simple Linear Regression, Multiple Linear Regression, Polynomial Regression, and different Gradient Descent methods are explored and evaluated.

The evaluation metrics and visualizations help compare prediction accuracy, understand model behavior, and identify possible overfitting or underfitting.

The final model selection is based on the observed test-set performance and the ability to generalize to unseen data.

