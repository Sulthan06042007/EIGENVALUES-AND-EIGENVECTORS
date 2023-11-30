# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import the numpy module to use the bulit-in functions for calculation
### Step 2:
prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
end the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: 
#RegisterNumber: 23004839
import numpy as np
m=([[-2,2,-3],[2,1,-6],[-1,-2,0]])
w,v=np.linalg.eig(m)
print("Eigen values are",w,"and Eigen Vectors are",v)
```

## Output:
![image](https://github.com/Sulthan06042007/EIGENVALUES-AND-EIGENVECTORS/assets/144980103/d32ecc2e-b536-4d82-ab36-48caabc8bb8e)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
