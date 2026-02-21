# Height Prediction using Simple Linear Regression

## Project Overview
This project demonstrates the implementation of a **Simple Linear Regression** algorithm from scratch using Python's `scikit-learn` library. The goal is to predict an individual's **Height** based on their **Weight**.

This project serves as a foundational exercise in Data Science, focusing on exploratory data analysis, feature scaling, model training, and performance evaluation.

## Dataset
The dataset contains two primary features:
- **Weight (Independent Variable):** Used to predict height.
- **Height (Dependent Variable):** The target value for prediction.

## Key Technical Steps
- **Data Visualization:** Used `matplotlib` to identify the linear relationship.
- **Feature Scaling:** Implemented `StandardScaler` to normalize the input data for better model convergence.
- **Model Training:** Utilized `LinearRegression` to find the line of best fit.
- **Performance Metrics:** Evaluated the model using:
  - **MSE (Mean Squared Error):** ~109.77
  - **RMSE (Root Mean Squared Error):** ~10.47
  - **R-Squared:** ~0.77 (The model explains 77% of the variance).

## Regression Results
The relationship follows the linear equation:
**Height = 157.5 + 17.03 * (Weights)**

## Assumptions & Residual Analysis
To validate the model, I performed a residual analysis:
- **Normality:** The errors follow a nearly normal distribution.
- **Homoscedasticity:** Residuals are uniformly distributed against predictions, indicating constant variance.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn`.
3. Open the `.ipynb` file in Jupyter Notebook or VS Code.
