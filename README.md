# Jamboree-Education-Linear-Regression
Using Linear Regression to predict which features contribute to getting admission in an Ivy League College.

**Context**

Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.


**Concept Used:**

Exploratory Data Analysis
Linear Regression

**Stepwise Detail of the process used:**

1. Import the dataset and do usual exploratory data analysis steps like checking the structure & characteristics of the dataset.
2. Drop the unique row Identifier if you see any. This step is important as you don’t want your model to build some understanding based on row numbers.
3. Use Non-graphical and graphical analysis for getting inferences about variables. This can be done by checking the distribution of variables of graduate applicants.
4. Check correlation among independent variables and how they interact with each other.
5. Used Linear Regression from (Statsmodel library)
6. Tested the assumptions of linear regression: Multicollinearity check by VIF score, Mean of residuals, Linearity of variables (no pattern in residual plot), Test for Homoscedasticity, Normality of residuals.
7. Model evaluation was performed using MAE, RMSE, R2 score, Adjusted R2.
8. Tried Lasso and Ridge regression
