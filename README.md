# socioeconomic-status-prediction-ml-Model
final project 
Msc Data Science Project

Socioeconomic Status Prediction Using Employment and Demographic Data with Machine Learning Techniques

This paper presents an experiment with machine learning techniques for inference of socioeconomic status on demographic and employment characteristics. The entire exercise is cast as a binary income classification problem - predicting whether an individual earns more than or less than $50,000 per year.
 
The primary focus of this work is not centered on the deployment of applications, but a comparative analysis of the performance behavior of various machine learning models upon their application to real-world socioeconomic data, with an appropriate metric for measuring performance. Two models have been developed and compared: Logistic Regression and Random Forest. From experimental results obtained, Random Forest gave better predictive performance meaning that it had more strength in capturing complex relationships within the data.

Features Used  
The model training and testing rotated around demographic and occupational factors generally related to the outcome of income:  
OCCP, AGEP, POBP, WKHP, SCHL  
 
Models Implemented  
A comparable preprocessed dataset was used in the implementation of two supervised learning models.  
 
Logistic Regression  
Logistic regression is simple and easily understandable. It gives very clear results about linear relations between features and the target variable. It does not perform well when there are nonlinear interactions involved.  

Random Forest
Random Forest, as the more non-linear flexible model, was selected for it to pick complex interactions of features. It outperformed Logistic Regression across all evaluation metrics.
Accuracy: 0.79
AUC-ROC: 0.87
Feature importance analysis brought out occupation, age, place of birth, working hours, and education level as the most important predictors. More specifically, education level and weekly working hours have always come out strongly indicative of socioeconomic status.

Evaluation Approach
Model performance has been assessed through different metrics of evaluation to ensure a balanced and reliable comparison. These include, Accuracy, Precision, Recall, F1-score Area Under the ROC Curve (AUC-ROC). Just getting influenced by accuracy can be misleading in this type of task and hence such a multi-metric approach ensured that model performance is evaluated.


Key Findings  
Random Forest surpassed Logistic Regression in all evaluation metrics. Nonlinear feature interactions significantly contribute to SES prediction. Education level and working hours consistently emerge as strong predictors of income. Tree-based ensemble models are appropriate for socioeconomic data analysis.
License
This project is under the MIT license, strictly meant for academic and educational use.

