# Comparing Machine Learning Models for Diabetes Prediction

Allen Chang

29 March 2024

# Note

A more detailed report can be found under the QBIO 401 Final Report.

## Abstract

In this study, I aim to identify the best model for diabetes prediction. Here, I will be comparing a simple logistic regression, a neural network, and a decision tree classifier. The features I will consider are age, hypertension, heart disease, body mass index, HbA1c level, and blood glucose level. 

 
## Introduction

Diabetes is a disease that is characterized by a constant state of hyperglycemia resulting in issues related to both insulin secretion and action (Kharroubi and Darwish). In fact, 0.5% of US adults are diagnosed with type 1 diabetes while 8.5% of US adults are diagnosed with type 2 diabetes (Xu et. al.). In fact, globally, about 45.8% of diabetes cases are estimated to be undiagnosed (J. Beagley et. al.). Thus, there is a need for an accurate and efficient method to diagnose diabetes. 
 
## Methodology

Here, I will create three different models: logistic regression, neural network, and decision tree classifier. Using the publicly available dataset, I will train the three models and compare their results through various performance measures including accuracy, F1 score, precision, and recall. The dataset is available at: https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset/discussion

## Expected Results
	
I expect the models to perform better than a baseline random guess model, meaning that the AUROC score should be greater than 0.5. A well-performing model can be further improved upon for future clinical applications. Furthermore, this will aid doctors in diagnosing diabetes as well as helping individuals who may not have easily accessible healthcare advice. 
Potential limitations may include a lack of features and a relatively small sample size. Furthermore, there may be better model architectures or hyperparameters that can be used to improve the model. 

## References

Kharroubi AT, Darwish HM. Diabetes mellitus: The epidemic of the century. World J Diabetes. 2015 Jun 25;6(6):850-67.
Xu G, Liu B, Sun Y, Du Y, Snetselaar LG, Hu FB, Bao W. Prevalence of diagnosed type 1 and type 2 diabetes among US adults in 2016 and 2017: population based study.
J. Beagley, L. Guariguata, C. Weil, and A. A. Motala, “Global estimates of undiagnosed diabetes in adults,” Diabetes Res. Clin. Pract., vol. 103, no. 2, pp. 150–160, Feb. 2014, doi: 10.1016/j.diabres.2013.11.001.

