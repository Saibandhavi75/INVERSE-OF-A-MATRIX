# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation 
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.matrix_inverse(), we can find the rank of the given matrix. 
### Step 4: 
End the program

## Program:

#Program to find the inverse of a matrix.

#Developed by: A.Sai bandhavi

#RegisterNumber:21005573

import numpy as np

A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])

inverse=np.linalg.inv(A)

print(inverse)

## Output:
![output](https://github.com/Saibandhavi75/INVERSE-OF-A-MATRIX/blob/main/inverse%20of%20matrix.png?raw=true)

## Result:
Thus the inverse of given matrix is successfully solved using python program

