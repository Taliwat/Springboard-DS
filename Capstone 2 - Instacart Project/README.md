# Next-Order Predictions with Model Stacking and RNN-LSTM: An Advanced Approach to Instacart User Behavior

## Project Summary
This project aims to develop a sophisticated predictive model to forecast the next set of purchases for users based on historical order data from the Instacart dataset, originally featured in a previous Kaggle competition. By leveraging model stacking, RNN-LSTM networks, and Bayesian Optimization, we seek to enhance prediction accuracy and robustness. The project is organized into several Jupyter Notebooks, each detailing different stages of the data science workflow.

### Table of Contents
1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Objectives](#objectives)
4. [Tools and Technologies](#tools-and-technologies)
5. [Notebooks](#notebooks)
6. [How to Run](#how-to-run)
7. [Conclusion](#conclusion)

#  Introduction
Understanding and anticipating customer purchasing behavior is critical for improving user experience and optimizing inventory management in e-commerce platforms. This project uses the Instacart dataset to predict future purchases, enabling personalized recommendations and better operational decisions.

## Problem Statement
The objective is to build a predictive model capable of forecasting the next 'n' purchases for users based on their historical order data. We implement and compare various machine learning models, including logistic regression, XGBoost, and RNN-LSTM networks, and enhance model performance through model stacking and Bayesian optimization.

## Objectives
-Develop a robust predictive model.
-Compare multiple machine learning approaches.
-Optimize model performance.
-Evaluate models using standard metrics.

## Tools and Technologies
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, XGBoost, TensorFlow/Keras, Hyperopt

Visualization: Matplotlib, Seaborn
Platform: Jupyter Notebooks

## Notebooks
[main.ipynb](https://github.com/Taliwat/Springboard-DS/blob/master/Capstone%202%20-%20Instacart%20Project/main.ipynb): Data wrangling, initial importing, imputation, and merging of datasets.
[eda.ipynb](https://github.com/Taliwat/Springboard-DS/blob/master/Capstone%202%20-%20Instacart%20Project/eda.ipynb): EDA for main df to discover and explore surface trends before going forward.
[preprocessing.ipynb](https://github.com/Taliwat/Springboard-DS/blob/master/Capstone%202%20-%20Instacart%20Project/preprocessing.ipynb): Feature Engineering to discover any potentially useful features to use as well as the inclusion of our baseline model in Logistic Regression, plotted and resampled with GridSearchCV.
[modeling.ipynb](https://github.com/Taliwat/Springboard-DS/blob/master/Capstone%202%20-%20Instacart%20Project/modeling.ipynb): Addition of RNN-LSTM model as well as XGBoost, to further look at the metric table's results.  Then model stack before we optimize the results.
[conclusion.ipynb](): Conclusion summary and presentation of findings.

## Conclusion
This project demonstrates an advanced approach to predicting user purchases using a combination of traditional machine learning techniques and modern neural network architectures. By integrating model stacking and Bayesian optimization, we aim to deliver a highly accurate and robust predictive model, providing valuable insights for personalized recommendations in e-commerce platforms like Instacart.







