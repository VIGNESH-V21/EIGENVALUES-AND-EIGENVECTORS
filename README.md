# EX-4 EIGENVALUES-AND-EIGENVECTORS
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
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Vignesh V
#RegisterNumber: 212224040357
import numpy as np
A= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {} ".format(values,vector))
```

## Output:

<img width="881" height="255" alt="image" src="https://github.com/user-attachments/assets/cf2eeb68-3116-43a7-a2a0-58f54181cce9" />

<img width="866" height="215" alt="image" src="https://github.com/user-attachments/assets/62cb254b-8166-498a-b2a0-48064465222d" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
