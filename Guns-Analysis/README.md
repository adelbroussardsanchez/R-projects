# Resume Callback Bias Analysis (R)

## Overview
This project uses R to analyze factors influencing the likelihood of receiving a callback after submitting a resume. The primary objective is to evaluate whether race and/or gender has a statistically significant effect on callback rates in job applications. The analysis combines exploratory data analysis with predictive modeling and multiple model validation techniques.

The dataset used in this project is publicly available and can be accessed using this link: https://vincentarelbundock.github.io/Rdatasets/doc/openintro/resume.html

---

## Project Objectives
- Assess whether race and gender impact resume callback rates  
- Explore relationships between applicant characteristics and outcomes  
- Build and compare predictive models using multiple validation strategies  
- Apply rigorous statistical techniques to support or reject initial hypotheses  

---

## Contents

### Dataset
- **Description**  
  Overview of the resume audit dataset, including structure, source, and scope.

- **Data Cleaning**  
  Handling missing values, recoding categorical variables, and ensuring consistency for modeling.

- **Variable Description**  
  Detailed explanation of response variables, categorical predictors (e.g., race, gender), and numerical predictors.

---

### Purpose and Expectations
- Test for evidence of bias in hiring callbacks  
- Expectation that race and/or gender may influence callback probability  
- Emphasis on statistical validity rather than anecdotal inference  

---

## Data Analysis

### Categorical Variable Analysis
- **Bar Plots**  
  Visual comparison of callback rates across categorical groups.

- **Heatmaps**  
  Interaction effects between categorical variables and callback outcomes.

---

### Numerical Variable Analysis
- **Correlation Matrices**  
  Identification of relationships between numerical predictors.

- **Histograms**  
  Distribution analysis of continuous variables.

- **Density Plots**  
  Smoothed comparisons across groups to highlight structural differences.

---

## Predictive Modeling

### Best Subset Selection
- Identification of optimal predictor combinations based on model performance.

### Validation Techniques
- **Validation Set Approach**  
  Train/test split to evaluate generalization error.

- **Leave-One-Out Cross-Validation (LOOCV)**  
  High-bias reduction method for small-sample robustness.

- **K-Fold Cross-Validation**  
  Balanced bias–variance tradeoff for model comparison.

---

## Summary
- Consolidated findings across exploratory analysis and modeling  
- Interpretation of statistical results in the context of hiring bias  
- Discussion of limitations and assumptions  

---

## Tools and Technologies
- **Language:** R  
- **Libraries:** openintro, ggplot2, leaps, caret 
- **Methods:** EDA, regression modeling, cross-validation  

---

## Works Cited
Full list of academic and data sources referenced in the analysis.

---

