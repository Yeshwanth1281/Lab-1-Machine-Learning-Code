# Lab-1-Machine-Learning-Code
Student Performance Prediction
Overview
This project aims to predict student performance based on various demographic and academic factors using logistic regression. The dataset used for this analysis is studentInfo.csv, which contains information about students' demographics, academic background, and final outcomes.

Data Preprocessing
Loading Data: The data is loaded using the read.csv function from base R.
Preprocessing:
The final_result variable is transformed into a binary indicator of student success (is_passed), where 1 represents passing and 0 represents failing.
The disability variable is converted into a factor variable (disability_status).
The imd_band variable is converted to a numeric scale based on specified categories.
The dataset is split into training and test sets manually, with 80% of the data used for training.
Modeling
Logistic Regression: A logistic regression model is built using the glm function with a binomial family and logit link function.
Model Summary: Summary statistics of the logistic regression model are displayed to evaluate the model fit.
Evaluation
Prediction: The model is used to predict student outcomes on the test data.
Accuracy Calculation: Model accuracy is calculated by comparing predicted outcomes with true outcomes in the test data.
Files
studentInfo.csv: Dataset containing student information.
student_performance_prediction.R: R script for data preprocessing, modeling, and evaluation.
README.md: Description of the project, instructions, and overview of files.
Instructions
Ensure studentInfo.csv is in the current working directory.
Run the student_performance_prediction.R script in R environment.
Check the accuracy of the logistic regression model for predicting student performance.
