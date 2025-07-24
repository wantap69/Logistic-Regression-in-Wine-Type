# Logistic-Regression-in-Wine-Type
Logistic Regression on Wine Type Classification
🔍 Project Title

Quantitative Analysis of Wine Type Prediction via Logistic Regression

👤 Author
Benedict Bautista

📄 Description
This project uses binary logistic regression to predict whether a wine is red or white based on its physicochemical properties. The analysis explores how features like density, sulphates, alcohol content, and quality influence wine classification. The HTML document presents the complete analysis, including model diagnostics and assumption checking.

📁 File
winery_log.html – An HTML report generated using R and Quarto. It contains:

Data preprocessing steps

Model summary and interpretation

Tests for assumptions:

Linearity of the logit

Multicollinearity (VIF)

Outlier detection (Cook's Distance)

Independence of observations (Durbin-Watson)

Visualizations (residual plots, odds ratios, etc.)

Conclusions about model fit and variable significance

📊 Methodology
Model Used: Binary Logistic Regression

Dependent Variable: Wine type (Red = 0, White = 1)

Independent Variables:

Density

Sulphates

Alcohol

Quality

✅ Assumption Checks
Binary Outcome: Confirmed (red vs. white wine)

Linearity of Logit: Evaluated using residual plots

Multicollinearity: Tested using VIF (no values > 10)

Outliers: Checked via Cook’s Distance (no values > 1)

Independence: Assessed using Durbin-Watson test (DW ≈ 2)

📌 Summary of Findings
All predictors were statistically significant.

Density, sulphates, and alcohol had negative associations with the likelihood of a wine being white.

Quality had a positive association, increasing the odds of a wine being classified as white.

McFadden’s R² = 0.3868 indicated good model fit.

📎 How to View
Open this [link](http://rpubs.com/Nebz/1331879) to view in any modern web browser (e.g., Chrome, Firefox, Edge).

📬 Contact
For questions or feedback, contact Benedict Bautista.

