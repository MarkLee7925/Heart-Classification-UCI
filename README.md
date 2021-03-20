# Heart-Classification-UCI

Machine Learning classification project utilizing various models to predict if a patient has heart disease. Additionally, data visualization was used in this project to showcase various attributes and their relationships with one another.

## Dataset:

The dataset was retrieved from the UCI Machine Learning Repository (link: https://archive.ics.uci.edu/ml/datasets/Heart+Disease). It contains 303 samples; each representing a patient tested. 

Each patient was classified using the following 13 (out of 76) features:

1. **age** - Age of patient
2. **sex** - Gender\
  -- 0 = Female\
  -- 1 = Male
3. **cp** - Chest Pain type\
  -- 0 = Nontypical\
  -- 1 = Nonanginal\
  -- 2 = Asymptomatic\
  -- 3 = Typical
4. **trestbps** - Resting blood pressure (in mmHg)
5. **chol** - Serum Cholestorol in (mg/dl)
6. **fbs** - (Fasting blood sugar > 120 mg/dl)\
   -- 1 = True\
   -- 0 = False
7. **restecg** - Resting electrocardiographic (ECG) results\
  -- 0 = normal\
  -- 1 = having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)\
  -- 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria
8. **thalach** - Maximum heart rate achieved
9. **exang** - Exercise induced angina\
  -- 1 = yes\
  -- 0 = no
10. **oldpeak** - ST depression induced by exercise relative to rest
11. **slope** - Slope of the peak exercise ST segment\
  -- 1 = upsloping\
  -- 2 = flat\
  -- 3 = downsloping
12. **ca** - Number of major vessels (0-3) colored by flourosopy
13. **thal** - Thalassemia\
  -- 3 = normal\
  -- 6 = fixed defect\
  -- 7 = reversable defect
14. **num** - Dependent Variable (predicted target attribute)\
  -- 0 = No heart disease\
  -- 1 = Heart disease

## Models:

This project utilizes the following Machine Learning models:

- Deep Neural Network (DNN) using the Sequential class
- Logistic Regression (LogReg)
- Random Forest (RF)
- Support Vector Classification (SVC)
- XGBoost (XGB)

The **XGBoost** model was determined to be the most consistently accurate at **85.794%**.
