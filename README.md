# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import NumPy library.
### Step 2: 
Define the matrix for which eigenvalues and eigenvectors are required.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the results.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: BALA SARAVANAN K
#RegisterNumber: 212224230031

import numpy as np

A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values , vector = np.linalg.eig(A)

print("Eigen values are",values,"and Eigen Vectors are",vector)
```
## Output:
<img width="2534" height="1441" alt="Screenshot 2025-08-28 025053" src="https://github.com/user-attachments/assets/03bdf082-fa83-4701-abfe-9bd24a176430" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
