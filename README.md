# Date :
# Exp no:4
# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Rudesh kanna R
#RegisterNumber:24900303
import numpy as np
A = np.array([[4,2],[2,4]])
values, vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
## Output:
![image](https://github.com/user-attachments/assets/5739a9aa-c06e-479d-8a3f-bfc1ee262e6d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
