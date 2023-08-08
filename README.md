# Welcome to My Paypal
***

## Task
The task is to build a fraud detection model using a dataset of credit card transactions. The challenge lies in accurately identifying fraudulent transactions while dealing with an imbalanced dataset and limited information about the features.

## Description
To solve the problem, we have developed a fraud detection model using machine learning techniques. The dataset consists of anonymized features resulting from PCA transformation, along with the 'Time' and 'Amount' features. We have employed a combination of over and undersampling techniques to tackle the class imbalance. Exploratory data analysis was conducted to understand feature relationships, detect outliers, and create new features using 'Time' and 'Amount'. A pipeline was constructed to preprocess the data and train various classification algorithms. Model performance was evaluated using the area under the precision-recall curve (AUPRC). Our results indicate that the Random Forest Classifier is the best model for fraud detection.

## Installation
To install the project, please follow these steps:

Clone the repository
Install the required dependencies: pip install -r requirements.txt


## Usage
To use the project, follow these instructions:

Preprocess the data: python preprocess.py
Train the model: python train.py
Make predictions on new data: python predict.py
Make sure to provide the appropriate input data paths and adjust the hyperparameters as needed.

### The Core Team

Umar Kabir
<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
