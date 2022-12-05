# Covid19-Prediction
 Project Description The data used in this project will help to identify whether a person is going to recover from coronavirus symptoms or not based on some pre-defined standard symptoms. These symptoms are based on guidelines given by the World Health Organization (WHO).
 
 This project will help to identify whether a person is going to recover from coronavirus symptoms or not based on some pre-defined standard symptoms
The problem: - COVID-19 Outcome Prediction
 
## The data 
the first step in our project is loading the dataset (“data.csv”) and
describing it. After that step we notice that the data set contain
many features
('country','location','age','gender','visited_Wuhan','From_Wuhan','a
ge','symptom1','symptom2','symptom3','symptom4') and class
label ('result'). The data set has 863 records and 14 features.
The problem in that data set: - the number of class (0) is 755 and
the number value of class (1) is 108 which mean the class label is
highly unbalanced it will result the splitting to be unfair for both
classes. We can solve it by weighting the model 
(increasing class 1) and splitting and stratifying the data evenly between both
labels. We Weighted the models (Weighted Logistic Regression -
Naive Bayes priors) in our project. The two models’ classes
provide the class weight argument that can be specified as a
model hyperparameter. The class weight is a dictionary that
defines each class label (0 and 1) and the weighting to apply in
the calculation of the negative log-likelihood when fitting the
model. 

