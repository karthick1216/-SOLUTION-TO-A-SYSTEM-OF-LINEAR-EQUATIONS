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
#Developed by: Karthick . S
#RegisterNumber:212224230114

import numpy as np
a=[[1,-3],[3,1]]
b=np.array([0,10])
c=np.linalg.solve(a,b)
print(c)
```

## Output:
![Screenshot 2025-04-22 230648](https://github.com/user-attachments/assets/90ff007b-acf2-46b0-966a-df89bd0927a7)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

