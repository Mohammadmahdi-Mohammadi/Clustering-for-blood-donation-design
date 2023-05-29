# Clustering-for-blood-donation-design
In this problem, we want you to cluster the blood tests to define whether its owner can be a blood donor:

a) Load the dataset and apply the needed preprocessing steps. (Categorical to numerical and normalization). why is normalization in distance-based clustering algorithms necessary? Justify your answer with examples.

b) Implement the K-Means function with the below template:
KMeans(X_train, ClusterCount=2, iteration=30, ConergenceRatio=0.01, DistanceMetric=[Euclidean or CityBlock]) -> centers: list

c) Use the implemented function to detect outliers in the dataset and indicate what percent of the dataset is recognized as an outlier; Explain the steps you have done. (Note that the target column is "Category" and should be removed in the feature vector)

d) Split it to train and test sets with the ratio of 8:2.

e) Train the K-Means clustering algorithm for two centers (target to evaluate [0-0s] or [1-3]) and test it with obtained centers and test sets. Report the results for Purity, Entropy, and accuracy metrics as well as obtained centers. (Note that labels of obtained and original may be different only numerically; for example, the original label of 0,1 is assigned to 1,0 respectively, and there may be no difference in members) You are not allowed to use functions or libraries to calculate metrics.

f) Repeat the previous part for four clusters (target to evaluate: [0-0s], [1], [2], or [3]).
