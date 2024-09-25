# Date :
# Exp no:4
# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation</br>

Step 2:
Prepare the lists from each equations and assign in np.array()</br>

Step 3:
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix</br>

Step 4:
End the program</br>

## Program:
#Program to find the eigen values and eigen vectors.</br>
#Developed by: Rudesh kanna R</br>
#RegisterNumber:24900303</br>
import numpy as np</br>
A = np.array([[4,2],[2,4]])</br>
values, vectors = np.linalg.eig(A)</br>
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))</br>
## Output:
![image](https://github.com/user-attachments/assets/5739a9aa-c06e-479d-8a3f-bfc1ee262e6d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
