# wine-classification
Supervised and Unsupervised Models for wine dataset

The data set contains 178 wine chemical analysis samples belonging to 3 different classes. Each sample is described by 13 characteristics. The classes are distributed as follows: class_0 (59), class_1 (71), class_2 (48). No missing or null values were found.

In this work 2 datasets are used, one with the original data and one with the correctly scaled and/or normalized data. Both datasets have been divided into training and validation sets.

A value of K has been chosen and then applied to the KNN algorithm on both datasets. Accuracy has been evaluated afterwards.
A max_depth value has been chosen and  the Decision Trees algorithm on both datasets applied while evaluating its accuracy.

The data has been scaled and/or normalized, the problem dimension has been reduced to 2 using PCA and the resulting set has been plotted.
Without using the labels of the dataset, a value of K was selected and the KMeans algorithm was applied on the data transformed by PCA. The procedure was repeated using KMeans by mini-batches.
