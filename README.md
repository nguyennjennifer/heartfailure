## Overview

The purpose of this project is to demonstrate various methods of using machine learning classification to predict a target variable. Specifically,  kNN, decision trees, and logistic regression modeling will be used. After constructing each model, models will be improved through methods of cross-validation, boosting, tuning, and more. Additionally, ensemble models will also be utilized to make predictions. Specifically, an ensemble model will be constructed as a function that incorporates majority voting of multiple models. A random forest model will also be implemented to showcase homogenous learning. Confusion matrices and performance statistics of each model will be used to compare and contrast for model evaluation.

## About the data

The dataset used for this project contains information about heart failure clinical records from the Faisalabad Institute of Cardiology and the Allied Hospital in Faisalabad in Pakistan (Heart Failure Clinical Records, 2020). Data was originally collected to analyze the effects of serum creatinine and ejection fraction on heart failure patients.

The dataset has `r nrow(heart)` observations and `r ncol(heart)` variables. There are 6 categorical variables and 7 numerical variables. - `death_event`: 

This project aims to explore multiple classification models to predict the target variable `death event`. The `death event` variable is a binary variable that states if the patient died during follow up period (1 = death, 0 = survived).

## Author

Jennifer Nguyen

## Date Created

April 2024 

## Running the project

Please first download the `heart_failure_clinical_records_dataset.csv` file in order to follow along the project Rmd file. Please note all data pre-processing was done on the aforementioned csv file in a specific order. The Rmd and pdf files indicate which processes were done and why. 

## Help
Please [email](mailto:n.nguyenjennifer@gmail.com) me if you have any questions or concerns.
