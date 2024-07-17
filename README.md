# Wine Quality Analysis

### Authors: Min Jegal, Alba Arribas

### Date: 2023-12-24

## Project Overview

This project aims to analyze a wine dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality). The dataset is divided into red and white wine data, both containing 12 variables. Our primary goal is to determine which factors affect wine quality the most and how these factors differ between red and white wines.

## Dataset Description

The dataset consists of the following variables:

- **Fixed Acidity**: Non-volatile acids in wine.
- **Volatile Acidity**: Amount of acetic acid in wine, which can lead to an unpleasant vinegar taste if too high.
- **Citric Acid**: Found in small quantities, can add freshness and flavor to wines.
- **Residual Sugar**: The amount of sugar remaining after fermentation.
- **Chlorides**: The amount of salt in the wine.
- **Free Sulfur Dioxide**: The free form of SO2 exists in equilibrium and prevents microbial growth.
- **Total Sulfur Dioxide**: The combination of free and bound forms of SO2.
- **Density**: Related to the alcohol and sugar content of the wine.
- **pH**: Describes how acidic or basic a wine is, typically between 3-4.
- **Sulphates**: Acts as an antimicrobial and affects sulfur dioxide (SO2) levels.
- **Alcohol**: The percent alcohol content of the wine.
- **Quality**: The output variable, a sensory score between 0 and 10.

## Objectives

1. Identify the factors that most significantly impact wine quality.
2. Understand how these factors differ between red and white wines.

## Technologies and Models

### Programming Language and Tools

- **R**: Used for data analysis and visualization.
- **RMarkdown**: For creating dynamic documents that include code, text, and results.
- **R Packages**: 
  - `dplyr`: For data manipulation.
  - `ggplot2`: For data visualization.
  - `caret`: For machine learning model training and evaluation.

### Machine Learning Models

1. **Linear Regression**:
   - Used to predict the quality of wine based on the input variables.
   - Helps understand the relationship between each feature and the wine quality score.

2. **Random Forest**:
   - An ensemble learning method used for both classification and regression.
   - Applied to identify the most important variables that affect wine quality.
   - Provides better accuracy and handles non-linear relationships well.

3. **Support Vector Machine (SVM)**:
   - Used for classification tasks.
   - Helps differentiate between high-quality and low-quality wines.

4. **Cross-Validation**:
   - Employed to evaluate the performance of the models.
   - Ensures that the models generalize well to unseen data
