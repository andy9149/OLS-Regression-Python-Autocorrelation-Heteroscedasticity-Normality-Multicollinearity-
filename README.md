# OLS-Regression-Python-Autocorrelation-Heteroscedasticity-Normality-Multicollinearity-
Comprehensive regression diagnostics and modeling using financial data from 4,000+ firms. Applies OLS, Ridge, Lasso, and Elastic Net to predict P/E ratios. Includes winsorization, log transformations, multicollinearity checks (VIF), and assumption testing to enhance model reliability.

📊 Advanced Regression Analysis and Data Diagnostics

Author: Sebastian Heredia
Course: BSAN6070 – INTRODUCTION TO MACHINE LEARNING
Tools: Python (Pandas, NumPy, Statsmodels, Scikit-learn, Matplotlib, Seaborn)

📘 Overview

This project performs a detailed regression modeling and diagnostics analysis using financial data from over 4,000 firms. The study builds and refines predictive models for Price-to-Earnings (P/E) ratios, addressing common statistical issues such as multicollinearity, non-normality, and outliers to ensure robust and interpretable results.

The work is divided into two main components:

Lab 1: OLS Regression Diagnostics and Assumption Testing

Lab 2: Advanced Regression with Regularization and Data Preprocessing

🧩 Project Files
File	Description
Lab1.ipynb	Jupyter Notebook performing OLS regression, assumption testing, and model diagnostics.
Lab2_reviewed.ipynb	Notebook expanding to Ridge, Lasso, and Elastic Net regression with preprocessing.
LAB1_OLS REGRESSION ANALYSIS DIAGNOSE TESTS.pdf	Report summarizing regression diagnostics, residual analysis, and multicollinearity tests.
LAB 2 ADVANCED REGRESSION ANALYSIS WITH DATA PREPROCESSING.pdf	Full report detailing model improvements, transformations, and regularization results.
⚙️ Methodology
1. Data Preprocessing

Imported and cleaned financial datasets (4,000+ observations).

Handled missing values and scaled predictors.

Applied winsorization and log transformations to handle outliers and non-normality.

2. Regression Diagnostics (Lab 1)

Built an OLS regression model to predict P/E ratios.

Conducted diagnostics for:

Multicollinearity (Variance Inflation Factor – VIF)

Heteroskedasticity (Breusch–Pagan, White’s test)

Normality of residuals (Q–Q plots, Shapiro–Wilk)

Linearity and influential points (Cook’s distance)

3. Advanced Modeling (Lab 2)

Implemented Ridge, Lasso, and Elastic Net regressions to regularize coefficients and improve generalization.

Conducted cross-validation to optimize alpha (λ) parameters.

Compared results to baseline OLS using Adjusted R², AIC, and MSE.

📊 Key Insights
Focus Area	Finding
📈 OLS Model	Initial OLS model exhibited multicollinearity (high VIF) and residual non-normality.
⚙️ Regularization	Ridge and Lasso reduced variance and improved interpretability by shrinking coefficients.
🧮 Transformation	Log and winsorized transformations stabilized variance and improved residual distribution.
🔍 Elastic Net	Provided a balanced trade-off between L1 and L2 penalties, yielding the best model fit.
💡 Conclusions

Addressing data quality and assumption violations significantly improves model performance.

Regularization techniques mitigate overfitting and enhance predictive accuracy.

Proper diagnostics and transformations are essential steps before model interpretation.

🚀 Future Work

Explore non-linear models such as Random Forests or XGBoost.

Automate diagnostics through modular Python scripts.

Develop an interactive dashboard for regression diagnostics visualization.

📬 Contact

Sebastian Heredia
📧 andy_9149@hotmail.com

🔗 LinkedIn

💻 GitHub
