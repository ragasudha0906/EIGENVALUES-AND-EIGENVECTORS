# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the required library numpy as np.
### Step 2: Define the input matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and eigenvectors using print().

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: RAGASUDHA R
#RegisterNumber:212224230215
import numpy as np
matrix=([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigen_values,eigen_vector=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eigen_values,eigen_vector))
```
## Output:
<img width="1293" height="921" alt="python 4" src="https://github.com/user-attachments/assets/e13c0b09-725d-4206-b691-16a451bd5397" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
