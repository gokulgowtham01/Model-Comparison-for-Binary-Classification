# Model-Comparison-for-Binary-Classification

This project evaluates the performance of four classification algorithms on a binary classification problem using a dataset from SpaceX launch data. The following models are compared:

Logistic Regression
Support Vector Machine (SVM)
Decision Tree Classifier
K-Nearest Neighbors (KNN)
Features

## Data Preparation:

Loads and preprocesses the dataset.
Scales features using StandardScaler.

##Model Training & Hyperparameter Tuning:
Utilizes GridSearchCV to find optimal parameters for each model.

##Evaluation:

Generates and displays confusion matrices for each model.
Computes performance metrics: Jaccard Score, F1 Score, and Accuracy.

##Requirements
pandas
numpy
scikit-learn
matplotlib
seaborn

##How to Use
Clone the repository.
Install the required packages.
Run the script to see the model performances and confusion matrices.

##Results
The script outputs confusion matrices and a performance comparison table showing Jaccard Scores, F1 Scores, and Accuracy for each model.
