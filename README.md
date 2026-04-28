# Implementation-of-Linear-Regression-Using-Gradient-Descent

## AIM:
To write a program to predict the profit of a city using the linear regression model with gradient descent.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Read the input values X (independent variable) and y (dependent variable).

2.Assume a linear relationship between X and y using the for p

3.Predict the output values using: pp

4.Display the slope 𝑚 and intercept c, and plot:

*Actual data points

*Regression line

## Program:
```
/*
Program to implement the linear regression using gradient descent.
Developed by: Vedha M
RegisterNumber:25012201
*/
import numpy as np
from sklearn.linear_model import LinearRegression
import matplotlib.pyplot as plt

# Sample data (X = input, y = output)
X = np.array([1, 2, 3, 4, 5]).reshape(-1, 1)
y = np.array([2, 4, 5, 4, 5])

# Create and train the model
model = LinearRegression()
model.fit(X, y)

# Make predictions
y_pred = model.predict(X)

# Print results
print("Slope (Coefficient):", model.coef_[0])
print("Intercept:", model.intercept_)

# Plot the data and regression line
plt.scatter(X, y, color='blue', label='Actual Data')
plt.plot(X, y_pred, color='red', label='Regression Line')
plt.xlabel("X")
plt.ylabel("y")
plt.legend()

Program to implement the linear regression using gradient descent.
Developed by: KALPANA M
RegisterNumber: 212225240064 

```

## Output:
<img width="1103" height="620" alt="Screenshot 2026-04-28 090105" src="https://github.com/user-attachments/assets/b2e85027-4fa6-4325-8946-39054392147f" />



## Result:
Thus the program to implement the linear regression using gradient descent is written and verified using python programming.
