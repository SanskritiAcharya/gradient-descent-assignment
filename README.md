# Understanding and Implementing Gradient Descent

Course assignment for Basics of Neural Networks and Deep Learning.

`gradient_descent_assignment.ipynb` covers:

1. Gradient descent on a quadratic error surface with five learning rates
2. How the learning rate affects reaching the global minimum on a non-convex surface (500 random starts)
3. A 5-hidden-layer network on spiral data trained with no normalization, batch normalization, and layer normalization (all forward and backward passes written by hand in NumPy)

No external dataset is needed. All data is generated inside the notebook.

## Run

```
pip install -r requirements.txt
jupyter notebook gradient_descent_assignment.ipynb
```

Figures and a results log are written to `figures/`.
