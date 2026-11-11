# Liver Disease Prediction Using Statistical Analysis

## Project Overview

This project focuses on analyzing liver disease-related patient data using statistical methods and data analysis techniques.

We used the Indian Liver Patient Dataset to explore different health-related features, identify patterns, compare patients with and without liver disease, and understand the relationships between different medical indicators.

This project was completed as an academic group project by five members.

## Project Objectives

- To understand and explore the liver patient dataset.
- To calculate descriptive statistical measures.
- To identify missing values and outliers.
- To visualize and analyze patient health-related data.
- To compare liver disease and non-liver disease groups.
- To apply probability and probability distributions.
- To perform correlation and regression analysis.
- To conduct hypothesis testing and calculate confidence intervals.
- To identify important statistical patterns related to liver disease.

## Dataset Information

**Dataset Name:** Indian Liver Patient Dataset

**Dataset Overview:**
- Original Observations: 583
- Original Variables: 12
- Observations After Removing Missing Values: 579
- Variables After Removing Missing Values: 11
- Target Variable: Liver Disease

**Important Features:**
- Age
- Gender
- Total Bilirubin
- Direct Bilirubin
- Alkaline Phosphotase
- SGPT
- SGOT
- Total Proteins
- Albumin
- Albumin and Globulin Ratio

## Technologies and Libraries Used

- **Programming Language:** Python
- **Platform:** Google Colab

**Libraries:**
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn

## Project Workflow

### 1. Data Loading and Exploration

- Loaded the Indian Liver Patient Dataset.
- Examined the dataset structure, rows, columns, and data types.
- Identified important variables.

### 2. Descriptive Statistical Analysis

- Calculated Mean, Median, Mode, Variance, and Standard Deviation.
- Analyzed important variables such as Bilirubin, Albumin, and Alkaline Phosphotase.

### 3. Missing Values and Outlier Detection

- Checked missing values in the dataset.
- Detected outliers using the Interquartile Range (IQR) method.

### 4. Data Visualization

Created different visualizations, including:

- Histograms
- Boxplots
- Scatter plots
- Bar charts
- Correlation heatmaps
- Scatter matrices
- Pairplots

### 5. Probability and Probability Distributions

Applied the following concepts:

- Basic Probability
- Conditional Probability
- Bayes' Theorem
- Binomial Distribution
- Normal Distribution
- Uniform Distribution
- Exponential Distribution
- Central Limit Theorem (CLT)

### 6. Correlation and Regression Analysis

- Examined relationships between important health-related variables.
- Applied correlation analysis.
- Used Simple Linear Regression to study the relationship between Total Bilirubin and Albumin.

### 7. Hypothesis Testing

Performed independent t-tests to compare liver disease and non-liver disease groups using:

- Total Bilirubin
- Albumin
- SGPT
- SGOT

### 8. Confidence Interval

Calculated a 95% confidence interval for Total Bilirubin.

## Results and Key Findings

### 1. Correlation Analysis

| Variables | Correlation |
|---|---:|
| Total Bilirubin vs Direct Bilirubin | 0.8745 |
| Albumin vs Total Proteins | 0.7831 |
| SGPT vs SGOT | 0.7919 |
| A/G Ratio vs Liver Disease | -0.1631 |

### 2. Regression Analysis

The relationship between Total Bilirubin and Albumin was examined using Linear Regression.

**Regression Equation:**

Albumin = 3.2358 - (0.0285 × Total Bilirubin)

**R-squared:** 0.0494

### 3. Hypothesis Testing

Independent t-tests were performed to compare the two patient groups.

| Variable | P-value |
|---|---:|
| Total Bilirubin | 8.63 × 10⁻⁸ |
| Albumin | 0.000113 |
| SGPT | 0.0000805 |
| SGOT | 0.000246 |

All four tests showed statistically significant differences at the 0.05 significance level.

### 4. Probability Analysis

- Probability of Liver Disease: 0.7150
- Probability of Liver Disease given High Bilirubin: 0.9565

### 5. Confidence Interval

The calculated 95% confidence interval for Total Bilirubin was:

- Lower Limit: 2.807
- Upper Limit: 3.824

## Key Observations

- Total Bilirubin and Direct Bilirubin have a strong positive correlation.
- SGPT and SGOT also show a strong positive correlation.
- Liver disease patients have higher average Bilirubin, SGPT, and SGOT levels in the analyzed dataset.
- Albumin levels are lower on average in the liver disease group.
- Hypothesis testing shows significant differences between the two groups for the four examined variables.
- Statistical analysis helps identify patterns and relationships in patient data.

## Project Files

- `STA.ipynb` – Contains the Python code, statistical calculations, data analysis, visualizations, and results.

## Contributors

This academic project was completed collaboratively by:

1. Somaya Akter
2. Md Sharzil Karim
3. Ayman Nehar Siddiqa Sayma
4. Afia Jainab
5. Sadia Shawdagar Bushra

## Project Information

- **Project Type:** Academic Group Project
- **Domain:** Statistics and Data Analysis
- **Dataset:** Indian Liver Patient Dataset
- **Platform:** Google Colab

## Future Improvements

- Apply Machine Learning classification algorithms.
- Compare different prediction models.
- Improve model performance through feature selection and preprocessing.
- Develop a more complete liver disease prediction system.

## Disclaimer

This project is developed for academic and educational purposes only. The statistical findings are not intended to replace professional medical advice or diagnosis.
