Masters : AI Project on Heart Disease Prediction

## Problem:
To predict target variable (‘cardio’) for a given  patient record.
Feature Selection is a problem if there are more no. of attributes in the dataset.

## Significance:
By Exploring Data, we can rule out irrelevant features by plotting  and analyzing them.
With the help of heatmap, we can find the features that influences the presence of heart disease.

## Dataset used :
Cardiovascular Disease Dataset is obtained from Kaggle. https://www.kaggle.com/sulianova/cardiovascular-disease-dataset
with 13 attributes over 70,000 records of patients. Here 'Cardio' is the target variable



Below Models are applied on the dataset :
1.K-Nearest Neighbors (KNN).
2.Support Vector Machine (SVM).
3.Naive Bayes. 
4.Deep Forest (Cascade Forest).

Sci-kit learn is used for building KNN,SVM and Naive Bayes models.

## Deep Forest 

Deep Forest model is proposed by Zhi-Hua Zhou and Ji Feng 

Official Github Link : https://github.com/kingfengji/gcForest 

Conference paper : https://www.ijcai.org/Proceedings/2017/0497.pdf


Deep forest comprise of many layers of cascade structure where output from each layer of the cascade is the feature input for the upcoming layer.
Each level of the cascade forest includes two random forests (RF) and two complete-random tree forests.
Each cascade comprise of an ensemble of Random Forest, i.e. it is an ensemble of ensembles.

Deep Forest has 2 parts :
1) Multi -Grained Scanning  and 
2) Cascaded Forest

For my project, I have implement Deep Forest model with only Cascaded Forest part.







