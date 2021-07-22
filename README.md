# Heart Disease Analysis and Prediction


**Goal**

The goal of this notebook is to analyze the heart disease data obtained from [UCI](https://archive.ics.uci.edu/ml/datasets/Heart+Disease), and show which features have the most affect in the occurrence of heart disease.

**Limits**

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to this date.

**Content**

- age
- sex
- chest pain type (4 values)
- resting blood pressure
- serum cholestoral in mg/dl
- fasting blood sugar > 120 mg/dl
- resting electrocardiographic results (values 0,1,2)
- maximum heart rate achieved
- exercise induced angina
- oldpeak = ST depression induced by exercise relative to rest
- the slope of the peak exercise ST segment
- number of major vessels (0-3) colored by flourosopy
- thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

## Classifiers

- SVC
- Random Forest Classifier
- Gradient Boosting Classifier
