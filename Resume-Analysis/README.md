# Resume Callback Analysis (R)

## Overview
In this project, I used R to analyze a resume audit dataset to see what factors affect whether a job application receives a callback. The main goal was to find out if race and/or gender influence callback rates. I combined data cleaning, visual analysis, and modeling to better understand patterns in the data and test these questions statistically.

The dataset used in this project is publicly available using this link: https://vincentarelbundock.github.io/Rdatasets/doc/openintro/resume.html

---

## Project Goals
- See whether race or gender affects callback rates  
- Explore patterns in resume characteristics and outcomes  
- Build models to predict callbacks  
- Check how well those models perform using different validation methods  

---

## Contents

### Dataset
- **Description**  
  Overview of the dataset and what information it contains.

- **Cleaning the Data**  
  Steps taken to clean the data, handle missing values, and prepare variables for analysis.

- **Variable Description**  
  Explanation of the main variables, including callback outcome, race, gender, and other resume features.

---

### Purpose and Expectations
The purpose of this project was to test whether race and gender play a role in hiring callbacks. Based on prior research, I expected to see differences in callback rates across groups, but relied on the data to confirm or reject that assumption.

---

## Data Analysis

### Categorical Variables
- **Bar Plots**  
  Used to compare callback rates across different groups.

- **Heatmaps**  
  Used to explore how combinations of categorical variables relate to callbacks.

---

### Numerical Variables
- **Correlation Matrices**  
  Used to see how numerical variables relate to one another.

- **Histograms**  
  Used to understand the distribution of numeric variables.

- **Density Plots**  
  Used to compare distributions across groups in a smoother way.

---

## Modeling

### Best Subset Selection
Tested different combinations of variables to find which ones best explained callback outcomes.

### Model Validation
- **Validation Set Approach**  
  Split the data into training and testing sets to evaluate performance.

- **Leave-One-Out Cross-Validation (LOOCV)**  
  Tested models by training on all but one observation at a time.

- **K-Fold Cross-Validation**  
  Evaluated models by splitting the data into multiple groups to balance accuracy and stability.

---

## Summary
This project brings together data exploration and modeling to better understand hiring outcomes. The results highlight which variables matter most and whether race and gender show meaningful effects on callbacks, while also acknowledging the limits of the data.

---

## Tools Used
- **Language:** R  
- **Main Packages:** openintro, ggplot2, leaps, caret  
- **Techniques:** data cleaning, visualization, regression, model validation  

---

## Works Cited
List of sources and references used in the analysis.
