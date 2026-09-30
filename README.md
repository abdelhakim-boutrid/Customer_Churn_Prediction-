# Customer Churn Prediction

A machine learning project to predict whether a telecom customer is likely to churn.

I built this project to practice the main steps of a machine learning workflow, from data preprocessing to deploying a simple prediction interface.

## What I did

- Explored and cleaned the Telco Customer Churn dataset
- Encoded categorical features and scaled numerical features
- Used SMOTE to handle class imbalance
- Trained Random Forest and XGBoost models
- Used GridSearchCV for hyperparameter tuning
- Evaluated the model using accuracy, ROC-AUC and classification metrics
- Saved the trained model with Pickle
- Built a simple web interface with Flask

## Results

The final Random Forest model achieved around 78% accuracy on the test set.

## Technologies

Python, Pandas, NumPy, Scikit-learn, XGBoost, SMOTE, Flask, Matplotlib and Seaborn.

## Run the project

Install the dependencies and run:

python app.py

Then open:

http://127.0.0.1:5000
