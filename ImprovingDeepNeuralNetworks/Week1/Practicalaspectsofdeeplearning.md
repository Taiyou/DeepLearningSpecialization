# 1. If you have 10,000,000 examples, how would you split the train/dev/test set?
-1. 33% train . 33% dev . 33% test
-2. 60% train . 20% dev . 20% test
-3. 98% train . 1% dev . 1% test

Answer: 3. 98% train . 1% dev . 1% test.

In deep learning framework, it is important to have many training datasets.

# 2. The dev and test set should:
- 1. Come from the same distribution
- 2. Come from different distributions
- 3. Be identical to each other (same (x,y) pairs)
- 4. Have the same number of examples

Answer: 1.

Data structure should be same.

# 3. If your Neural Network model seems to have high bias, what of the following would be promising things to try? (Check all that apply.)
- 1. Get more training data
- 2. Get more test data
- 3. Add regularization
- 4. Make the Neural Network deeper
- 5. Increase the number of units in each hidden layer

Answer: 4, 5.

Bias means the difference between expectation and predictions.
Choose neural networks which increase model complexity.

# 4. You are working on an automated check-out kiosk for a supermarket, and are building a classifier for apples, bananas and oranges. Suppose your classifier obtains a training set error of 0.5%, and a dev set error of 7%. Which of the following are promising things to try to improve your classifier? (Check all that apply.)
- 1. Increase the regularization parameter lambda
- 2. Decrease the regularization parameter lambda
- 3. Get more training data
- 4. Use a bigger neural network

Answer: 1,3

The model seems to be stacked into overfitting. Therefore, we need to add the stronger regularizer and more data.

# 5. What is weight decay?
- 1. The process of gradually decreasing the learning rate during training.
- 2. A technique to avoid vanishing gradient by imposing a ceiling on the values of the weights.
- 3. Gradual corruption of the weights in the neural network if it is trained on noisy data.
- 4. A regularization technique (such as L2 regularization) that results in gradient descent shrinking the weights on every iteration.

Answer: 4.

# 6. What happens when you increase the regularization hyperparameter lambda?
- 1. Weights are pushed toward becoming smaller (closer to 0)
- 2. Weights are pushed toward becoming bigger (further from 0)
- 3. Doubling lambda should roughly result in doubling the weights
- 4. Gradient descent taking bigger steps with each iteration (proportional to lambda)

Answer: 1

# 7. With the inverted dropout technique, at test time:
- 1. You apply dropout (randomly eliminating units) and do not keep the 1/keep_prob factor in the calculations used in training
- 2. You do not apply dropout (do not randomly eliminate units), but keep the 1/keep_prob factor in the calculations used in training.
- 3. You do not apply dropout (do not randomly eliminate units) and do not keep the 1/keep_prob factor in the calculations used in training
- 4. You apply dropout (randomly eliminating units) but keep the 1/keep_prob factor in the calculations used in training.

Answer: 3.

You dont have to randomly remove units in the test sets as well as keep the factor.

# 8. Increasing the parameter keep_prob from (say) 0.5 to 0.6 will likely cause the following: (Check the two that apply)
- 1. Increasing the regularization effect
- 2. Reducing the regularization effect
- 3. Causing the neural network to end up with a higher training set error
- 4. Causing the neural network to end up with a lower training set error

Answer: 2, 4.

Increasing keep_prob means increasing fitting power to training datasets (reduction of the regularization effect as well as higher accuracy in training datasets)

# 9. Which of these techniques are useful for reducing variance (reducing overfitting)? (Check all that apply.)
- 1. Gradient Checking
- 2. Vanishing gradient
- 3. Dropout
- 4. Xavier initialization
- 5. Data augmentation
- 6. Exploding gradient
- 7. L2 regularization

Answer: 3, 5, 7.

# 10. Why do we normalize the inputs x?
- 1. It makes the cost function faster to optimize
- 2. It makes it easier to visualize the data
- 3. It makes the parameter initialization faster
- 4. Normalization is another word for regularization--It helps to reduce variance

Answer: 1.

After normalizing the inputs, input space is not skewed.

