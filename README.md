supervised learning

classification
decision trees - data is split based on binary decisions, one can eliminate the hypothesis space by limiting the number of leaves or maximum depth of the tree by setting the DecisionTreeClassifier values accordingly
k-nearest neighbors - to determine k-nearest neighbors, all data is always trained in memory (ad-hoc), so its only ever valuable in situations with limited data; when it comes to which distance measure to choose from (euklid vs. Hamming etc.) it is important to look at the unit of measure (centimeter vs. integers etc.)

regression
regression always predicts an aribitrary number
gradient descend - get closer to local minimums by MSE, loss graph must be smooth, derivative and convex to make sure only one local minimum exists
logistic regression - as opposed to its name, logistic regression is actually not predicting a number, but a categorical result (but its doing that using a regression operation and a transfer function - transfers number to categorical value)
support vector machines - used when data is linearily seperable, SVM have a line that has the widest mimimum margin between data points 

accuracy - correctly predicted vs all predictions
precision - number of true positives / all labelled as positive
recall - number of true positives / all actual positive instances
