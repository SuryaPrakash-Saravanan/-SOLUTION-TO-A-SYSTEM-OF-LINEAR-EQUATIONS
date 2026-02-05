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
```
#Program to find the solution for the given linear equations.
#Developed by: Surya Prakash S
#RegisterNumber: 25014536 / 212225040443

import numpy as np
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B = np.array([-9,4,-1])
x = np.linalg.solve(A,B)
print(x)
```
## Output:
<img width="394" height="159" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/e326c5c7-a2d6-4af2-964a-47f1ef3ce77b" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

