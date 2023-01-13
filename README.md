# diabetes

remarks:

- Last few cells need a strong cpu to run.
- plot dendogram function was taken from your github repo.
- for the histplot of each feature that looks at the clusters and wheter or not a person has diabetes I didn't label #counts on each y-axis because it looked bad
- silhouette coefficient idea was taken from here: https://towardsdatascience.com/evaluating-goodness-of-clustering-for-unsupervised-learning-case-ccebcfd1d4f1
while code block was on the yellowbrick api


Due to the abundance of features, I deleted all that had a correlation of 1 with each one since they won't improve the model. This is my main concern wheter or not this is actually okay to do. Furthermore all missing values got dropped immediatly, It's a shame that the Liver inflammation Factor was mostly nan because because it could have also a signigicant contribution in a classifier as we can see in the correlation matrix.



