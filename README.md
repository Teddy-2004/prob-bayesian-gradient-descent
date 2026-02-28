Overview

This assignment explores core machine learning concepts through theoretical derivations, probabilistic modeling, optimization, and practical implementation.

The project is divided into four main parts:

Data Exploration and Preprocessing

Bayesian Learning (Naïve Bayes)

Manual Gradient Descent Derivation

Model Implementation and Analysis

Each section combines mathematical reasoning, implementation, and analytical interpretation.

- Dataset Used
- IMDB Dataset of 50K Movie Reviews

50,000 labeled movie reviews

Binary sentiment classification (Positive / Negative)

Balanced dataset

Used for Bayesian modeling and evaluation

The dataset was provided as part of the assignment.

- Part 1 – Data Exploration & Preprocessing
Objectives:

Load and inspect dataset

Clean text data

Handle missing values

Convert text into numerical representation

Techniques Used:

Pandas for data manipulation

Text preprocessing

Feature extraction

Output:

Cleaned dataset

Structured features ready for modeling

Summary statistics and observations

- Part 2 – Bayesian Learning
Model Used:

Naïve Bayes Classifier

Mathematical Foundation:

Bayes’ Theorem:

P(C | X) = (P(X | C) * P(C)) / P(X)

Under conditional independence assumption:

P(C | X₁, X₂, ..., Xn) ∝ P(C) ∏ P(Xi | C)

Implementation Includes:

Prior probability computation

Likelihood estimation

Posterior prediction

Laplace smoothing

Model evaluation

Evaluation Metrics:

Accuracy

Confusion Matrix

Error analysis

- Part 3 – Manual Gradient Descent
Objective:

Understand optimization through manual derivation.

Included:

Loss function definition

Full derivative derivation

Step-by-step gradient calculation

Manual first iteration

Iterative updates in Python

Visualization of cost reduction

Key Formula:

Gradient Update Rule:

θ := θ - α ∂J(θ)/∂θ

Where:

α = learning rate

J(θ) = loss function

- Part 4 – Model Implementation & Analysis
Objective:

Apply machine learning algorithm and analyze results critically.

Includes:

Mathematical formulation

Model training

Performance evaluation

Error interpretation

Assumptions discussion

Improvement suggestions

Analytical Reflection Covers:

Bias vs variance

Overfitting considerations

Effect of hyperparameters

Model limitations

- Results Summary

Bayesian classifier achieved strong sentiment classification performance.

Gradient descent successfully minimized cost function.

Model behavior analyzed both mathematically and practically.

Clear connection established between theory and implementation.

- Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

- Repository Structure
├── Part1_Data_Preprocessing.ipynb
├── Bayesian.ipynb
├── Gradient_Descent_Manual_Calculation_F3
├── Part4_Model_Analysis.ipynb
├── Gradient_Descent_Manual_Calculation
├── README.md
- Learning Outcomes

Through this assignment, I developed:

Strong understanding of Bayesian probability

Deep comprehension of gradient descent mechanics

Ability to derive optimization mathematically

Practical model implementation skills

Critical model evaluation skills

- Conclusion

This project integrates probability theory, optimization, and applied machine learning into a structured and rigorous workflow.

It demonstrates both mathematical understanding and practical implementation competence.
