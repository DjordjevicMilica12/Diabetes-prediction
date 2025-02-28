**Project Overview**

This project explores two different algorithms for diabetes prediction. We approached the problem as a binary classification task, where each instance had an "Outcome" column value of either 1 or 0, depending on whether the individual had diabetes or not.

We used Decision Trees and Gradient Boosting. However, the results were not satisfactory, as the models did not achieve the desired performance, especially in terms of recall. The main objective was to accurately predict True Positive values, which was unsuccessful. We identified the primary issue as an insufficient number of features used for prediction. As an improvement, we suggest expanding the dataset with additional features.

This project consisted of several stages: data preparation and preprocessing, feature selection, exploratory and graphical analysis, model building (training with different hyperparameters and selecting the best one), followed by testing and evaluation using performance metrics and a confusion matrix.


**Project Explanation and Setup Guide**

1. *preparation&preprocessing.ipynb*
This file is part of the project where we prepared the data for analysis, familiarized ourselves with the dataset, handled outliers and missing values, and selected the features that would be used in the project. The original data is stored in **diabetes.csv**, while the cleaned dataset is saved in **diabetes_preprocessed.csv**.

2. *exploratory_analysis.ipynb*
This file contains the code for the visualizations used in the data analysis, exploring the relationships between multiple variables and the target variable. The goal was to gain a deeper understanding of the dataset and identify significant patterns.

3. *model_performance_comparison.ipynb*
This file represents the final and most crucial part of the project—building machine learning models, training and testing them, and evaluating their performance. At the end of the file, you will find the conclusions we drew based on the analysis and the results obtained.
