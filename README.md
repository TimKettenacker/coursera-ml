supervised learning

classification
decision trees - one can eliminate the hypothesis space by limiting the number of leaves or maximum depth of the tree by setting the DecisionTreeClassifier values accordingly
k-nearest neighbors - to determine k-nearest neighbors, all data is always trained in memory (ad-hoc), so its only ever valuable in situations with limited data; when it comes to which distance measure to choose from (euklid vs. Hamming etc.) it is important to look at the unit of measure (centimeter vs. integers etc.)

regression
regression always predicts an aribitrary number
gradient descend - get closer to local minimums by MSE, loss graph must be smooth, derivative and convex to make sure only one local minimum exists
