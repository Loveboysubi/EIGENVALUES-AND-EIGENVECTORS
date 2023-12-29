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
prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Subishesh P
#RegisterNumber:23003621
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/Loveboysubi/EIGENVALUES-AND-EIGENVECTORS/assets/138970879/85a0b097-7d20-459f-bd5a-12f2185e5a85)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
