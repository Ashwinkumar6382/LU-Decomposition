# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

Step 1: import numpy module to use bulit in function

step 2: assign matrix a in np.array()

Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

Step 4: given matrix.: end of the module

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Ashwin kumar E
RegisterNumber:212224230026 
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Ashwin kumar E
RegisterNumber: 212224230026
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)

```

## Output1:
<img width="1254" height="582" alt="Screenshot 2025-10-17 093902" src="https://github.com/user-attachments/assets/6a5d9263-9fab-4dfa-8d0d-a0c48a0a77d4" />

## Output2:
<img width="1044" height="305" alt="Screenshot 2025-10-17 093930" src="https://github.com/user-attachments/assets/82a418b5-1242-4b37-b081-ca47f63a7bb9" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

