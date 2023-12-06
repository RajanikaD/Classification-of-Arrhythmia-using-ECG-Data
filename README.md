# Classification of Arrhythmia using ECG Data
CS-584 Machine Learning Project

Submitted by: 
Rajanika Debnath- A20543193
Vaishnavi Kadam- A20546870
Nirbhay Rajgor- A20539617

Developed accurate and efficient machine learning algorithms for automated arrhythmia detection and classification.   The goal is to predict if a person is suffering from arrhythmia or not, and if yes, classify it in to one of the available groups.

# Dataset
This study utilizes a dataset from the UCI Machine Learning Repository, available at https://archive.ics.uci.edu/ml/datasets/Arrhythmia. The dataset comprises 452 instances distributed across 16 classes, with 245 instances representing normal cases and the remaining representing 12 distinct arrhythmia types. The most prevalent arrhythmias include coronary artery disease and Rjgbt bundle branch block. The dataset contains 279 features, encompassing patient demographics such as age, sex, weight, and height. Notably, the feature count exceeds the instance count.

# Evaluation Strategy
As the dependent variable is a categorical variable we will be using classification models. The best way to do this is by comparing the precision and recall. 
They are crucial evaluation metrics due to the unacceptable consequences of misclassifying an individual having Cardiac Arrhythmia as healthy person. We will prioritize identifying sick individuals over identifying healthy individuals.

# Algorithm Used

1. Algorithms Used
2. KNN Classifier
3. Logistic Regression
4. Decision Tree Classifier
5. Linear SVC
6. Kernelized SVC
7. Random Forest Classifier
8. Principal Component analysis (PCA)

# Conclusion
Applying PCA to the resampled data enhanced the performance of the models. This improvement stems from PCA's ability to reduce data complexity, prioritize variables with high variance, and generate non-collinear components, effectively addressing collinearity in large datasets. PCA also expedites model execution time and enhances model quality, proving particularly beneficial when dealing with a vast number of variables.

The Best model in term of recall score is Kernalized SVM with PCA having accuracy of 80.21%.
