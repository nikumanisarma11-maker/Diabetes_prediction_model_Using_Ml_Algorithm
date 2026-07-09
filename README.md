# Diabetes Prediction using Machine Learning

## Project Overview
This project predicts whether a patient has diabetes using Machine Learning algorithms.

## Dataset
- diabetes.csv
- Features include:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Machine Learning
This project compares the performance of three machine learning classification algorithms:

- K-Nearest Neighbors (KNN) – Uses nearby similar patients to make predictions.
- Decision Tree – Uses simple decision rules to classify patients.
- Support Vector Machine (SVM) – Separates diabetic and non-diabetic patients with the optimal  boundary.
- Ensemble - Combines the predictions of multiple machine learning models to improve performance and make more reliable predictions.

* Three machine learning models (KNN, Decision Tree, and SVM) were first trained and compared using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

Among these three models, the Support Vector Machine (SVM) achieved the best performance and was selected as the strongest individual model.

*After identifying SVM as the best individual model, an Ensemble model was developed. The Ensemble model was then compared with all the individual models.

The Ensemble model achieved the highest overall performance, providing better accuracy and more reliable predictions than KNN, Decision Tree, and SVM. Therefore, it is selected as the final model for diabetes prediction.

## Repository Structure
- diabetes.csv
- diabetes_Prediction_using_ML.ipynb
