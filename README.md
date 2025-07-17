# sonar
zSonar Rock vs Mine Classification
This project focuses on building a machine learning model to classify sonar signals as either rocks or mines using Logistic Regression.
Overview
Sonar signals are used to detect and classify objects underwater. This classification task helps in identifying whether the detected object is a rock (R) or a mine (M) based on the sonar data. The dataset used contains 208 samples with 60 features each, representing frequency-based energy measurements.
Workflow
Loading the Data   The sonar dataset is loaded into a Pandas DataFrame for exploration and analysis. 
Data Preprocessing   Basic statistical analysis is done to understand feature distributions.   The label column (column 60) is separated from the features. 
Train-Test Split   The data is split into training and testing sets using an 90/10 ratio, while preserving the class distribution through stratification. 
Model Building   A Logistic Regression model is trained on the training data to learn the patterns and relationships between input features and labels. 
Model Evaluation   The model is evaluated on both training and testing data. 
Training accuracy: ~83% 
Testing accuracy: ~76% 
Prediction System   A simple prediction pipeline is built where new sonar data can be input to get a classification result (Rock or Mine). 
Conclusion
The model provides a baseline solution for sonar-based object classification using a simple yet effective algorithm. It demonstrates the applicability of logistic regression in binary classification problems.
