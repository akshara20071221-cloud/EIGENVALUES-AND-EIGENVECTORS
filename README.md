# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the required libraries os and numpy.
### Step 2: Set the environment variable and define the matrix using np.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Store the eigenvalues and eigenvectors in variables and display the result using print().

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[4,2],[2,4]])
eig_val,eig_vec=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_val,eig_vec))
```

## Output:
<img width="1266" height="157" alt="image" src="https://github.com/user-attachments/assets/df9662e3-398d-41d0-8d68-41a7adfb2e21" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
