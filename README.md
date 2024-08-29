#  Cancer Prediction with Python
Introduction
This project demonstrates how to train a logistic regression model to predict whether a cell is malignant or benign based on specific measurements. We utilize the Breast Cancer dataset, which contains detailed cell measurements and corresponding diagnoses.

Dataset
The dataset used is the Breast Cancer dataset, which includes the following:

Features: Various measurements of cell nuclei (e.g., radius, texture, perimeter).
Target Variable: Diagnosis of the cell (0 for benign and 1 for malignant).
Project Workflow
Data Import and Exploration:

Loaded and explored the dataset to understand the structure and content.
Identified and dropped irrelevant columns (ID, Unnamed: 32).
Converted the target variable into a binary format (0 and 1).
Data Cleaning:

Visualized missing data using a heatmap and dropped columns with missing values.
Ensured the dataset was clean and ready for modeling.
Data Preprocessing:

Normalized the feature variables to ensure consistent scaling.
Split the dataset into training and testing sets (70% train, 30% test).
Model Training:

Trained a logistic regression model using the training data.
Evaluated the model's performance on the test set, achieving an accuracy of 98%.
Model Evaluation:

Assessed the model using accuracy, precision, recall, and F1 score.
Observed that the model performs well on the dataset, making it reliable for predictions.
Conclusion
The logistic regression model effectively predicts whether a cell is malignant or benign based on the dataset. This model can be further integrated into a web application or backend service to assist doctors in diagnosing breast cancer, potentially improving patient outcomes.

Future Work
Deployment: Integrate the model into a web application using Flask or a similar framework.
Further Evaluation: Test the model with other evaluation metrics or datasets to ensure robustness.
