# Cardiovascular-Risk-Prediction

## Problem Statement & Objectives

Heart disease is the major cause of morbidity and mortality globally: it accounts for more deaths annually than any other cause. According to the WHO, an estimated 17.9 million people died from heart disease in 2016, representing 31% of all global deaths. Over three quarters of these deaths took place in low- and middle-income countries.

Of all heart diseases, coronary heart disease (aka heart attack) is by far the most common and the most fatal. In the United States, for example, it is estimated that someone has a heart attack every 40 seconds and about 805,000 Americans have a heart attack every year (CDC 2019).

Doctors and scientists alike have turned to machine learning (ML) techniques to develop screening tools and this is because of their superiority in pattern recognition and classification as compared to other traditional statistical approaches.

In this project, We will be giving you a walk through on the development of a screening tool for predicting whether a patient has a 10-year risk of developing coronary heart disease(CHD) using different Machine Learning techniques.

## Data Description

### Demographic:
Sex: male or female("M" or "F")

Age: Age of the patient;(Continuous - Although therecorded ages have been truncated towhole numbers, the concept of age is continuous)

### Behavioral-
is_smoking: whether or not the patient is a currentsmoker ("YES" or "NO")

Cigs Per Day: the number of cigarettes that theperson smoked on average in one day.(can beconsidered continuous as one can have any number ofcigarettes, even half a cigarette.)
### Medical( history)
BP Meds: whether or not the patient was on bloodpressure medication (Nominal)

Prevalent Stroke: whether or not the patient hadpreviously had a stroke (Nominal)

Prevalent Hyp: whether or not the patient was hypertensive(Nominal)

Diabetes: whether or not the patient had diabetes(Nominal)Medical(current)

Tot Chol: total cholesterol level (Continuous)

Sys BP: systolic blood pressure (Continuous)

Dia BP: diastolic blood pressure (Continuous)

BMI: Body Mass Index (Continuous)

Heart Rate: heart rate (Continuous - In medicalresearch, variables such as heart rate though infact discrete, yet are considered continuous becauseof large number of possible values.)

Glucose: glucose level (Continuous)Predict variable (desired target)

10-year risk of coronary heart disease CHD(binary:“1”, means “Yes”, “0” means “No”) -DV

## Project Workflow

1. Splitting to Train and Test sets to avoid Data bleeding.

2. Simultaneously Data Cleaning of Train and Test sets

3. EDA on features

4. Feature cleaning and engineering

5. Solving Class Imbalanced problem

6. Base Model and Candidate Models

7. Hypertuning of parameters

8. Final Predictions

## Evaluation-metric

The most important evaluation metric that we go with, to address this problem statement, is the recall. Since we want to decrease the number of false negatives and predict all the true cases for 10-year risk of having CHD correctly, the focus of our ML models is to improve the recall.


## Conclusion

We have used Logistic Regression, KNN, SVC and XGBoost for modelling. Based on our observations, the Support vector classifier seems to have performed better with a recall of 74%. Based on the recall metrics, the model performance is really good, which was our objective from the very beginning i.e. we wanted to correctly predict all the positive cases of high risk CHD. 

