# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equation and assign in np.array.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Baudhigan D
#RegisterNumber: 212223230028
import numpy as np
A=[[-2,2,-3], [2,1,-6], [-1,-2,0]]
Eigenvalues, Eigenvectors=np. linalg. eig(A)
print ("Eigen values are", Eigenvalues, "and Eigen Vectors are", Eigenvectors)
```
## Output:
![image](https://github.com/baudhigan/EIGENVALUES-AND-EIGENVECTORS/assets/151921158/f538c47c-38b2-4a15-b4d5-6b920770d7a0)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
