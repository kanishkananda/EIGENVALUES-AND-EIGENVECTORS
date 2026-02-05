# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: prepare the lists from each equationns and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:end the program 

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: N.Kanishka
#RegisterNumber:212225230127
import numpy as np
A=np.array([[2,2],[1,3]])
Values,vector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(Values,vector))

## Output:
<img width="1869" height="923" alt="Maths Exp-4" src="https://github.com/user-attachments/assets/cffe6d60-a5c0-4690-80ea-eccba08ca926" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
