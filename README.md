# Diabetes-Prediction-Model

Diabetes Prediction Model using Support Vector Machine(SVM) classifier
This project demonstrates the development of a machine learning model to predict the likelihood of diabetes based on medical diagnostic measurements. The model utilizes the Pima Indians Diabetes Database.

Dataset Description
The dataset used for this project contains the following columns:
Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skinfold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body Mass Index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: Diabetes pedigree function (a function which scores likelihood of diabetes based on family history)
Age: Age in years
Outcome: Class variable (0: Non-diabetic, 1: Diabetic)

Project Workflow

Data Preprocessing
Standardized the dataset using StandardScaler to ensure uniform scaling for optimal model performance.
Train-Test Split
Split the dataset into training and testing sets for evaluation of model performance.

Model Selection and Training
Used Support Vector Machine (SVM) algorithm for classification.

Model Evaluation
Achieved an accuracy of:
78.6% on training data
77.2% on testing data

Predictive System
Created a system where users can input the above medical parameters to predict the likelihood of diabetes.

Key Libraries Used
Pandas: For data manipulation and analysis
NumPy: For numerical operations
Scikit-learn: For machine learning algorithms and evaluation metrics

Results
The SVM model provides a reliable prediction of diabetes with an accuracy of over 77% on the test set. This demonstrates the potential for using machine learning in medical diagnostics to aid healthcare professionals.

Future Improvements
Optimize the hyperparameters of the SVM model for improved performance.
Experiment with other machine learning algorithms.
Add more features to the dataset for better accuracy.
Create a web or mobile application for easier access to the predictive system.

Acknowledgment
The dataset used in this project is from the Pima Indians Diabetes Database.
Thanks to siddharthan(youtube) for teaching concepts with great clarity.


The dataset used in this project is from the Pima Indians Diabetes Database.
