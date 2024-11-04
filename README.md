# Gradient Descent DEMO

## Overview
This repository demonstrates the implementation of gradient descent and stochastic gradient descent (SGD) algorithms. It visualizes the parameter optimization process for a simple linear regression model, comparing the optimization trajectory to the true coefficient values. The project uses Python and Jupyter Notebook to illustrate and explore the mechanics of gradient descent.

## Purpose
This project is part of my initial learning journey into deep learning. It serves as an exercise in understanding the fundamentals of gradient descent, which is a foundational optimization technique in machine learning and deep learning. By visualizing the parameter update process, I was able to gain a deeper insight into how gradient descent works.

## Features
- **Feature Scaling (Normalization)**: Applies a custom normalization technique to scale some feature to a specified range. This ensures the model’s inputs are on a similar scale, which helps in stabilizing the gradient descent updates and achieving a smoother convergence path.
- **Full-Batch Gradient Descent**: Calculates gradients using the entire dataset at each iteration.
- **Stochastic Gradient Descent (SGD)**: Calculates gradients for each data point individually, which provides a more dynamic but potentially noisier update path.
- **Visualization of Parameter Trajectory**: Plots the optimization paths in the parameter space to show how the parameters move toward the true coefficient values.
- **Loss Function Plotting**: Tracks and visualizes the squared loss over iterations to observe convergence behavior.

## Requirements
- Python 3.x
- Libraries: `numpy`, `matplotlib`, `sklearn`
