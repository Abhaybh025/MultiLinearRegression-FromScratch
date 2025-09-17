## Multiple Linear Regression from Scratch (NumPy)

### Overview

This project demonstrates a Multiple Linear Regression implementation from scratch using NumPy, without relying on sklearn.
The model uses the Normal Equation to calculate coefficients and make predictions. The implementation is validated against sklearn’s LinearRegression on the Diabetes dataset.

The goal of this project is to bridge theory and practice, understanding the math behind linear regression — including matrix operations, coefficient derivation, and
evaluation metrics — rather than just using library functions.

### Dataset

Source: Sklearn Diabetes Dataset
Samples: 442
Features: 10 numerical baseline variables
age: Age in years
sex: Sex
bmi: Body Mass Index
bp: Average blood pressure
s1: Total serum cholesterol (tc)
s2: Low-density lipoproteins (ldl)
s3: High-density lipoproteins (hdl)
s4: Total cholesterol / HDL ratio
s5: Log of serum triglycerides (ltg)
s6: Blood sugar level (glu)
Target: Quantitative measure of disease progression after one year

### Features

- Implement Multiple Linear Regression from scratch using NumPy
- Compare results with sklearn LinearRegression
- Evaluate using metrics:
  - R²
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
- Visualize residuals and target distribution
-Plan to implement Gradient Descent for iterative optimization

### Notebook Structure

1. Introduction & Dataset Overview
2. Data Exploration – Preview, stats, and plots
3. Model Implementation – MultiLinearReg class with fit, predict, r2_score, mse, mae, and residuals methods
4. Training & Evaluation – Compare scratch implementation with sklearn
5. Residual Analysis & Visualization
6. Conclusion & Insights

### Usage 
1. Clone the repo : `git clone YOUR_REPO_LINK`
2. Open the notebook in Jupyter or collab
3. Run all cells to reproduce results and plots

### Next Steps

- Implement Gradient Descent for iterative coefficient optimization
- Explore regularization techniques like Ridge and Lasso
- Test on larger datasets to evaluate numerical stability

### License

This project is for educational purposes and is open for anyone to use or adapt.
