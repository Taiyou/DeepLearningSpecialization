# Regularizing your neural networks
*1.Regularization*

Regularization is to avoid overfiting to training datasets by regularting degree of freedom of weights.

*2. Dropout Regularization*


Intuition: by removing weights at random, we can avoid relying on sparse weights too much.

*3. Other regularization methods*
- Data Augumentation

Adding distortions to trainings data

- Early Stopping
Stopping iteration at earlier stage.

advantage: Computation is easier.
disadvantage: This process coumples minimizing a cost function and avoiding overfiting.

As replacement for this early stopping, you can use L2 regularization.
However, L2 reuglarization also requires additional calculations for <a href="https://www.codecogs.com/eqnedit.php?latex=\lambda" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\lambda" title="\lambda" /></a>
# Setting up your optimization problem
- normalizing input
- Vanishing / Exploding gradient problem
- Weight initialization for Deep Networks
