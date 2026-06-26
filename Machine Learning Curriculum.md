4-Week Machine Learning Intensive Curriculum

Inspired by Andrew Ng's Machine Learning Specialization

Commitment: 4 Weeks | 5-10 Hours Daily
Methodology: Intuition first -> Math second -> Code third.

Week 1: The Foundations (Linear Regression & Optimization)

Goal: Understand how machines learn continuous numbers (like prices) and the engine that makes learning possible.

[ ] Day 1: Intuition & The "Line of Best Fit"

Concept: What is ML? Supervised vs. Unsupervised.

Math: High school algebra ($y = mx + b$ vs $\hat{y} = wx + b$).

Daily Assignment: Identify features ($X$) and targets ($y$) in 3 real-world scenarios.

[ ] Day 2: The Language of Data (Linear Algebra & NumPy)

Concept: How computers store and manipulate massive amounts of data instantly.

Math: Vectors, Matrices, and Dot Products.

Code: Introduction to NumPy arrays.

Daily Assignment: Matrix multiplication by hand, then verify it using NumPy.

[ ] Day 3: The Cost Function (Measuring "Wrongness")

Concept: The "Mountain" analogy. How do we score a model?

Math: Mean Squared Error (MSE) formulation.

Daily Assignment: Calculate MSE for a tiny dataset by hand and in Python.

[ ] Day 4: Calculus Refresher (The Slope)

Concept: How to find the direction of the bottom of the valley.

Math: Derivatives, Partial Derivatives, and the Power Rule.

Daily Assignment: Find the derivative of 5 simple algebraic functions.

[ ] Day 5: Gradient Descent (The Engine of Learning)

Concept: The "Blindfolded Hiker". Explaining Learning Rates (step size) and Epochs.

Math: The Gradient Descent update rule $\theta_j := \theta_j - \alpha \frac{\partial}{\partial \theta_j} J(\theta)$

Daily Assignment: Trace one "step" of Gradient Descent on paper.

[ ] Day 6: Multiple Features & Vectorization

Concept: Predicting price based on size, bedrooms, AND age simultaneously.

Math: Multi-dimensional matrix multiplication.

Daily Assignment: Translate a slow Python for loop into a lightning-fast vectorized NumPy operation.

[ ] Day 7: WEEKLY ASSIGNMENT 1

Project: The Perfected House Price Predictor. Build a Linear Regression model from absolute scratch using NumPy arrays. Implement the cost function and gradient descent mathematically.

Week 2: Classification & The Reality of Data (Logistic Regression)

Goal: Teach the computer how to make Yes/No decisions and handle messy, real-world data.

[ ] Day 8: Introduction to Classification

Concept: Why Linear Regression fails for Yes/No questions.

Math: The concept of a decision boundary.

Daily Assignment: Plot a dataset and draw a decision boundary manually.

[ ] Day 9: The Sigmoid Function

Concept: Squishing infinite numbers into a probability between 0% and 100%.

Math: $g(z) = \frac{1}{1 + e^{-z}}$

Daily Assignment: Code the Sigmoid function and plot its S-curve using Matplotlib.

[ ] Day 10: Logistic Regression & Log Loss

Concept: Punishing the model for being confidently wrong.

Math: Binary Cross-Entropy (Log Loss) Cost Function.

Daily Assignment: Calculate the cost of 3 different model predictions.

[ ] Day 11: Feature Scaling & Normalization

Concept: Why a house's age (1995) crushes the number of bedrooms (3) in math, and how to fix it.

Math: Z-score normalization (Mean and Standard Deviation).

Daily Assignment: Write a Python function to normalize a dataset from scratch.

[ ] Day 12: The Goldilocks Problem (Overfitting & Underfitting)

Concept: Memorization vs. Learning (Variance vs. Bias).

Math: Train/Validation/Test splits.

Daily Assignment: Diagnose learning curves (graphs) to spot overfitting.

[ ] Day 13: Regularization (Keeping things simple)

Concept: Penalizing the model for being too complex.

Math: L1 (Lasso) and L2 (Ridge) penalties added to the cost function.

Daily Assignment: Add an L2 penalty to Day 10's Cost Function.

[ ] Day 14: WEEKLY ASSIGNMENT 2

Project: The Spam Filter. Build a Logistic Regression model from scratch that reads emails and outputs a probability (0 to 1) of whether it is Spam or Not Spam.

Week 3: Deep Learning Foundations (Neural Networks)

Goal: Move from single equations to interconnected networks of equations modeled after the human brain.

[ ] Day 15: Non-linear Boundaries

Concept: What if the data is shaped like a circle? Why straight lines aren't enough.

Math: Combining features (Polynomials).

Daily Assignment: Create polynomial features to draw a curved boundary.

[ ] Day 16: Anatomy of a Neural Network

Concept: Neurons, Hidden Layers, and Architecture.

Math: A network is just Logistic Regression stacked on top of Logistic Regression.

Daily Assignment: Map out the architecture (dimensions) of a 3-layer network on paper.

[ ] Day 17: Forward Propagation

Concept: How data flows from input to the final guess.

Math: Matrix multiplication across multiple layers.

Daily Assignment: Code the Forward Propagation of a 2-layer network in Python using NumPy.

[ ] Day 18: Backpropagation (Intuition)

Concept: The "Blame Game." How does the network know which specific neuron made the mistake?

Math: The Chain Rule (Calculus).

Daily Assignment: Calculate the chain rule for a 3-step nested mathematical function.

[ ] Day 19: Backpropagation (Code)

Concept: Translating the blame game into Python.

Math: Gradients of weight matrices.

Daily Assignment: Implement the backward pass for yesterday's network.

[ ] Day 20: Activations & Advanced Optimization

Concept: Why we use ReLU instead of Sigmoid, and how the Adam Optimizer speeds up learning.

Math: Equations of ReLU/Softmax and the concept of "Momentum" in optimization.

Daily Assignment: Swap Sigmoid for ReLU in your network and observe the training speed difference.

[ ] Day 21: WEEKLY ASSIGNMENT 3

Project: Handwritten Digit Recognizer. Build a 2-layer Neural Network from scratch using the famous MNIST dataset to recognize handwritten numbers from images.

Week 4: Applied Machine Learning & Advanced Algorithms

Goal: Broaden the toolkit to include non-calculus based algorithms, recommendation engines, and industry-standard practices.

[ ] Day 22: Error Analysis & Evaluation Metrics

Concept: Why "99% Accuracy" can be a lie (The Cancer Prediction paradox) and Ng's iterative cycle for improving models.

Math: Confusion Matrices, Precision, Recall, and F1-Score.

Daily Assignment: Calculate Precision and Recall by hand. Perform error analysis on your Week 3 digits model.

[ ] Day 23: Decision Trees & Random Forests

Concept: Playing "20 Questions" with data, and the "Wisdom of the Crowd" (Ensemble learning).

Math: Information Gain (Entropy) and Bagging.

Daily Assignment: Calculate Information Gain by hand, then train a Random Forest using Scikit-Learn.

[ ] Day 24: Unsupervised Learning (K-Means & Anomaly Detection)

Concept: Finding groups (clustering) and finding weird data (fraud detection) without target labels.

Math: Euclidean Distance and Gaussian Distribution.

Daily Assignment: Code K-Means from scratch to group customers by purchasing habits.

[ ] Day 25: Recommender Systems (Collaborative Filtering)

Concept: How Netflix knows what movie you want to watch next.

Math: Matrix Factorization.

Daily Assignment: Build a mini-recommendation system for a 5-user, 5-movie dataset.

[ ] Day 26: Moving to Scikit-Learn (Industry Standard)

Concept: Translating all our scratch-built knowledge into professional, highly optimized code.

Daily Assignment: Re-write Week 1 and Week 2 projects in just 10 lines of code using Scikit-Learn.

[ ] Day 27 & 28: COURSE MILESTONE PROJECT

Project: The End-to-End Pipeline. You will be given a raw, messy, real-world dataset (e.g., Predicting Heart Disease or Titanic Survival). You must clean it, engineer features, test 3 different models (Logistic, Neural Network, Random Forest), evaluate them using precision/recall, and choose the best one.

End of Course. You are now fundamentally equipped to understand any modern Machine Learning architecture.