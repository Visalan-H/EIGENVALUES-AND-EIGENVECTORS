# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Visalan H
#RegisterNumber:212223240183

import numpy as np
A=np.array([[4,2],[2,4]])
va,ve=np.linalg.eig(A)
print(f"Eigen values are {va} and Eigen Vectors are {ve}")
```
## Output:
![image](https://github.com/Visalan-H/EIGENVALUES-AND-EIGENVECTORS/assets/152077751/a9e65fcf-a803-4102-b8c3-d96b12cd9818)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
