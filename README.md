# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import numpy as np
### Step 2:
put the given values in the np.array command
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
print the program and get the output
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:S.Subashini 
#RegisterNumber:22009344
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```


## Output:
![output](/Screenshot_20221228_072350.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
