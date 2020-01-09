# Theory and Applications of Data Mining Final Project - George Mason University, Computer Science Department

**Title**: Classifying genetic mutations based on their role in contributing to tumor growth

**Summary**: In this project, I develop a machine learning model to classify a set of genetic mutations based on their role in contributing to tumor growth. Using an annotated training dataset in which researchers and oncologists have manually annotated mutations and classified them among one of nine classes, I develop a model that automatically classifies genetic mutations in a subset of the dataset reserved for testing. First, I read in the data and perform feature selection as well as dimensionality reduction using Singular Value Decomposition - SVD. Next, I evaluate three classification models (K-nearest neighbors - KNN, Support Vector Classification - SVC, and a pruned Decision Tree classifier) using the unbalanced dataset. Then, I use the model that produced the highest F-1 score, SVC (F-1 = 0.597), to evaluate three methods of balancing the data: undersampling, oversampling, and a hybrid technique called SMOTE. Finally, I use the method of balancing data that produced the highest F-1 score, SMOTE (F-1 = 0.597), to reevaluate the three classification models. The model that produces the highest F-1 score in this case, SVC (F-1 = 0.615), is the best model. In the future, the model can be improved by using other classification methods such as deep learning as well as combining multiple classifiers via ensemble methods such as bagging and/or boosting.

**Data**: All data used for this project is provided by the Memorial Sloan Kettering Cancer Center (MSKCC) and was obtained from the Kaggle website: https://www.kaggle.com/c/msk-redefining-cancer-treatment.

**Code**: All code used to analyze the data is located in the mutationclassification.ipynb file.
