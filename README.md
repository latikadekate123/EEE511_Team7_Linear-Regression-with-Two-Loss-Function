# Linear Regression with MSE vs. Huber Loss
This project is a practical analysis of linear regression, focusing on how to handle a dataset that contains outliers. We implemented the gradient descent algorithm from scratch to find the optimal model parameters (w and b) and compare different training approaches.

## Our main areas of focus were:

Loss Function Comparison: A deep dive into the performance of Mean Squared Error (MSE) versus the more robust Huber Loss.

Hyperparameter Analysis: We studied how different learning rates (α) (0.01, 0.1, and 0.5) and termination criteria impact the model's convergence speed and the final accuracy of the parameters w and b.

Outlier Robustness: The main aim was to determine which approach provides a more reliable fit.

## Conclusion
The primary conclusion from our experiments is that Huber Loss provides a significantly more accurate model for this dataset, as it is not biased by the outlier points.
