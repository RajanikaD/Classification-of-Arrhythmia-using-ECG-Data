# Classification-of-Arrhythmia-using-ECG-Data
CS-584 Machine Learning Project
Submitted by: Rajanika Debnath, Vaishnavi Kadam, Nirbhay Rajgor

Developed accurate and efficient machine learning algorithms for automated arrhythmia detection and classification.   The goal is to predict if a person is suffering from arrhythmia or not, and if yes, classify it in to one of the available groups.

# Dataset
The Dataset used in this project is available on the UCI machine learning Repository.

It can be found at: https://archive.ics.uci.edu/ml/datasets/Arrhythmia.
It consists of 452 different examples spread over 16 classes. Of the 452 examples,

245 are of "normal" people. We also have 12 different types of arrhythmias.

Among all these types of arrhythmias, the most representative are the "coronary artery disease" and "Rjgbt boundle branch block".

We have 279 features, which include age, sex, weight, height of patients and other related information. We explicitly observe that the number of features is relatively high compared to the number of examples we are available.

#Evaluation strategy
As the dependent variable is a categorical variable we will be using classification models. The best way to do this is by comparing the precision and recall. 
They are crucial evaluation metrics due to the unacceptable consequences of misclassifying an individual having Cardiac Arrhythmia as healthy person. We will prioritize identifying sick individuals over identifying healthy individuals.

