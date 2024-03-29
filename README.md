# AML_2019_Group17
## 1. Why is gradient descent important in machine learning?
Gradient descent, also known as steepest descent, is an optimization algorithm for finding the local minimum of a function. To find a local minimum, the function "steps" in the direction of the negative of the gradient.Most models of machine learning need to find a area or a point to make sum of residuals reduced to a minimum value that models could fit data in a efficient way and show great performance. Gradient descent is one of a powerful algorithm to find the piont and sum of residuals reach to the minimum. 
<br /><br />
## 2. How does plain vanilla gradient descent work?
The cost function calculates the sum of residuals, the coefficients of will be updated with the changing sum of residuals. While the algorithm runs many times, the coefficients would be convergence in a stable value or area. This combine of coefficients is the target of status that the model fits data efficiently and we could use this model to prediction.
<br /><br />
## 3. Two modiﬁcations to plain vanilla gradient descent
The first method is Stochastic gradient descent,‘stochastic‘ means a system or a process that is linked with a random probability. Hence, in Stochastic Gradient Descent, a few samples are selected randomly instead of the whole data set for each iteration. In Gradient Descent, there is a term called “batch” which denotes the total number of samples from a dataset that is used for calculating the gradient for each iteration. Although, using the whole dataset is really useful for getting to the minima in a less noisy or less random manner, but the problem arises when our datasets get really huge. This problem is solved by Stochastic Sradient Descent. In SGD, it uses only a single sample, i.e., a batch size of one, to perform each iteration. The sample is randomly shuffled and selected for performing the iteration. Here, we compare the two different learning rate 0.05 and 0.005. The second method is Momentum method is a technique can be used to mitigate these problems, which can accelerate gradient descent by taking accounts of previous gradients in the update rule at each iteration
<br /><br />
## 4. Experiment
### 4.1 Example
<p align="left">
  <img width="400" height="300" src="https://github.com/acyz737/AML_2019_Group17/blob/master/Images/Figure%201.png"/400/300>
  <img width="400" height="300" src="https://github.com/acyz737/AML_2019_Group17/blob/master/Images/Figure%202.png"/400/300>
</p>

### 4.2 Learninng rate = 0.05
<p align="left">
  <img width="400" height="300" src="https://github.com/acyz737/AML_2019_Group17/blob/master/Images/figure%203.png"/400/300>
  <img width="400" height="300" src="https://github.com/acyz737/AML_2019_Group17/blob/master/Images/Figure%204.png"/400/300>
</p>
From the 3D figure, it is clear that the location where the color is darkest, we could find the best coefficients and the sum of square is the smallest value.
### 4.3 Learning rate = 0.005
<p align="left">
  <img width="400" height="300" src="https://github.com/acyz737/AML_2019_Group17/blob/master/Images/Figure%205.png"/400/300>
  <img width="400" height="300" src="https://github.com/acyz737/AML_2019_Group17/blob/master/Images/Figure%206.png"/400/300>
</p>
Comparing learning rate = 0.05 and learning rate = 0.005, these have different ways to reach the point that makes sum of square to be smallest. While the learning rate is 0.05, we could know that the times of loop is smaller than learning rate is 0.005. And the sum of square is different, the learning rate = 0.05 would be better.

