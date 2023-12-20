# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array().
### Step 3:
Using the np.linalg.matrix_rank(),we can find the solution.
### Step 4: 
End the program.
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: VINNUSH KUMARL S
#RegisterNumber:23012349
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![image](https://github.com/vinnush147/RANK-OF-A-MATRIX/assets/147139234/b1ff4346-1848-4357-a2be-2d8a3477686d)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

