# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
# program to find a solution to a system of linear equations
# Developed by : Arunachalam.M
# RegisterNumber : 212225230019
import numpy as np
A = np.array([[1,-3],[3,1]])
B=np.array([0,10])
C=np.linalg.solve(A,B)
print(C)
## Output:
<img width="760" height="272" alt="Screenshot 2026-05-23 212333" src="https://github.com/user-attachments/assets/a6b1c03d-752c-4fbb-a588-d657a7db1871" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

