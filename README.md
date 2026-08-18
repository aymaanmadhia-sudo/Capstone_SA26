# GreenTravel Intelligence Challenge – HighCarbon Prediction

## Overview

Machine Learning project developed for the **GreenTravel Intelligence Challenge** to predict whether a business trip will be classified as **HighCarbon before booking**.

## Approach

* Performed exploratory data analysis to identify the strongest factors affecting HighCarbon trips.
* Created **8 features** using route, transport mode, domestic travel, hotel nights, costs, and policy information.
* Used **target encoding** for route and shipping type while avoiding data leakage.
* Trained a **Gradient Boosting Classifier** with 5-fold cross-validation.
* Evaluated the model using ROC-AUC, Precision, Recall, F1-score, ROC Curve, and Confusion Matrix.

## Results

* **5-Fold CV ROC-AUC: 0.99821**
* **AUC: 0.99770**
* **Precision: 0.98537**
* **Recall: 0.96515**
* **F1 Score: 0.97515**

The model's predictions were mainly driven by **route and transport mode**, with `route_te` being the most important feature.

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Jupyter Notebook.

## Key Takeaway

The analysis showed that **where a trip travels and how it travels** are the strongest signals for predicting its carbon category.

## Author

**Aymaan Madhia**

