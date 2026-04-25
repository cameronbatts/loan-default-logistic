# Loan Default Prediction via Logistic Regression

**Tools:** R · tidyverse · ggplot2 · gridExtra · glm · caret · Logistic Regression

---

## Problem

Lenders needed a statistically grounded model to identify borrowers at risk of default using credit grade, income, employment history, and age data.

## Approach

Applied logistic regression in R to classify loan default risk. Conducted exploratory analysis across key variables, removed outliers, handled missing data with median imputation and indicator columns, and evaluated model performance using confusion matrices with adjusted cutoff thresholds. Compared glmBase, glmTop5, and glmTop3 models using AIC to identify the best balance of fit and complexity.

## Impact

Identified credit grade and interest rate as the strongest predictors of default. The top 5 predictor model (glmTop5) achieved the lowest AIC (~11197), outperforming both the full model and the 3-variable model, supporting more data-driven and transparent lending risk assessments.

---

## Files

| File | Description |
|------|-------------|
| `loan_default_logistic.Rmd` | R Markdown source file with full analysis |
| `loan_default_logistic.html` | Rendered HTML output |

---

*Part of my data & analytics portfolio — [cameronbatts.github.io](https://cameronbatts.github.io)*
