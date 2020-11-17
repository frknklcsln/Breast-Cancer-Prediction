# Breast Cancer Prediction

# Abstract
Breast cancer is one of the most common cancers with a high mortality rate among women. Therefore, an accurate and reliable system is necessary for the early diagnosis of this cancer. This paper presents a comparison of four machine learning (ML) algorithms: Logistic Regression (LR), Nearest Neighbor Classifier (k-NN), Random Forest Classifier (RFC), Naïve Bayes (NB) on the Wisconsin Diagnostic Breast Cancer (WDBC) dataset by measuring their classification test and cross-validation accuracy. For the implementation of the ML algorithms, the dataset was split in the following fashion: 70% for training, and 30% for the testing. I use Sequential Feature Selector from mlxtend library for feature selection. I compared test and GridSearchCV scores for each model. Logistic Regression gives the best accuracy for this dataset with %96,58 score.
