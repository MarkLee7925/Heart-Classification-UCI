# Heart-Classification-UCI

This Machine Learning classification project utilizes various models to predict if a patient has heart disease. Additionally, some data visualization was employed to showcase various attributes and their relationships with one another. This can be found in the heart-DNN.ipynb file.

## Dataset:

The dataset was retrieved from the UCI Machine Learning Repository (link: https://archive.ics.uci.edu/ml/datasets/Heart+Disease). It contains 303 samples; each representing a patient tested. 

Each patient was classified using the following 13 (out of the original 76) features:

1. **age** - age of patient
2. **sex** - gender
    - 0 = Female
    - 1 = Male
3. **cp** - Chest Pain type
    - 0 = Nontypical
    - 1 = Nonanginal
    - 2 = Asymptomatic
    - 3 = Typical
4. **trestbps** - resting blood pressure (in mmHg)
5. **chol** - Serum Cholestorol (in mg/dl)
6. **fbs** - (Fasting Blood Sugar > 120 mg/dl)
    - 1 = True
    - 0 = False
7. **restecg** - resting electrocardiographic (ECG) results
    - 0 = normal
    - 1 = having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    - 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria
8. **thalach** - maximum heart rate achieved
9. **exang** - exercise induced angina
    - 1 = yes
    - 0 = no
10. **oldpeak** - ST depression induced by exercise relative to rest
11. **slope** - slope of the peak exercise ST segment
    - 1 = upsloping
    - 2 = flat
    - 3 = downsloping
12. **ca** - number of major vessels (0-3) colored by Flourosopy
13. **thal** - Thalassemia
    - 3 = normal
    - 6 = fixed defect
    - 7 = reversable defect
14. **target** - Dependent Variable (predicted attribute)
    - 0 = No heart disease
    - 1 = Heart disease

## Models:

The following Machine Learning models were used for classification:

- Logistic Regression (LR)
- Support Vector Machine (SVM)
- Random Forest (RF)
- XGBoost (XGB)
- Deep Neural Network (DNN)

## References:

- Detrano, R., Janosi, A., Steinbrunn, W., Pfisterer, M., Schmid, J., Sandhu, S., Guppy, K., Lee, S., & Froelicher, V. (1989). International application of a new probability algorithm for the diagnosis of coronary artery disease. American Journal of Cardiology, 64,304--310. [Web Link]
- David W. Aha & Dennis Kibler. "Instance-based prediction of heart-disease presence with the Cleveland database." [Web Link]
- Gennari, J.H., Langley, P, & Fisher, D. (1989). Models of incremental concept formation. Artificial Intelligence, 40, 11--61.[Web Link]
- https://archive.ics.uci.edu/ml/datasets/Heart+Disease
