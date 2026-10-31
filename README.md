# Socioeconomic Factors Influencing COVID-19 Deaths in England

## Project Overview

This project investigates the relationship between socioeconomic characteristics and COVID-19 mortality across different regions of England.

Using R programming and statistical analysis, the study explores how demographic, housing and health-related factors are associated with COVID-19 death rates. The analysis uses data from UK Census-related variables to identify patterns, relationships and potential contributing factors.

## Research Objectives

- Examine the relationship between socioeconomic characteristics and COVID-19 mortality.
- Analyse the influence of different age groups on mortality rates.
- Investigate associations between housing conditions and COVID-19 deaths.
- Explore the relationship between population health conditions and mortality.
- Apply statistical techniques to identify significant relationships and patterns.

## Technologies & Libraries

- **Programming Language:** R
- **Data Analysis:** Base R, dplyr, tidyr
- **Statistical Analysis:** psych, ppcor, car
- **Data Visualisation:** ggplot2, corrplot, corrgram
- **Statistical Modelling:** Multiple Linear Regression, Principal Component Analysis

## Project Structure

```text
Socioeconomic-Factors-Influencing-COVID-19-Deaths/
│
├── Plots and graphs/
├── Final1.csv
├── R code.r
└── README.md
```

## Methodology

### 1. Data Preparation

- Imported and inspected the dataset.
- Examined missing values and removed incomplete observations.
- Reviewed variable types and summary statistics.
- Exported the cleaned dataset.

### 2. Exploratory and Descriptive Analysis

- Calculated mean, standard deviation, minimum and maximum values.
- Examined mortality distributions using histograms and boxplots.
- Used Q-Q plots and normality tests to assess distribution characteristics.

### 3. Correlation Analysis

- Applied Pearson and Spearman correlation methods.
- Examined relationships between mortality rates and demographic variables.
- Investigated associations involving housing and health conditions.
- Performed partial correlation analysis.

### 4. Factor Analysis and Principal Component Analysis

- Applied the Kaiser-Meyer-Olkin (KMO) test.
- Examined eigenvalues and scree plots.
- Used principal component analysis with Varimax rotation to explore underlying patterns in the variables.

### 5. Multiple Linear Regression

- Developed multiple linear regression models to investigate associations with COVID-19 mortality.
- Examined multicollinearity using Variance Inflation Factor (VIF).
- Applied stepwise model selection.
- Evaluated model residuals and relative variable importance.

## Key Variables

The analysis includes:

- **Age:** Population groups ranging from 0–19 to 60 and above.
- **Housing:** Shared dwellings, unshared flats and unshared bungalows.
- **Health:** Good, fair and poor health categories.
- **Outcome variable:** Total COVID-19 deaths per thousand.

## Key Learning Outcomes

- Practical application of statistical analysis using R.
- Experience with data cleaning and exploratory data analysis.
- Understanding of correlation and partial correlation techniques.
- Application of PCA and multiple linear regression.
- Experience interpreting statistical relationships and evaluating regression models.

## Future Improvements

- Add a detailed comparison of statistical model results.
- Improve visual presentation of key findings.
- Explore additional socioeconomic indicators.
- Evaluate model assumptions and robustness.
- Improve reproducibility through a structured analysis workflow.

---

