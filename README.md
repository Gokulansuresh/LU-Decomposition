# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### 5(a)
### step 1.import numpy for multi- dimentional array operation
### step 2. bring lu from scify.linalg to handel the actual matrix decomposition
### step 3.call the lu(A) funtion.this splits the target matrix into three seperate output matrices P,L AND U
### STEP 4.END program

### 5(b)
### step 1.import numpy for multi- dimentional array operation
### step 2. bring lu from scify.linalg to handel the actual matrix decomposition
### step 3.pass the factorised component (lu,p) along with the right-hand side matrix b into the lu_solve() funtion to compute the solution matrix x
### STEP 4.END program

## Program:
(i) 5(a) to find the L and U matrix
### '''Program to find L and U matrix using LU decomposition.
### Developed by: GOKULAN.S.S
### RegisterNumber: 26018286
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### from scipy.linalg import lu
### A=np.array(eval(input()),dtype=float)
### P,L,U=lu(A)
### print(L)
### print(U)
(ii) 5(b) to find the L and U MATRIX
### '''Program to solve a matrix using LU decomposition.
### Developed by:GOKULAN.S.S
### RegisterNumber: 26018286
'''

### To print X matrix (solution to the equations)
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### from scipy.linalg import lu_factor,lu_solve
### a=np.array(eval(input()))
### b=np.array(eval(input()))
### l,p=lu_factor(a)
### x=lu_solve((l,p),b)
### print(x)



## Output:
## 5A:
<img width="1155" height="851" alt="image" src="https://github.com/user-attachments/assets/987d680c-6856-4ada-8be4-98116191bbcb" />

## 5B:
<img width="1102" height="777" alt="image" src="https://github.com/user-attachments/assets/e1d5cfa0-22d4-411a-9db4-ba39e89bdd27" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

