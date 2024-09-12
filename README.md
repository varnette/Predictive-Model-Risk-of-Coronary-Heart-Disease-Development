## Predictive Model: Risk of Coronary Heart Disease Development within 10 Years

<img width="608" alt="heart disease pic" src="https://github.com/user-attachments/assets/77706d99-bf1f-4413-b405-13efebcc2ff2">

## Overview
 
This project demonstrates my interest in public health and my ability to develop predictive models using logistic regression, as part of the requirements for the **Turing College Data Analytics Career Certificate**. The study focuses on predicting the 10-year risk of coronary heart disease (CHD), utilizing a dataset from Kaggle’s [Cardiovascular Study Dataset](https://www.kaggle.com/datasets/christofel04/cardiovascular-study-dataset-predict-heart-disea/data).

## Purpose

Coronary heart disease (CHD) is a leading cause of death globally and in the US, with substantial healthcare costs that exceed $200 billion annually in the US alone. Despite being largely preventable, CHD remains a significant public health burden. This project aims to predict the presence of CHD within a 10-year period using logistic regression, based on demographic, behavioral, and medical data. The predictive model can support early intervention and reduce both economic and health impacts of CHD.

## Project Details

The analysis follows a structured approach, including data cleaning, exploratory data analysis, feature selection, model training, and evaluation. It involves:

- **Data Analysis**: Conducting an exploratory data analysis to understand and prepare the dataset for modeling.
- **Feature Selection**: Identifying the most relevant features to include in the logistic regression model.
- **Model Fitting**: Building a logistic regression model to predict the 10-year risk of CHD.
- **Model Evaluation**: Assessing model performance using metrics such as recall, precision, and ROC-AUC.

## Key Insights and Recommendations

The project concludes with a two-step screening approach for identifying individuals at risk for CHD:

1. **Initial Broad Screening Test**: Utilizes a high-sensitivity model to minimize false negatives (threshold at 0.10).
2. **Subsequent Highly Specific Test**: Applies a model with a higher threshold (0.48) to minimize false positives from the initial screening.

The study also suggests that expanding the dataset and enhancing feature engineering could further improve model accuracy, demonstrating an analytical approach to addressing public health challenges through predictive modeling.

By completing this project, I have illustrated my proficiency in using logistic regression and predictive modeling to tackle significant public health issues.

[View the Jupyter Notebook](https://github.com/varnette/Predictive-Model-Risk-of-Coronary-Heart-Disease-Development/blob/main/Arnette_Cardiovascular_Log_Regression.ipynb)
