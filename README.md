# Predicting Heart Failure with Machine Learning
Testing the effectiveness of different Machine Learning models at predicting heart failure

## Introduction
This investigation involved analyzing patient records and diagnoses from Cleveland Clinic to identify symptoms that highly correlated to heart disease fatalities, then evaluating the effectiveness of 3 machine learning models at predicting heart disease.

An effective model accurately predicts whether a patient, given their described symptoms, is likely to experience heart failure. I used the Logistic Regression model, Decision Tree classifier, and K-Nearest Neighbors algorithm to predict whether a patient would experience heart failure. 

## Results
We used a correlation matrix to identify chest pain, ST depression, number of major blood vessels, and thalassemia as symptoms with the highest correlation to heart disease. 

<img width="506" alt="image" src="https://github.com/ShreyanshMisra/HeartDiseasePrediction/assets/80748482/b3e0c535-9967-4f82-983e-b0d5835f9213">


The Logistic Regression model was most effective at predicting heart disease with an accuracy of 88%. Similarly to what we identified through the correlation matrix, the most important features in the logistic regression model were the number of major blood vessels, chest pain, and thalassemia.

<img width="638" alt="image" src="https://github.com/ShreyanshMisra/HeartDiseasePrediction/assets/80748482/730f292b-0fca-41d0-a8ea-527fe9eb3b72">


## Files
- `data.csv`
- `prediction.ipynb` 

### Citations
- Heart failure clinical records. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C5Z89R.
