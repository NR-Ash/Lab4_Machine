# Lab4_Machine

##Overview:
This lab focuses on data preprocessing using the StudentPerformanceFactors dataset. The goal is to identify data quality issues and apply common preprocessing techniques to prepare the data for analysis.

##Tasks
Task 1: Data Quality Assessment:
The dataset is examined to understand its structure and detect potential issues. This includes checking data types, missing values, duplicates, and basic statistical summaries.

Task 2: Missing Value Strategy:
Missing values are handled using median imputation, which replaces missing values with the median of the column. This method is less affected by extreme values.

Task 3: Outlier Detection and Handling (IQR):
Outliers in numerical features are detected using the Interquartile Range (IQR) method. Values outside the acceptable range are capped to reduce the impact of extreme values.

Task 4: Normalization:
Numerical features are normalized using Min-Max scaling and Z-score standardization to ensure features are on comparable scales.

Task 5: Principal Component Analysis (PCA):
Correlation between numerical features is analyzed. If correlations exist, PCA is applied to reduce dimensionality while preserving most of the variance.
