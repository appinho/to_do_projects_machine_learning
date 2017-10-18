# To do projects Machine Learning
A to do list for all machine learning tasks that I wanna tackle in future

Machine Learning can be subdivided into three categories:
- Supervised learning (labeled training dataset to predict other instances)
- Reinforcement learning (some form of feedback for each predictive step)
- Unsupervides learning (discover implicit relationships in a given unlabeled dataset)

# 1 Decions Trees
Use a tree-like graph or model of decisions
Minimum number of yes/no questions to assess the probability of making a correct decision

# 2 Naive Bayes Classification
P(A|B) posterior probability = P(B|A) likelihood * P(A) prior probability / P(B) predictor prior probability  
Examples: Spam Classifier, Classify news articles, Face Recognition

# 3 Ordinary Least Squares Regression
Linear regression is the task to fit a line through a set of points
Linear because model has degree 1 and least squares because of error metric

# 4 Logistic regression
Model a binomial outcome using a logistic function
Examples: Credit Scoring, Success rate of marketing campaigns, Predict revenues

# 5 Support Vector Machines
Binary classification algorithm
Given: Set of points of 2 types in N dimensional space
SVM generates a N-1 dimensional hyperlane for separation
Examples: Human Splice Site Recognition, Image-based gender detection

# 6 Ensemble Methods
Construct a set of classifiers and then classify new data points by taking a weighted vote of their predictions
- average out biases
- reduce the variances (less diversification)
- unlikely to over-fit

# 7 Clustering Algorithms
Grouping a set of objects that are more similar to each other than others.
- Centroid-based (k-means, mean-shift)
- Connectivity-based
- Density-based (DBSCAN)
- Probabilistic
- Dimensional Reduction
- Neural networks/ Deep Learning

# 8 Principal Component Analysis
Statistical procedure that uses an orthogonal transformation to convert a set of observations of possibly correlated variables into a set of values of linearly uncorrelated variables called principal components
Examples: compression, simplifying data (not for noisy data)

# 9 Singular Value Decomposition
M = UEV where U and V are unitary matrices and E is diagonal
PCA is actually a simple application of SVD

# 10 Independent Component Analysis
Reveals hidden factors that underlie sets of random variables,measurements, or signals.
Defines a generative model for the observed multivariate data.
More powerful than PCA

# Source:
https://gab41.lab41.org/the-10-algorithms-machine-learning-engineers-need-to-know-f4bb63f5b2fa
