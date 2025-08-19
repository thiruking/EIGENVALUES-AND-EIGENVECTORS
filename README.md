# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End of program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: THIRUMALAI K
#RegisterNumber: 212224240176
import numpy as np
A = np.array([[4, 2],
              [2, 4]])
evalue, evectors = np.linalg.eig(A)
print(f"Eigen values are {evalue} and Eigen Vectors are {evectors}")

```

## Output:
<img width="1485" height="871" alt="image" src="https://github.com/user-attachments/assets/44e9c110-389b-420a-8cdd-6e43d525c031" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
