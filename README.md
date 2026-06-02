# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from matrix and assign in np.array()
3. Using the np.linalg.solve(), we can find the solutions.
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Daffodil Irene S
RegisterNumber: 212225100006
*/

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np 

from scipy.linalg import lu 

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Daffodil Irene S
RegisterNumber: 212225100006
*/
import numpy as np

A = np.array(eval(input()), dtype=float)
B = np.array(eval(input()), dtype=float)

X = np.linalg.solve(A, B)

print(X)

```

## Output:
<img width="1189" height="561" alt="Screenshot 2026-05-31 170808" src="https://github.com/user-attachments/assets/8b8a8bf1-091c-48ac-80e2-1d9489f8a936" />


<img width="1048" height="200" alt="Screenshot 2026-05-31 170822" src="https://github.com/user-attachments/assets/6d5617d7-ae31-4445-a6c6-a60bd8d96b96" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

