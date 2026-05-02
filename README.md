# MAI_EXP2
# RANK-OF-A-MATRIX
# Name:POOJA PRIYA B
# Reg no: 212224230196
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Read the matrix.
### Step 2:Convert the matrix into row echelon form using row operations.
### Step 3:Count the number of non-zero rows.
### Step 4:That count is the rank of the matrix. 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: POOJA PRIYA.B
#RegisterNumber:212224230196

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A) 
print(rank)

```
## Output:

<img width="632" height="295" alt="image" src="https://github.com/user-attachments/assets/7beeeb29-cc53-4531-8984-2111d36b21d6" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
