# Customer Purchase Prediction

**Python | Pandas | Scikit-learn | Seaborn | Matplotlib**

## Project Overview

This project uses logistic regression to predict whether a customer will purchase a product based on their age and estimated salary.

The objective was to develop a classification model, evaluate its predictive accuracy, and visualize the results using a confusion matrix.

## Methodology

The dataset was loaded and processed using Pandas. The model used two independent variables: Age and Estimated Salary.

The data was divided into 75% training and 25% testing subsets. Features were standardized before training a logistic regression classification model using Scikit-learn.

## Results

The model achieved **80.00% accuracy** on the testing dataset, correctly classifying four out of five observations.

### Confusion Matrix

<img width="733" height="590" alt="Customer Purchase Prediction Confusion Matrix" src="https://github.com/user-attachments/assets/5a864ea4-bfa9-480e-b360-2d9eac91a9e9" />

The confusion matrix visualizes the model's correct and incorrect predictions for purchase and non-purchase outcomes.

## Skills Demonstrated

- Python programming
- Data preprocessing
- Logistic regression
- Supervised machine learning
- Train/test splitting
- Feature scaling
- Model evaluation
- Data visualization

## Running the Project

Install dependencies:

`pip install -r requirements.txt`

Run the script:

`python purchase_prediction.py`
