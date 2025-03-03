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
#Developed By:S VASUNTHARA SAI
#REGISTER NUMBER:212224230297

import numpy as np
A = np.array([[1, 3], [2, 5]])
B = np.array([5, -3])
solution = np.linalg.solve(A, B)
x, y = solution
print(f"[{int(x)}.  {int(y)}.]")
```
## Output:
![image](https://github.com/user-attachments/assets/be7f6bbf-8b3f-47e6-8df6-ace18a8a80f6)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

