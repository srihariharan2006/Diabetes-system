# Diabetes Prediction System

A machine learning project that predicts whether a patient has diabetes using an SVM classifier.

## Dataset
- **File:** `diabetes.csv`
- **Source:** Pima Indians Diabetes Dataset
- **Features:** Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age
- **Target:** Outcome (0 = Non-Diabetic, 1 = Diabetic)

## How It Works
1. Load and explore the dataset
2. Standardize features using `StandardScaler`
3. Split data into training and test sets
4. Train an SVM classifier
5. Evaluate accuracy on both sets

## Requirements
```
numpy
pandas
scikit-learn
```

## Usage
Open `DIABETS.ipynb` in Jupyter Notebook and run all cells.
