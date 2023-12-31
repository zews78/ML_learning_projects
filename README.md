# ML_learning_projects
This repo contains all the ML projects that i created during my learning process.

Here are the ML algorithms that i worked on:
1. Regression Models( Linear Regresssion, Logistic Regression)
2. Clustering(k-means)
3. K Nearest Neighbour(KNN)
4. Support Vector Machine(SVM)
5. Decision Tree
6. Random Forest
7. Native Bayes

Worked on various datasets from [Kaggle](https://www.kaggle.com/datasets)
eg: Titanic Survival, Iris flower species, etc.

Also, created some own dataset to run unsupervised models like K-means clustering.
Eg:



### K-means clustering:
![image](https://github.com/zews78/ML_learning_projects/assets/56071706/78d03f08-20b2-46ed-8a6c-d80ae9f71aa8)

Clustering is one of the most common exploratory data analysis technique used to get an intuition about the structure of the data.

It assigns data points to a cluster such that the sum of the squared distance between the data points and the cluster’s centroid (arithmetic mean of all the data points that belong to that cluster) is at the minimum.

The way kmeans algorithm works is as follows:
* Specify number of clusters K.
* Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.
* Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.
* Compute the sum of the squared distance between data points and all centroids.
* Assign each data point to the closest cluster (centroid).
* Compute the centroids for the clusters by taking the average of the all data points that belong to each cluster.

![image](https://github.com/zews78/ML_learning_projects/assets/56071706/f637749f-b5e1-46c0-9c2b-4e0ed5af7d5d)






-------
accuracy, precision, recall, f1-score, confusion matrix



-------

After learning all the different types of Model with diffrent hyperparameters. It becomes more difficult to choose the model and with specific hyperparameter.
Here comes the end of this session with hyperparameter tuning.
Where you iterate all possible models with there different possible hyperparameters check their model parameters like: accuracy, f1-score, etc. 
And after tabular comparision you choose the best model.

Below is the example shows printed tabular output to compare the models with their accuracy and best hyperparameters.

| model               | best_score | best_params                   |
|---------------------|------------|-------------------------------|
| svm                 | 0.968842   | {'C': 0.1, 'kernel': 'poly'}   |
| random_forest       | 0.935477   | {'n_estimators': 40}          |
| logistic_regression | 0.922114   | {'C': 1}                      |
| NB_gaussian         | 0.806928   | {}                            |
| NB_multinomial      | 0.870350   | {}                            |
| decision_tree       | 0.801927   | {'criterion': 'entropy'}      |
| knn                 | 0.966622   | {'n_neighbors': 3}            |





