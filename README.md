# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: R Anirudh 
RegisterNumber: 23003227
*/
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: R Anirudh
RegisterNumber: 23003227
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(a)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
i) ![Screenshot (25)](https://github.com/anushanirudh/LU-Decomposition/assets/151725737/3aa89360-cf6d-4fc8-a44b-a2bf6be70fec)

ii) ![Screenshot (26)](https://github.com/anushanirudh/LU-Decomposition/assets/151725737/9a60a649-f04e-4ada-a913-9f65dbebb8cc)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

