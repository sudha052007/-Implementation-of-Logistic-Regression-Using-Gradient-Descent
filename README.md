# Implementation-of-Logistic-Regression-Using-Gradient-Descent

## AIM:
To write a program to implement the the Logistic Regression Using Gradient Descent.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1: Import the required Python libraries and load the dataset containing input features and target class labels.

2: Initialize the model parameters (weights and bias) and set the learning rate and number of iterations.

3: Apply the logistic (sigmoid) function and use gradient descent to update the parameters by minimizing the error.

4: Use the trained logistic regression model to predict the class label and evaluate the model performance.
## Program:
```
/*
Program to implement the the Logistic Regression Using Gradient Descent.
Developed by: sudharshini.G
RegisterNumber:  25013290
*/
/*
import numpy as np
import matplotlib.pyplot as plt

# Sample dataset
X = np.array([0,1,2,3,4,5,6,7,8,9])
Y = np.array([0,0,0,0,0,1,1,1,1,1])

# Initialize parameters
w = 0
b = 0

learning_rate = 0.01
epochs = 1000
n = len(X)

# Sigmoid function
def sigmoid(z):
    return 1 / (1 + np.exp(-z))

# Gradient Descent
for i in range(epochs):

    # Linear model
    z = w * X + b

    # Prediction
    y_pred = sigmoid(z)

    # Gradients
    dw = (1/n) * np.sum((y_pred - Y) * X)
    db = (1/n) * np.sum(y_pred - Y)

    # Update parameters
    w = w - learning_rate * dw
    b = b - learning_rate * db

print("Weight:", w)
print("Bias:", b)

# Predictions
z = w * X + b
prob = sigmoid(z)

plt.scatter(X, Y, color="blue", label="Actual Data")
plt.plot(X, prob, color="red", label="Logistic Curve")
plt.xlabel("X")
plt.ylabel("Probability")
plt.legend()
plt.show() 
*/
```

## Output:
<img width="675" height="470" alt="image" src="https://github.com/user-attachments/assets/9338813c-8995-4064-aab4-217cd6693f9e" />


## Result:
Thus the program to implement the the Logistic Regression Using Gradient Descent is written and verified using python programming.

