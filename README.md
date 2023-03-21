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
#Developed by: s.Deepika
#RegisterNumber:21222223008
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
s=np.linalg.solve(A,B)
print(s)


## Output:

![EX 1](https://user-images.githubusercontent.com/119393935/226540535-4fa1974c-fb65-40cd-8278-f56efdb00f86.png)




## Result:
Thus the solutions for the linear equations are successfully solved using python program

