# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Given a matrix A of Size m x n
### Step 2: Use a numerical method such as Singular Value Decomposition (SVD) or Gaussian Elimination to compute the rank of the matrix.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Print the rank.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: priyan
#RegisterNumber:24000051

import numpy as np
matrix=np.array([[5,-3,-10],[2,3,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(matrix)
print(rank)
```

## Output:
![output](./PNG1.png)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.