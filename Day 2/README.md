# Linear Regression from Scratch - Day 2

## Overview
This Jupyter Notebook demonstrates how to implement a Linear Regression model from scratch using Gradient Descent. It is a practical exercise aimed at deepening the understanding of fundamental machine learning algorithms by building them without relying on external libraries. Through this process, you will gain insights into how linear regression works, beyond simply using pre-built functions from libraries like scikit-learn.

## Objectives
- Understand the working principles of Linear Regression, including its mathematical foundation.
- Implement the Mean Squared Error (MSE) loss function to quantify prediction errors.
- Develop a Gradient Descent optimizer to iteratively improve the model.
- Train and evaluate the Linear Regression model on sample data to observe its effectiveness.
- Visualize the optimization process and the resulting regression line.

## Key Topics Covered
1. **Loss Function**
   - Implementation of the Mean Squared Error (MSE) function to measure the model's prediction error.
   - Understanding why minimizing the MSE helps achieve the best fit for the data.

2. **Gradient Descent**
   - Step-by-step implementation of the gradient descent optimization algorithm.
   - Explanation of how gradients are calculated and used to update model parameters (weights and biases).
   - Discussion of hyperparameters such as learning rate and number of iterations (epochs).

3. **Model Training**
   - Training the Linear Regression model using a synthetic or real-world dataset.
   - Iteratively updating weights to minimize the loss function and achieve better predictions.
   - Understanding the convergence of the gradient descent algorithm.

4. **Evaluation**
   - Visualizing the regression line to assess the quality of fit.
   - Plotting the loss function over iterations to observe optimization progress.
   - Interpreting key metrics for model performance.

## Prerequisites
- Basic knowledge of Python and NumPy.
- Familiarity with Linear Regression concepts such as cost functions and optimization techniques.
- An understanding of high-school-level algebra and calculus concepts like derivatives.

## Getting Started
1. Clone this repository or download the notebook file.
2. Open the `ML_101_Day_2.ipynb` file in Jupyter Notebook or Google Colab.
3. Ensure the required libraries are installed:
   ```bash
   !pip install numpy matplotlib
   ```
4. Execute the cells sequentially to understand and implement the Linear Regression algorithm.

## How to Use This Notebook
- Follow the detailed explanations and code provided in each section to build the Linear Regression model step-by-step.
- Experiment with different learning rates, dataset sizes, or initial weight values to observe how they affect the convergence and accuracy of the model.
- Use this implementation as a foundation for understanding more advanced machine learning concepts and algorithms.

## Resources
- [NumPy Documentation](https://numpy.org/doc/)
- [Linear Regression - Wikipedia](https://en.wikipedia.org/wiki/Linear_regression)
- [Gradient Descent - Wikipedia](https://en.wikipedia.org/wiki/Gradient_descent)
- [Mathematics of Gradient Descent](https://ml-cheatsheet.readthedocs.io/en/latest/gradient_descent.html)

## Feedback
Feel free to reach out or submit an issue if you have any feedback or suggestions.

---

Happy Coding! 🧮
