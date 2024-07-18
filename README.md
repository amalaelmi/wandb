# wandb
** Weight and Biases** 
_Description_
This project involves building and evaluating machine learning models to classify URLs. The dataset used includes various features extracted from URLs and a target label indicating whether the URL is malicious or benign. The models trained include Logistic Regression and Decision Tree classifiers. The results and metrics are logged using Weights and Biases (wandb).

**Table of Contents**
Description
Setup
Data Preprocessing
Model Training
Model Evaluation
Logging with Weights and Biases
Results
Contributing
License
Setup
Prerequisites
Python 3.x
Google Colab (optional, for running the notebook)
GitHub account
Weights and Biases account

**Installation**

_Open the notebook in Colab._
Save a copy in your own drive.
Follow the instructions to clone your GitHub repository and save the notebook back to GitHub or as a Gist.
_Data Preprocessing_
Load the dataset from the CSV file.
_Handle missing values:_
Fill missing values in features using SimpleImputer.
Remove rows with missing target values.
Split the data into training and testing sets.
_Model Training_
_Logistic Regression_
Initialize the Logistic Regression model.
Train the model using the training data.
Predict on the testing data.
_Decision Tree_
Initialize the Decision Tree classifier.
Train the model using the training data.
Predict on the testing data.
_Model Evaluation_
Evaluate the models using accuracy score.
Compare the performance of the Logistic Regression and Decision Tree models.
_Logging with Weights and Biases_
Initialize a wandb run.
Log model metrics such as accuracy.
End the wandb run.
_Results_
The models are evaluated based on their accuracy in classifying the URLs. The results are logged and visualized using Weights and Biases for easy comparison and analysis.

Contributing
Contributions are welcome! Please follow these steps:

This project is licensed under the MIT License - see the LICENSE file for details.
