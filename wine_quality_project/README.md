# Wine Quality Logistic Regression Project

This project uses logistic regression models to study which wine characteristics are associated with high-quality red wine.

## Goal

The goal of this project was to predict whether a wine is considered **high quality** based on several physicochemical measurements such as:

- alcohol
- sulphates
- acidity
- chlorides
- sulfur dioxide
- density

The original wine quality score was converted into a binary response variable:

- High Quality = quality > 6
- Not High Quality = quality ≤ 6

---

## Methods Used

This project uses methods from categorical data analysis and generalized linear models (GLMs), including:

- Logistic Regression
- Probit Regression
- Identity-Link Binomial Model
- Likelihood Ratio Tests (LRT)
- AIC Model Selection
- Odds Ratios
- Confidence Intervals
- ROC Curves and AUC
- LOOCV and 10-Fold Cross Validation
- Confusion Tables

---

## Main Results

Some important findings from the project:

- Alcohol and sulphates were strong positive predictors of high-quality wine.
- Volatile acidity and chlorides were negatively associated with wine quality.
- The reduced logistic regression model performed well while using fewer predictors.
- The ROC curve produced an AUC of about 0.88, showing strong classification performance.
- The probit model slightly outperformed the logistic model based on AIC.

---

## Files

- `449_Project_GUZMAN.Rmd` → R Markdown source file
- `449_Project_GUZMAN.pdf` → Final report
- `winequality-red.csv` → Data set

---

## Tools Used

- R
- RStudio
- GLM functions (`glm`)
- Packages:
  - `pROC`
  - `boot`
  - `DAAG`

---

## Data Source

Wine Quality Dataset from the UCI Machine Learning Repository:

https://archive.ics.uci.edu/ml/datasets/wine+quality
