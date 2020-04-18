# Breast Cancer Classifier

We build different Machine Learning-based models by using data available on 
[**Kaggle (Breast Cancer Wisconsin Diagnostic dataset)**](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data). 

Here, we hypothesize that Machine Learning algorithms can predict the nature of a breast tumour (benign or malignant) in order 
to provide health sector with assistance to breast tumour classification. 
Same methodology could be applied to other similar kind of cancer detection.

The algorithms tested in this project are:
- Support Vector Machine (SVM)
- Multilayer Perceptron (MLP)
- K Nearest Neighbour (KNN)
- Decision Tree (DT)
- Logistic Regression (LR)

Model evaluation is determined by:
- Mean accuracy on cross validation
- Accuracy on test data
- Jaccard index
- F1-score

Some features selection methods have been used in order to find the less relevant features.

You can run the notebook and play with the code here: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ealmenzar/BreastCancerClassifier/master?urlpath=https%3A%2F%2Fgithub.com%2Fealmenzar%2FBreastCancerClassifier%2FBreastCancerClassifier.ipynb)
