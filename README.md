# Perceptron-algorithm-for-finding-the-weights-of-a-Linear-Discriminant-function
The Perceptron algorithm is a simple and classic algorithm used for binary classification. It finds the weights of a linear discriminant function that can separate two classes of data points. The algorithm iteratively adjusts the weights based on misclassified points until all points are correctly classified or a maximum number of iterations is reached.

To accomplish the tasks you've described, we need to follow these steps:

Read and Plot Data:

1. Load data from "train.txt".
2. Plot samples with different colors and markers for each class.
Generate High Dimensional Points:

1. Apply the formula to generate high dimensional points using a second-order polynomial discriminant function.
2. Normalize one class to ensure that the dimensions are consistent. y=[ x1^2 x2^2 x1*x2 x1 x2 1 ]
   
Implement Perceptron Algorithm:

1. Implement the Perceptron algorithm for both one-at-a-time and batch learning.
2. Loop through different initial weights and learning rates.
3. Count the number of iterations until convergence.
   
Create Table and Bar Chart:

1. Record the learning rate, number of iterations, and other parameters for each case.
2. Create a table displaying this information.
3. Generate a bar chart visualizing the data in the table.
