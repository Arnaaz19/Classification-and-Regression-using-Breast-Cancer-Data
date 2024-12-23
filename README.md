Predictive Modeling of PCR and RFS in Breast Cancer Using Machine Learning

Overview

This repository contains the code, data, and documentation for our project on predictive modeling of Pathological Complete Response (PCR) and Relapse-Free Survival (RFS) in breast cancer patients using machine learning techniques. The goal of the project is to enhance the precision, efficacy, and personalization of breast cancer treatment strategies by leveraging clinical and MRI data.

Features
	•	Classification Models: Logistic Regression, Random Forest, and Support Vector Machine to predict PCR.
	•	Regression Models: Linear Regression, Random Forest Regressor, Gradient Boosting, and Decision Tree to predict RFS.
	•	Data Preprocessing:
	•	Missing value imputation
	•	Min-max scaling for normalization
	•	Correlation analysis for feature selection
	•	Model Evaluation: Metrics such as RMSE, R-Squared, Precision, Recall, and F1 Score.
	•	Hyperparameter Tuning: Optimization of models for better performance and generalization.

Project Structure
	•	data/: Contains the dataset used for training and testing.
	•	notebooks/: Jupyter notebooks detailing the exploratory data analysis (EDA) and model development.
	•	models/: Trained model files and configurations.
	•	src/: Python scripts for preprocessing, feature selection, and model training.
	•	docs/: Documentation and report of the project.
	•	results/: Output files, visualizations, and evaluation metrics.
Results

The key findings of the project include:
	•	Gradient Boosting emerged as the best regression model for RFS prediction.
	•	Neural Networks performed well in PCR classification tasks with an F1 score of 0.55 on the test set.

Contributors
	•	Harish Mohan
  •	Arnaaz Khan
  •	Saanidhya Khurana

License
This project is licensed under the MIT License. See the LICENSE file for details.
