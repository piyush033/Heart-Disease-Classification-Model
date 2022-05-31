# Heart-Disease-Classification-Model

## Problem Statement 

Given clinical parameters about a patient, can we predict whether or not they have heart disease?
Yes we can ! This model uses a set of clinical data about a patient to predict whether or not they have cardiac disease.
Main Code : https://github.com/piyush033/Heart-Disease-Classification-Model/blob/main/Heart_Disease_Project.ipynb

## Table of Content

* [Problem Statement](https://github.com/piyush033/Heart-Disease-Classification-Model/blob/main/README.md#problem-statement)
* [Datasets Used](https://github.com/piyush033/Heart-Disease-Classification-Model/blob/main/README.md#datasets-used)
* [Frameworks Used](https://github.com/piyush033/Heart-Disease-Classification-Model/blob/main/README.md#frameworks-used)
* [Heart Disease Data Dictionary](https://github.com/piyush033/Heart-Disease-Classification-Model/blob/main/README.md#heart-disease-data-dictionary)
* [Model Visualizations](https://github.com/piyush033/Heart-Disease-Classification-Model/blob/main/README.md#model-visualizations)

## Datasets Used 

The original data came from the Cleveland data from UCI Machine Learning Repository.
https://archive.ics.uci.edu/ml/datasets/heart+disease

There is also a version of it available on Kaggle: 
https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

## Frameworks used

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

## Heart Disease Data Dictionary

A data dictionary describes the data you're dealing with. Not all datasets come with them so this is where you may have to do your research or ask a **subject matter expert** (someone who knows about the data) for more.
The following are the features we'll use to predict our target variable (heart disease or no heart disease).
* age - age in years
* sex - (1 = male; 0 = female)
* cp - chest pain type
0: Typical angina: chest pain related decrease blood supply to the heart
1: Atypical angina: chest pain not related to heart
2: Non-anginal pain: typically esophageal spasms (non heart related)
3: Asymptomatic: chest pain not showing signs of disease
* trestbps - resting blood pressure (in mm Hg on admission to the hospital)
anything above 130-140 is typically cause for concern
* chol - serum cholesterol in mg/dl
* serum = LDL + HDL + .2 * triglycerides
above 200 is cause for concern
* fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
'>126' mg/dL signals diabetes
* restecg - resting electrocardiographic results
0: Nothing to note
1: ST-T Wave abnormality
can range from mild symptoms to severe problems
signals non-normal heart beat
2: Possible or definite left ventricular hypertrophy
Enlarged heart's main pumping chamber
* thalach - maximum heart rate achieved
* exang - exercise induced angina (1 = yes; 0 = no)
* oldpeak - ST depression induced by exercise relative to rest
looks at stress of heart during exercise
unhealthy heart will stress more
* slope - the slope of the peak exercise ST segment
0: Upsloping: better heart rate with exercise (uncommon)
1: Flat Sloping: minimal change (typical healthy heart)
2: Downsloping: signs of unhealthy heart
* ca - number of major vessels (0-3) colored by fluoroscopy
colored vessel means the doctor can see the blood passing through
the more blood movement the better (no clots)
* thal - thallium stress result
1,3: normal
6: fixed defect: used to be defect but ok now
7: reversible defect: no proper blood movement when exercising
* target - have disease or not (1=yes, 0=no) (= the predicted attribute)
 
 
 
## MODEL VISUALIZATIONS 
Data :





Comparison between cp(Chest Pain) and Target :


























