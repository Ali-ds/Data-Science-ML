Predicting heart disease using machine learning

This notebook looks into various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes


## 1. Problem Definition

In a statement,
> Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## 2. Data

The original data came from Cleveland data from UCI Machine Learning Repository.

There is also a version of it available on Kaggle. 

https://www.kaggle.com/ronitf/heart-disease-uci

## 3. Evaluation

> If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.

## 4. Features 

This is where you'll get different information about each of the features in your data.

**Data dictionary**
* age = age in years
* sex = (1 = male; 0 = female)
* cp = chest pain type
* trestbps = resting blood pressure (in mm Hg on admission to the hospital)
* chol = serum cholestoral in mg/dl
* fbs = (fasting blood sugar &gt; 120 mg/dl) (1 = true; 0 = false)
* restecg = resting electrocardiographic results
* thalach = maximum heart rate achieved
* exang = exercise induced angina (1 = yes; 0 = no)
* oldpeak = ST depression induced by exercise relative to rest
* slope = the slope of the peak exercise ST segment
* ca = number of major vessels (0-3) colored by fluoroscopy
* thal= 3 = normal; 6 = fixed defect; 7 = reversible defect
* target = 1 or 0
