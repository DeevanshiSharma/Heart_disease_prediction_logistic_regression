# Heart-Disease-Prediction-using-ML | logistic-regression

CONTEXT:

- Day by day the cases of heart diseases are increasing at a rapid rate and it’s very Important and concerning to predict any such diseases beforehand.

DATASET:

https://drive.google.com/file/d/1sX9mdej4fhC_jGgMvBHsYa8lab2e17EP/view

METADATA:

- age: age in years

- sex: sex (1 = male; 0 = female)

- cp: chest pain type
-- Value 0: typical angina
-- Value 1: atypical angina
-- Value 2: non-anginal pain
-- Value 3: asymptomatic

- trestbps: resting blood pressure (in mm Hg on admission to the hospital)

- chol: serum cholestoral in mg/dl

- fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

- restecg: resting electrocardiographic results
-- Value 0: normal
-- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
-- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

- thalach: maximum heart rate achieved

- exang: exercise induced angina (1 = yes; 0 = no)

- oldpeak = ST depression induced by exercise relative to rest

- slope: the slope of the peak exercise ST segment
-- Value 0: upsloping
-- Value 1: flat
-- Value 2: downsloping

- ca: number of major vessels (0-3) colored by flourosopy

- thal: 0 = normal; 1 = fixed defect; 2 = reversable defect and the label

- target: 0 = no disease, 1 = disease

APPROACH:

I used this Dataset to train a Logistic regression model which can predict patients that are most likely to suffer from a heart disease in the near future using the features given.

PACKAGES USED:

Pandas, Numpy, and Scikit Learn.

