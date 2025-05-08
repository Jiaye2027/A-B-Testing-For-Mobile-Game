# A-B-Testing-For-Mobile-Game

This repository contains the analysis and implementation of an A/B Testing experiment for a mobile game application. The purpose of the experiment is to optimize game features and enhance user engagement based on statistical testing and data-driven decisions.

## Project Overview

A/B Testing is a controlled experiment comparing two or more variants to determine which version performs better based on a predefined metric. This project analyzes game user data to evaluate feature performance, aiming to:
* Increase user retention
* Boost in-game purchases
* Improve overall user experience

## Technologies Used
* Pandas & NumPy: Data manipulation and analysis
* Matplotlib & Seaborn: Data visualization
* Scipy & Statsmodels: Statistical testing and hypothesis validation

## Key Concepts

* Data Preprocessing:
  - Handled over 90,000 user records including missing values, duplicates, and outliers using quantile-based filtering and IQR.
  - Applied boolean encoding to retention metrics and ensured version labeling consistency.
* Statistical Hypothesis Testing:
  - Verified normality assumptions using the Shapiro-Wilk test before choosing parametric vs non-parametric tests.
  - Applied independent t-tests to compare user engagement (game rounds) between control and test groups.
  - Used Mann–Whitney U test as a non-parametric alternative for skewed distributions.
* Data Visualization:
  - Used Seaborn and Matplotlib to create histograms, boxplots, and retention bar charts.
  - Visualized group distributions before and after outlier removal to communicate data integrity.
* Results Analysis:
  - Calculated and interpreted p-values and confidence intervals.
  - Making data-driven decisions based on statistical evidence.

## Results and Insights
The experiment results are documented in the notebook, highlighting significant differences between the test groups. Key findings include:
* Impact of feature changes on user engagement.
* Statistical significance of A/B test results.
* Recommendations for game optimization.

