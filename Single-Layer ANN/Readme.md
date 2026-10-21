# Single-Layer Artificial Neural Network (ANN)

This project implements a single-layer Artificial Neural Network using NumPy to classify input data into two classes using sigmoid activation and gradient descent.

## Concepts Used

- **Artificial Neural Network (ANN):** A computational model that learns patterns from input data.
- **Sigmoid Activation Function:** Converts the model's output into a probability between 0 and 1.
- **Forward Propagation:** Calculates predictions using input features, weights, and bias.
- **Gradient Descent:** Updates weights and bias to reduce prediction error.
- **Binary Classification:** Assigns each input to class 0 or class 1.

## Dataset

- **Source:** Manually created sample dataset using NumPy.
- **Features:** Two numerical input features.
- **Target:** Binary labels (0 and 1).
- **Download:** No external dataset is required.

## Implementation Steps

- Create the input data and target labels.
- Initialize weights and bias.
- Train the model using forward propagation and gradient descent.
- Predict classes using a probability threshold of 0.5.
- Calculate classification accuracy.
- Visualize the input data and predict the class of a new sample.

## Tools and Libraries

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Output

The program displays the learned weights and bias, actual and predicted classes, training accuracy, a scatter plot of the dataset, and the predicted class for a new input.
