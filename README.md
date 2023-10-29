# Hacktoberfest--
Batch gradient descent is an optimization algorithm commonly used in machine learning and deep learning for training models. It's a form of gradient descent where the entire training dataset is used to compute the gradient of the cost function in each iteration. Here's a brief overview of batch gradient descent:

Initialization: Initialize model parameters (e.g., weights and biases) randomly.

Batch Selection: Divide the training dataset into mini-batches, each containing a fixed number of samples (batch size). The entire dataset is used in each iteration.

Gradient Calculation: Compute the gradient of the cost function with respect to the model parameters using the current mini-batch.

Parameter Update: Update the model parameters in the opposite direction of the gradient to minimize the cost function. The update is performed using a learning rate, which determines the step size.

Iterate: Repeat steps 3 and 4 for a predefined number of iterations (epochs) or until convergence.
