# Stochastic Gradient Descent implementation from scratch
## What is Gradient Descent?

> Gradient descent or batch gradient descent is an iterative algorithm that starts from a random point on a function and travels down its slope until it reaches the lowest point of the function. A gradient descent iterates on all N points in the training data set before making any update to weights. Cost function in gradient descent is mean squared error. 

## What is stochastic Gradient Descent?
> In stochastic gradient descent weights are updated for each single data point in the training dataset so that the new function fits that data point little better. SGD updates the weights based on each data point in the training set and hence converges quickly compared to gradient descent. Cost function for stochastic gradient descent is squared error for the ith point. 
-- Weights are updated in the opposite direction of the gradient wrt θ
-- Entire algorithm is repeated multiple times on the training dataset, each single pass through the training set is counted as one epoch
-- η is called the learning rate and it decides (along with the gradient value) the magnitude of the step size

## Gradient Descent with Momentum
> Gradient descent with momentum is all about calculating exponentially weighted average of the gradient and using that weighted averaged gradient to update weights since then. Momentum method helps the accelerate the gradient descent in one direction (direction of the minimum) and dampens the oscillation. Typical value of  γ=0.9 is used in momentum which is analogous to taking weighted average of last 10 gradient descents

## Gradient Descent with Adagrad
> Adagrad adapts the learning rate to the parameters, performing smaller updates (i.e. low learning rates) for parameters associated with frequently occurring features, and larger updates (i.e. high learning rates) for parameters associated with infrequent features -- It is well-suited for dealing with sparse data and doesn’t require manual tune the learning rate.




