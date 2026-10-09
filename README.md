# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Importing os and numpy module packages.
### Step 2: Creating given matrices in code.
### Step 3: Finding solution to the inverse of the matrix.
### Step 4: Print result.

## Program:
####Program to find the inverse of a matrix.
#Developed by: Harish Bakavadh J
#RegisterNumber:26007865
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
B=np.linalg.inv(A)
print(B)
## Output:<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/eff8eb41-f0c5-43ed-a58e-4114f30cd687" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

