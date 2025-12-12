# Global Disaster Analytics (2018–2024)
### Econometrics • Machine Learning • Data Science Project
This repository contains my full econometrics and machine learning analysis of global disaster events recorded between 2018 and 2024. The project explores how disaster intensity, response patterns, and economic losses shape casualty levels and recovery duration. It uses both classical statistical models and modern machine learning methods to uncover meaningful insights.

### Project Overview
The dataset contains 50,000 global disaster events with detailed attributes such as:
- Disaster type
- Severity index
- Casualties
- Economic loss
- Response time
- Aid amount
- Response efficiency
- Recovery days
- Geographic coordinates

A stratified 5,000-sample subset was used for analysis to optimize computation while preserving representativeness.

This project integrates:
- Exploratory Data Analysis (EDA)
- Hypothesis testing (Pearson correlation)
- Econometric modeling (OLS, Logistic Regression)
- Machine learning classification (PyCaret)
- K-Means and DBSCAN clustering

### Key Questions Explored
1. What factors drive the number of days required for communities to recover after a disaster?
2. Can casualty levels (High vs Low) be predicted using available features?
3. How do disasters naturally group together based on their characteristics?
4. How effective are machine learning models at predicting severity levels?

### Methods Used
1. Exploratory Data Analysis
- Histograms
- KDE Plots
- Correlation Matrix
- Disaster Type Distribution
- Time-series trends (2018–2024)
2. Econometrics
- OLS Regression to model the determinants of recovery duration
- Logistic Regression to predict high–casualty disasters
- Multicollinearity checks
- Statistical significance testing
3. Machine Learning Models
Using PyCaret
- Gradient Boosting
- Random Forest
- Logistic Regression
- AdaBoost
- KNN
- LightGBM
- SVM
- Naive Bayes
- Extra Trees
- Baseline Dummy Classifier

Best Model: Gradient Boosting Classifier
- Accuracy: 93.5%
- AUC: 0.984
4. Clustering (Insupervised Learning)
- K-Means: Identified 4 natural disaster clusters
- DBSCAN: Used for density-based outlier detection
- k-NN distance plot used for EPS calibration

### Major Findings
- Severity index is the strongest predictor of both casualties and recovery days.
- Response time is strongly and negatively correlated with recovery (r ≈ –0.655).
- Recovery time decreases significantly with higher response efficiency.
- Machine learning models predict severity with high accuracy.
- Clustering reveals four meaningful disaster groupings: Low-severity/low-impact events, Moderate disasters, High-casualty events, Extreme, high-economic-loss events

### Recommendations Based on Analysis
- Countries should invest in faster response systems to reduce recovery duration.
- Strengthen early-warning and climate resilience systems to reduce severity.
- Improve logistics and communication for better response efficiency.
- Machine learning should be integrated into national disaster forecasting systems.
- Aid allocation should be more targeted and data-driven.
- Cluster-based disaster policy planning can help optimize intervention strategies.
