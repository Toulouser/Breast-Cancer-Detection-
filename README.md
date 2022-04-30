# Breast-Cancer-Detection-

The breast cancer detection problem is a binary classification problem. Classification is a family of supervised machine learning algorithms that categorizes data into classes. Our aim here is to classify whether the breast cancer is benign or malignant on previously unseen data. 

# Dataset:

The dataset, Breast Cancer Wisconsin (Diagnostic) Data Set, is publicly available at UCI Machine Learning website and was created by Dr. William H. Wolberg. The program uses a curve-fitting algorithm, to compute ten features from each one of the cells in the sample, then it calculates the mean value, extreme value and standard error of each feature for the image.

Dataset: https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)

## Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)

Ten real-valued features are computed for each cell nucleus:

i) radius 
ii) texture 
iii) perimeter
iv) area
v) smoothness 
vi) compactness
vii) concavity 
viii) concave points 
ix) symmetry
x) fractal dimension 

#Model:

We used pyspark, an interface for Apache Spark to use Python API. We used linear regression to pedict whether the cancer is malignant or not. The model utilizes a probabilistic model which is used to predict the label class. 
