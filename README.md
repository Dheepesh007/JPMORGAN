# SESSION 7 – JPMORGAN (Optimization)

## Aim
To find the minimum value of an energy function using derivative-based optimization.

## Dataset
Synthetic Optimization Function
https://www.kaggle.com/code/optimization-functions

## Objective
To determine the optimal value of x that minimizes the energy function.

## Given Function
E(x) = x² - 6x + 10

## Procedure
Step 1: Define energy function
Step 2: Compute derivative
Step 3: Set derivative = 0
Step 4: Solve for x
Step 5: Display result

## Algorithm
Step 1: Start program
Step 2: Define function E(x)
Step 3: Compute derivative dE/dx
Step 4: Set derivative = 0
Step 5: Solve equation
Step 6: Display minimum point
Step 7: Stop program

## Code Logic
If derivative equals zero → minimum point found

## Python Code
import sympy as sp
x = sp.symbols('x')
E = x**2 - 6*x + 10
solution = sp.solve(sp.diff(E, x), x)
print(solution)

## Output
x = 3

## Result
Minimum energy point identified successfully.

## Industry Application
Used in AI Ops optimization for efficient resource and energy management.

## Tools Used
Python
Sympy
Google Colab
GitHub
