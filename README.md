# Housing-Classification
This project utilizes well established machine learning classifiers to determine the classification of houses (Expensive or not Expensive) based on their features.

The Classifiers utilized for this project are;
1. Decision Tree Classifier.
2. RandomForest Classifier.
3. ExtraTrees Classifier.
4. KNeighbours Classifier.
5. SupportVector Classifier.
6. SGD Classifier.

Data Preprocessing was done by visualizations, cleaning, imputting missing values, and scaling in some cases, to minimize outlier effects. 

Categorical encoding of type Onehot and Ordinal was also used. 

Different pipelines were created to handle categorical and numerical features, and finally, the grid search cross validation iterator was used to ensure our model predicts without overfitting. 

The results from these classifiers are as given in the table below.

![image](https://user-images.githubusercontent.com/103940202/201202581-c7975a3b-ae7d-46ca-b67d-07e0f0293301.png)
